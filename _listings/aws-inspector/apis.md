---
name: AWS Inspector
x-slug: aws-inspector
description: Amazon Inspector is an automated security assessment service that helps
  improve the security and compliance of applications deployed on AWS. Amazon Inspector
  automatically assesses applications for vulnerabilities or deviations from best
  practices. After performing an assessment, Amazon Inspector produces a detailed
  list of security findings prioritized by level of severity.To help you get started
  quickly, Amazon Inspector includes a knowledge base of hundreds of rules mapped
  to common security best practices and vulnerability definitions. Examples of built-in
  rules include checking for remote root login being enabled, or vulnerable software
  versions installed. These rules are regularly updated by AWS security researchers.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Assessments
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/assessments/master/_listings/aws-inspector/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Inspector API - List Assessment Run Agents
  x-api-slug: actionlistassessmentrunagents-get
  description: |-
    Lists the agents of the assessment runs that are specified by the ARNs of the
             assessment runs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assessments/master/_listings/aws-inspector/actionlistassessmentrunagents-get-openapi.md
- name: AWS Inspector API - Create Assessment Target
  x-api-slug: actioncreateassessmenttarget-get
  description: |-
    Creates a new assessment target using the ARN of the resource group that is generated
             by.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assessments/master/_listings/aws-inspector/actioncreateassessmenttarget-get-openapi.md
- name: AWS Inspector API - Create Assessment Template
  x-api-slug: actioncreateassessmenttemplate-get
  description: |-
    Creates an assessment template for the assessment target that is specified by the ARN
             of the assessment target.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assessments/master/_listings/aws-inspector/actioncreateassessmenttemplate-get-openapi.md
- name: AWS Inspector API - Delete Assessment Run
  x-api-slug: actiondeleteassessmentrun-get
  description: |-
    Deletes the assessment run that is specified by the ARN of the assessment
             run.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assessments/master/_listings/aws-inspector/actiondeleteassessmentrun-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assessments/master/_listings/aws-inspector/actiondeleteassessmentrun-get-openapi.md
- name: AWS Inspector API - Delete Assessment Target
  x-api-slug: actiondeleteassessmenttarget-get
  description: |-
    Deletes the assessment target that is specified by the ARN of the assessment
             target.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assessments/master/_listings/aws-inspector/actiondeleteassessmenttarget-get-openapi.md
- name: AWS Inspector API - Delete Assessment Template
  x-api-slug: actiondeleteassessmenttemplate-get
  description: |-
    Deletes the assessment template that is specified by the ARN of the assessment
             template.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assessments/master/_listings/aws-inspector/actiondeleteassessmenttemplate-get-openapi.md
- name: AWS Inspector API - Describe Assessment Runs
  x-api-slug: actiondescribeassessmentruns-get
  description: |-
    Describes the assessment runs that are specified by the ARNs of the assessment
             runs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assessments/master/_listings/aws-inspector/actiondescribeassessmentruns-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assessments/master/_listings/aws-inspector/actiondescribeassessmentruns-get-openapi.md
- name: AWS Inspector API - Describe Assessment Targets
  x-api-slug: actiondescribeassessmenttargets-get
  description: |-
    Describes the assessment targets that are specified by the ARNs of the assessment
             targets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assessments/master/_listings/aws-inspector/actiondescribeassessmenttargets-get-openapi.md
- name: AWS Inspector API - Describe Assessment Templates
  x-api-slug: actiondescribeassessmenttemplates-get
  description: |-
    Describes the assessment templates that are specified by the ARNs of the assessment
             templates.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assessments/master/_listings/aws-inspector/actiondescribeassessmenttemplates-get-openapi.md
- name: AWS Inspector API - List Assessment Run Agents
  x-api-slug: actionlistassessmentrunagents-get
  description: |-
    Lists the agents of the assessment runs that are specified by the ARNs of the
             assessment runs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assessments/master/_listings/aws-inspector/actionlistassessmentrunagents-get-openapi.md
- name: AWS Inspector API - List Assessment Runs
  x-api-slug: actionlistassessmentruns-get
  description: |-
    Lists the assessment runs that correspond to the assessment templates that are
             specified by the ARNs of the assessment templates.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assessments/master/_listings/aws-inspector/actionlistassessmentruns-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assessments/master/_listings/aws-inspector/actionlistassessmentruns-get-openapi.md
- name: AWS Inspector API - List Assessment Targets
  x-api-slug: actionlistassessmenttargets-get
  description: Lists the ARNs of the assessment targets within this AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assessments/master/_listings/aws-inspector/actionlistassessmenttargets-get-openapi.md
- name: AWS Inspector API - List Assessment Templates
  x-api-slug: actionlistassessmenttemplates-get
  description: |-
    Lists the assessment templates that correspond to the assessment targets that are
             specified by the ARNs of the assessment targets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assessments/master/_listings/aws-inspector/actionlistassessmenttemplates-get-openapi.md
- name: AWS Inspector API - Start Assessment Run
  x-api-slug: actionstartassessmentrun-get
  description: Starts the assessment run specified by the ARN of the assessment template.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assessments/master/_listings/aws-inspector/actionstartassessmentrun-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assessments/master/_listings/aws-inspector/actionstartassessmentrun-get-openapi.md
- name: AWS Inspector API - Stop Assessment Run
  x-api-slug: actionstopassessmentrun-get
  description: |-
    Stops the assessment run that is specified by the ARN of the assessment
             run.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assessments/master/_listings/aws-inspector/actionstopassessmentrun-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assessments/master/_listings/aws-inspector/actionstopassessmentrun-get-openapi.md
- name: AWS Inspector API - Update Assessment Target
  x-api-slug: actionupdateassessmenttarget-get
  description: |-
    Updates the assessment target that is specified by the ARN of the assessment
             target.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assessments/master/_listings/aws-inspector/actionupdateassessmenttarget-get-openapi.md
- name: AWS Inspector API - List Assessment Run Agents
  x-api-slug: actionlistassessmentrunagents-get
  description: |-
    Lists the agents of the assessment runs that are specified by the ARNs of the
             assessment runs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assessments/master/_listings/aws-inspector/actionlistassessmentrunagents-get-openapi.md
- name: AWS Inspector API - List Assessment Run Agents
  x-api-slug: actionlistassessmentrunagents-get
  description: |-
    Lists the agents of the assessment runs that are specified by the ARNs of the
             assessment runs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assessments/master/_listings/aws-inspector/actionlistassessmentrunagents-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.identity.and.access.management.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.inspector.stack.network
- type: x-documentation
  url: http://docs.aws.amazon.com/inspector/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/inspector/faqs/
- type: x-getting-started
  url: https://docs.aws.amazon.com/inspector/latest/userguide/inspector_quickstart.html
- type: x-partners
  url: https://aws.amazon.com/inspector/partners/
- type: x-pricing
  url: https://aws.amazon.com/inspector/pricing/
- type: x-testimonials
  url: https://aws.amazon.com/inspector/customers/
- type: x-website
  url: https://aws.amazon.com/inspector/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---