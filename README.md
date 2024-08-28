<p align="center">
  <img align="center" src="https://github.com/prowler-cloud/prowler/blob/master/docs/img/prowler-logo-black.png#gh-light-mode-only" width="50%" height="50%">
  <img align="center" src="https://github.com/prowler-cloud/prowler/blob/master/docs/img/prowler-logo-white.png#gh-dark-mode-only" width="50%" height="50%">
</p>
<p align="center">
  <b><i>Prowler SaaS </b> and <b>Prowler Open Source</b> are as dynamic and adaptable as the environment they’re meant to protect. Trusted by the leaders in security.
</p>
<p align="center">
<b>Learn more at <a href="https://prowler.com">prowler.com</i></b>
</p>

<p align="center">
<a href="https://join.slack.com/t/prowler-workspace/shared_invite/zt-1hix76xsl-2uq222JIXrC7Q8It~9ZNog"><img width="30" height="30" alt="Prowler community on Slack" src="https://github.com/prowler-cloud/prowler/assets/38561120/3c8b4ec5-6849-41a5-b5e1-52bbb94af73a"></a>
  <br>
<a href="https://join.slack.com/t/prowler-workspace/shared_invite/zt-1hix76xsl-2uq222JIXrC7Q8It~9ZNog">Join our Prowler community!</a>
</p>
<hr>
<p align="center">
  <a href="https://join.slack.com/t/prowler-workspace/shared_invite/zt-1hix76xsl-2uq222JIXrC7Q8It~9ZNog"><img alt="Slack Shield" src="https://img.shields.io/badge/slack-prowler-brightgreen.svg?logo=slack"></a>
  <a href="https://pypi.org/project/prowler/"><img alt="Python Version" src="https://img.shields.io/pypi/v/prowler.svg"></a>
  <a href="https://pypi.python.org/pypi/prowler/"><img alt="Python Version" src="https://img.shields.io/pypi/pyversions/prowler.svg"></a>
  <a href="https://pypistats.org/packages/prowler"><img alt="PyPI Prowler Downloads" src="https://img.shields.io/pypi/dw/prowler.svg?label=prowler%20downloads"></a>
  <a href="https://hub.docker.com/r/toniblyx/prowler"><img alt="Docker Pulls" src="https://img.shields.io/docker/pulls/toniblyx/prowler"></a>
  <a href="https://hub.docker.com/r/toniblyx/prowler"><img alt="Docker" src="https://img.shields.io/docker/cloud/build/toniblyx/prowler"></a>
  <a href="https://hub.docker.com/r/toniblyx/prowler"><img alt="Docker" src="https://img.shields.io/docker/image-size/toniblyx/prowler"></a>
  <a href="https://gallery.ecr.aws/prowler-cloud/prowler"><img width="120" height=19" alt="AWS ECR Gallery" src="https://user-images.githubusercontent.com/3985464/151531396-b6535a68-c907-44eb-95a1-a09508178616.png"></a>
  <a href="https://codecov.io/gh/prowler-cloud/prowler"><img src="https://codecov.io/gh/prowler-cloud/prowler/graph/badge.svg?token=OflBGsdpDl"/></a>
</p>
<p align="center">
  <a href="https://github.com/prowler-cloud/prowler"><img alt="Repo size" src="https://img.shields.io/github/repo-size/prowler-cloud/prowler"></a>
  <a href="https://github.com/prowler-cloud/prowler/issues"><img alt="Issues" src="https://img.shields.io/github/issues/prowler-cloud/prowler"></a>
  <a href="https://github.com/prowler-cloud/prowler/releases"><img alt="Version" src="https://img.shields.io/github/v/release/prowler-cloud/prowler?include_prereleases"></a>
  <a href="https://github.com/prowler-cloud/prowler/releases"><img alt="Version" src="https://img.shields.io/github/release-date/prowler-cloud/prowler"></a>
  <a href="https://github.com/prowler-cloud/prowler"><img alt="Contributors" src="https://img.shields.io/github/contributors-anon/prowler-cloud/prowler"></a>
  <a href="https://github.com/prowler-cloud/prowler"><img alt="License" src="https://img.shields.io/github/license/prowler-cloud/prowler"></a>
  <a href="https://twitter.com/ToniBlyx"><img alt="Twitter" src="https://img.shields.io/twitter/follow/toniblyx?style=social"></a>
  <a href="https://twitter.com/prowlercloud"><img alt="Twitter" src="https://img.shields.io/twitter/follow/prowlercloud?style=social"></a>
</p>
<hr>
<p align="center">
  <img align="center" src="/docs/img/prowler-cli-quick.gif" width="100%" height="100%">
</p>

# Description

**Prowler** is an Open Source security tool to perform AWS, Azure, Google Cloud and Kubernetes security best practices assessments, audits, incident response, continuous monitoring, hardening and forensics readiness, and also remediations! We have Prowler CLI (Command Line Interface) that we call Prowler Open Source and a service on top of it that we call <a href="https://prowler.com">Prowler SaaS</a>.

## Prowler CLI

```console
prowler <provider>
```
![Prowler CLI Execution](docs/img/short-display.png)

## Prowler Dashboard

```console
prowler dashboard
```
![Prowler Dashboard](docs/img/dashboard.png)

It contains hundreds of controls covering CIS, NIST 800, NIST CSF, CISA, RBI, FedRAMP, PCI-DSS, GDPR, HIPAA, FFIEC, SOC2, GXP, AWS Well-Architected Framework Security Pillar, AWS Foundational Technical Review (FTR), ENS (Spanish National Security Scheme) and your custom security frameworks.

| Provider | Checks | Services | [Compliance Frameworks](https://docs.prowler.com/projects/prowler-open-source/en/latest/tutorials/compliance/) | [Categories](https://docs.prowler.com/projects/prowler-open-source/en/latest/tutorials/misc/#categories) |
|---|---|---|---|---|
| AWS | 385 | 67 -> `prowler aws --list-services` | 28 -> `prowler aws --list-compliance` | 7 -> `prowler aws --list-categories` |
| GCP | 77 | 13 -> `prowler gcp --list-services` | 1 -> `prowler gcp --list-compliance` | 2 -> `prowler gcp --list-categories`|
| Azure | 135 | 16 -> `prowler azure --list-services` | 2 -> `prowler azure --list-compliance` | 2 -> `prowler azure --list-categories` |
| Kubernetes | 83 | 7 -> `prowler kubernetes --list-services` | 1 -> `prowler kubernetes --list-compliance` | 7 -> `prowler kubernetes --list-categories` |

# 💻 Installation

## Pip package
Prowler is available as a project in [PyPI](https://pypi.org/project/prowler-cloud/), thus can be installed using pip with Python >= 3.9, < 3.13:

```console
pip install prowler
prowler -v
```
>More details at [https://docs.prowler.com](https://docs.prowler.com/projects/prowler-open-source/en/latest/)

## Containers

The available versions of Prowler are the following:

- `latest`: in sync with `master` branch (bear in mind that it is not a stable version)
- `v3-latest`: in sync with `v3` branch (bear in mind that it is not a stable version)
- `<x.y.z>` (release): you can find the releases [here](https://github.com/prowler-cloud/prowler/releases), those are stable releases.
- `stable`: this tag always point to the latest release.
- `v3-stable`: this tag always point to the latest release for v3.

The container images are available here:

- [DockerHub](https://hub.docker.com/r/toniblyx/prowler/tags)
- [AWS Public ECR](https://gallery.ecr.aws/prowler-cloud/prowler)

## From GitHub

Python >= 3.9, < 3.13 is required with pip and poetry:

```
git clone https://github.com/prowler-cloud/prowler
cd prowler
poetry shell
poetry install
python prowler.py -v
```
> If you want to clone Prowler from Windows, use `git config core.longpaths true` to allow long file paths.
# 📐✏️ High level architecture

You can run Prowler from your workstation, a Kubernetes Job, a Google Compute Engine, an Azure VM, an EC2 instance, Fargate or any other container, CloudShell and many more.

![Architecture](docs/img/architecture.png)

# Deprecations from v3

## General
- `Allowlist` now is called `Mutelist`.
- The `--quiet` option has been deprecated, now use the `--status` flag to select the finding's status you want to get from PASS, FAIL or MANUAL.
- All `INFO` finding's status has changed to `MANUAL`.
- The CSV output format is common for all the providers.

We have deprecated some of our outputs formats:
- The native JSON is replaced for the JSON [OCSF](https://schema.ocsf.io/) v1.1.0, common for all the providers.

## AWS
- Deprecate the AWS flag --sts-endpoint-region since we use AWS STS regional tokens.
- To send only FAILS to AWS Security Hub, now use either `--send-sh-only-fails` or `--security-hub --status FAIL`.


# 📖 Documentation

Install, Usage, Tutorials and Developer Guide is at https://docs.prowler.com/

# 📃 License

Prowler is licensed as Apache License 2.0 as specified in each file. You may obtain a copy of the License at
<http://www.apache.org/licenses/LICENSE-2.0>

# Usage Commands

usage: prowler [-h] [--version] {aws,azure,gcp,kubernetes,dashboard} ... aws [-h] [--status {PASS,FAIL,MANUAL} [{PASS,FAIL,MANUAL} ...]]
                                                                             [--output-formats {csv,json-asff,json-ocsf,html} [{csv,json-asff,json-ocsf,html} ...]]
                                                                             [--output-filename [OUTPUT_FILENAME]] [--output-directory [OUTPUT_DIRECTORY]] [--verbose]
                                                                             [--ignore-exit-code-3] [--no-banner] [--unix-timestamp] [--log-level {DEBUG,INFO,WARNING,ERROR,CRITICAL}]
                                                                             [--log-file [LOG_FILE]] [--only-logs] [--check CHECK [CHECK ...]] [--checks-file [CHECKS_FILE]]
                                                                             [--service SERVICE [SERVICE ...]]
                                                                             [--severity {critical,high,medium,low,informational} [{critical,high,medium,low,informational} ...]]
                                                                             [--compliance {cisa_aws,soc2_aws,cis_1.4_aws,cis_1.5_aws,mitre_attack_aws,gdpr_aws,aws_foundational_security_best_practices_aws,iso27001_2013_aws,hipaa_aws,cis_2.0_aws,gxp_21_cfr_part_11_aws,aws_well_architected_framework_security_pillar_aws,gxp_eu_annex_11_aws,nist_800_171_revision_2_aws,nist_800_53_revision_4_aws,nist_800_53_revision_5_aws,aws_account_security_onboarding_aws,cis_3.0_aws,ens_rd2022_aws,aws_foundational_technical_review_aws,nist_csf_1.1_aws,aws_well_architected_framework_reliability_pillar_aws,aws_audit_manager_control_tower_guardrails_aws,rbi_cyber_security_framework_aws,ffiec_aws,pci_3.2.1_aws,fedramp_moderate_revision_4_aws,fedramp_low_revision_4_aws,mitre_attack_gcp,cis_2.0_gcp,cis_2.1_azure,mitre_attack_azure,cis_2.0_azure,cis_1.8_kubernetes} [{cisa_aws,soc2_aws,cis_1.4_aws,cis_1.5_aws,mitre_attack_aws,gdpr_aws,aws_foundational_security_best_practices_aws,iso27001_2013_aws,hipaa_aws,cis_2.0_aws,gxp_21_cfr_part_11_aws,aws_well_architected_framework_security_pillar_aws,gxp_eu_annex_11_aws,nist_800_171_revision_2_aws,nist_800_53_revision_4_aws,nist_800_53_revision_5_aws,aws_account_security_onboarding_aws,cis_3.0_aws,ens_rd2022_aws,aws_foundational_technical_review_aws,nist_csf_1.1_aws,aws_well_architected_framework_reliability_pillar_aws,aws_audit_manager_control_tower_guardrails_aws,rbi_cyber_security_framework_aws,ffiec_aws,pci_3.2.1_aws,fedramp_moderate_revision_4_aws,fedramp_low_revision_4_aws,mitre_attack_gcp,cis_2.0_gcp,cis_2.1_azure,mitre_attack_azure,cis_2.0_azure,cis_1.8_kubernetes} ...]]
                                                                             [--category CATEGORY [CATEGORY ...]] [--checks-folder [CHECKS_FOLDER]]
                                                                             [--excluded-check EXCLUDED_CHECK [EXCLUDED_CHECK ...]]
                                                                             [--excluded-service EXCLUDED_SERVICE [EXCLUDED_SERVICE ...]]
                                                                             [--list-checks | --list-checks-json | --list-services | --list-compliance | --list-compliance-requirements {cisa_aws,soc2_aws,cis_1.4_aws,cis_1.5_aws,mitre_attack_aws,gdpr_aws,aws_foundational_security_best_practices_aws,iso27001_2013_aws,hipaa_aws,cis_2.0_aws,gxp_21_cfr_part_11_aws,aws_well_architected_framework_security_pillar_aws,gxp_eu_annex_11_aws,nist_800_171_revision_2_aws,nist_800_53_revision_4_aws,nist_800_53_revision_5_aws,aws_account_security_onboarding_aws,cis_3.0_aws,ens_rd2022_aws,aws_foundational_technical_review_aws,nist_csf_1.1_aws,aws_well_architected_framework_reliability_pillar_aws,aws_audit_manager_control_tower_guardrails_aws,rbi_cyber_security_framework_aws,ffiec_aws,pci_3.2.1_aws,fedramp_moderate_revision_4_aws,fedramp_low_revision_4_aws,mitre_attack_gcp,cis_2.0_gcp,cis_2.1_azure,mitre_attack_azure,cis_2.0_azure,cis_1.8_kubernetes} [{cisa_aws,soc2_aws,cis_1.4_aws,cis_1.5_aws,mitre_attack_aws,gdpr_aws,aws_foundational_security_best_practices_aws,iso27001_2013_aws,hipaa_aws,cis_2.0_aws,gxp_21_cfr_part_11_aws,aws_well_architected_framework_security_pillar_aws,gxp_eu_annex_11_aws,nist_800_171_revision_2_aws,nist_800_53_revision_4_aws,nist_800_53_revision_5_aws,aws_account_security_onboarding_aws,cis_3.0_aws,ens_rd2022_aws,aws_foundational_technical_review_aws,nist_csf_1.1_aws,aws_well_architected_framework_reliability_pillar_aws,aws_audit_manager_control_tower_guardrails_aws,rbi_cyber_security_framework_aws,ffiec_aws,pci_3.2.1_aws,fedramp_moderate_revision_4_aws,fedramp_low_revision_4_aws,mitre_attack_gcp,cis_2.0_gcp,cis_2.1_azure,mitre_attack_azure,cis_2.0_azure,cis_1.8_kubernetes} ...]
                                                                             | --list-categories | --list-fixer] [--mutelist-file [MUTELIST_FILE]] [--config-file [CONFIG_FILE]]
                                                                             [--fixer-config [FIXER_CONFIG]] [--custom-checks-metadata-file [CUSTOM_CHECKS_METADATA_FILE]]
                                                                             [--shodan [SHODAN_API_KEY]] [--slack] [--profile [PROFILE]] [--role [ROLE]]
                                                                             [--role-session-name [ROLE_SESSION_NAME]] [--mfa] [--session-duration [SESSION_DURATION]]
                                                                             [--external-id [EXTERNAL_ID]]
                                                                             [--region {eu-south-2,af-south-1,ca-central-1,us-west-2,us-east-2,cn-northwest-1,sa-east-1,ap-east-1,us-east-1,ap-northeast-2,me-south-1,cn-north-1,ap-southeast-3,eu-central-1,ap-southeast-4,me-central-1,ap-south-1,ap-northeast-1,eu-central-2,ap-southeast-2,eu-west-2,eu-west-1,us-gov-east-1,ap-southeast-1,ap-northeast-3,us-west-1,eu-north-1,il-central-1,ca-west-1,us-gov-west-1,eu-south-1,ap-south-2,eu-west-3} [{eu-south-2,af-south-1,ca-central-1,us-west-2,us-east-2,cn-northwest-1,sa-east-1,ap-east-1,us-east-1,ap-northeast-2,me-south-1,cn-north-1,ap-southeast-3,eu-central-1,ap-southeast-4,me-central-1,ap-south-1,ap-northeast-1,eu-central-2,ap-southeast-2,eu-west-2,eu-west-1,us-gov-east-1,ap-southeast-1,ap-northeast-3,us-west-1,eu-north-1,il-central-1,ca-west-1,us-gov-west-1,eu-south-1,ap-south-2,eu-west-3} ...]]
                                                                             [--organizations-role [ORGANIZATIONS_ROLE]] [--security-hub] [--skip-sh-update] [--send-sh-only-fails]
                                                                             [--quick-inventory] [--output-bucket [OUTPUT_BUCKET] | --output-bucket-no-assume [OUTPUT_BUCKET_NO_ASSUME]]
                                                                             [--resource-tag RESOURCE_TAG [RESOURCE_TAG ...] | --resource-arn RESOURCE_ARN [RESOURCE_ARN ...]]
                                                                             [--aws-retries-max-attempts [AWS_RETRIES_MAX_ATTEMPTS]] [--scan-unused-services] [--fixer]

options:
  -h, --help            show this help message and exit
  --check CHECK [CHECK ...], --checks CHECK [CHECK ...], -c CHECK [CHECK ...]
                        List of checks to be executed.
  --checks-file [CHECKS_FILE], -C [CHECKS_FILE]
                        JSON file containing the checks to be executed. See config/checklist_example.json
  --service SERVICE [SERVICE ...], --services SERVICE [SERVICE ...], -s SERVICE [SERVICE ...]
                        List of services to be executed.
  --compliance {cisa_aws,soc2_aws,cis_1.4_aws,cis_1.5_aws,mitre_attack_aws,gdpr_aws,aws_foundational_security_best_practices_aws,iso27001_2013_aws,hipaa_aws,cis_2.0_aws,gxp_21_cfr_part_11_aws,aws_well_architected_framework_security_pillar_aws,gxp_eu_annex_11_aws,nist_800_171_revision_2_aws,nist_800_53_revision_4_aws,nist_800_53_revision_5_aws,aws_account_security_onboarding_aws,cis_3.0_aws,ens_rd2022_aws,aws_foundational_technical_review_aws,nist_csf_1.1_aws,aws_well_architected_framework_reliability_pillar_aws,aws_audit_manager_control_tower_guardrails_aws,rbi_cyber_security_framework_aws,ffiec_aws,pci_3.2.1_aws,fedramp_moderate_revision_4_aws,fedramp_low_revision_4_aws,mitre_attack_gcp,cis_2.0_gcp,cis_2.1_azure,mitre_attack_azure,cis_2.0_azure,cis_1.8_kubernetes} [{cisa_aws,soc2_aws,cis_1.4_aws,cis_1.5_aws,mitre_attack_aws,gdpr_aws,aws_foundational_security_best_practices_aws,iso27001_2013_aws,hipaa_aws,cis_2.0_aws,gxp_21_cfr_part_11_aws,aws_well_architected_framework_security_pillar_aws,gxp_eu_annex_11_aws,nist_800_171_revision_2_aws,nist_800_53_revision_4_aws,nist_800_53_revision_5_aws,aws_account_security_onboarding_aws,cis_3.0_aws,ens_rd2022_aws,aws_foundational_technical_review_aws,nist_csf_1.1_aws,aws_well_architected_framework_reliability_pillar_aws,aws_audit_manager_control_tower_guardrails_aws,rbi_cyber_security_framework_aws,ffiec_aws,pci_3.2.1_aws,fedramp_moderate_revision_4_aws,fedramp_low_revision_4_aws,mitre_attack_gcp,cis_2.0_gcp,cis_2.1_azure,mitre_attack_azure,cis_2.0_azure,cis_1.8_kubernetes} ...]
                        Compliance Framework to check against for. The format should be the following: framework_version_provider (e.g.: cis_3.0_aws)
  --category CATEGORY [CATEGORY ...], --categories CATEGORY [CATEGORY ...]
                        List of categories to be executed.
  --list-checks, -l     List checks
  --list-checks-json    Output a list of checks in json format to use with --checks-file option
  --list-services       List covered services by given provider
  --list-compliance, --list-compliances
                        List all available compliance frameworks
  --list-compliance-requirements {cisa_aws,soc2_aws,cis_1.4_aws,cis_1.5_aws,mitre_attack_aws,gdpr_aws,aws_foundational_security_best_practices_aws,iso27001_2013_aws,hipaa_aws,cis_2.0_aws,gxp_21_cfr_part_11_aws,aws_well_architected_framework_security_pillar_aws,gxp_eu_annex_11_aws,nist_800_171_revision_2_aws,nist_800_53_revision_4_aws,nist_800_53_revision_5_aws,aws_account_security_onboarding_aws,cis_3.0_aws,ens_rd2022_aws,aws_foundational_technical_review_aws,nist_csf_1.1_aws,aws_well_architected_framework_reliability_pillar_aws,aws_audit_manager_control_tower_guardrails_aws,rbi_cyber_security_framework_aws,ffiec_aws,pci_3.2.1_aws,fedramp_moderate_revision_4_aws,fedramp_low_revision_4_aws,mitre_attack_gcp,cis_2.0_gcp,cis_2.1_azure,mitre_attack_azure,cis_2.0_azure,cis_1.8_kubernetes} [{cisa_aws,soc2_aws,cis_1.4_aws,cis_1.5_aws,mitre_attack_aws,gdpr_aws,aws_foundational_security_best_practices_aws,iso27001_2013_aws,hipaa_aws,cis_2.0_aws,gxp_21_cfr_part_11_aws,aws_well_architected_framework_security_pillar_aws,gxp_eu_annex_11_aws,nist_800_171_revision_2_aws,nist_800_53_revision_4_aws,nist_800_53_revision_5_aws,aws_account_security_onboarding_aws,cis_3.0_aws,ens_rd2022_aws,aws_foundational_technical_review_aws,nist_csf_1.1_aws,aws_well_architected_framework_reliability_pillar_aws,aws_audit_manager_control_tower_guardrails_aws,rbi_cyber_security_framework_aws,ffiec_aws,pci_3.2.1_aws,fedramp_moderate_revision_4_aws,fedramp_low_revision_4_aws,mitre_attack_gcp,cis_2.0_gcp,cis_2.1_azure,mitre_attack_azure,cis_2.0_azure,cis_1.8_kubernetes} ...]
                        List requirements and checks per compliance framework
  --list-categories     List the available check's categories
  --list-fixer, --list-fixers, --list-remediations
                        List fixers available for the provider

Outputs:
  --status {PASS,FAIL,MANUAL} [{PASS,FAIL,MANUAL} ...]
                        Filter by the status of the findings ['PASS', 'FAIL', 'MANUAL']
  --output-formats {csv,json-asff,json-ocsf,html} [{csv,json-asff,json-ocsf,html} ...], --output-modes {csv,json-asff,json-ocsf,html} [{csv,json-asff,json-ocsf,html} ...], -M {csv,json-asff,json-ocsf,html} [{csv,json-asff,json-ocsf,html} ...]
                        Output modes, by default csv and json-oscf are saved. When using AWS Security Hub integration, json-asff output is also saved.
  --output-filename [OUTPUT_FILENAME], -F [OUTPUT_FILENAME]
                        Custom output report name without the file extension, if not specified will use default output/prowler-output-ACCOUNT_NUM-OUTPUT_DATE.format
  --output-directory [OUTPUT_DIRECTORY], -o [OUTPUT_DIRECTORY]
                        Custom output directory, by default the folder where Prowler is stored
  --verbose             Runs showing all checks executed and results
  --ignore-exit-code-3, -z
                        Failed checks do not trigger exit code 3
  --no-banner, -b       Hide Prowler banner
  --unix-timestamp      Set the output timestamp format as unix timestamps instead of iso format timestamps (default mode).

Logging:
  --log-level {DEBUG,INFO,WARNING,ERROR,CRITICAL}
                        Select Log Level
  --log-file [LOG_FILE]
                        Set log file name
  --only-logs           Print only Prowler logs by the stdout. This option sets --no-banner.

Specify checks/services to run:
  --severity {critical,high,medium,low,informational} [{critical,high,medium,low,informational} ...], --severities {critical,high,medium,low,informational} [{critical,high,medium,low,informational} ...]
                        Severities to be executed ['critical', 'high', 'medium', 'low', 'informational']
  --checks-folder [CHECKS_FOLDER], -x [CHECKS_FOLDER]
                        Specify external directory with custom checks (each check must have a folder with the required files, see more in
                        https://docs.prowler.cloud/en/latest/tutorials/misc/#custom-checks).

Exclude checks/services to run:
  --excluded-check EXCLUDED_CHECK [EXCLUDED_CHECK ...], --excluded-checks EXCLUDED_CHECK [EXCLUDED_CHECK ...], -e EXCLUDED_CHECK [EXCLUDED_CHECK ...]
                        Checks to exclude
  --excluded-service EXCLUDED_SERVICE [EXCLUDED_SERVICE ...], --excluded-services EXCLUDED_SERVICE [EXCLUDED_SERVICE ...]
                        Services to exclude

Mutelist:
  --mutelist-file [MUTELIST_FILE], -w [MUTELIST_FILE]
                        Path for mutelist YAML file. See example prowler/config/<provider>_mutelist.yaml for reference and format. For AWS provider, it also accepts AWS DynamoDB Table,
                        Lambda ARNs or S3 URIs, see more in https://docs.prowler.cloud/en/latest/tutorials/mutelist/

Configuration:
  --config-file [CONFIG_FILE]
                        Set configuration file path
  --fixer-config [FIXER_CONFIG]
                        Set configuration fixer file path

Custom Checks Metadata:
  --custom-checks-metadata-file [CUSTOM_CHECKS_METADATA_FILE]
                        Path for the custom checks metadata YAML file. See example prowler/config/custom_checks_metadata_example.yaml for reference and format. See more in
                        https://docs.prowler.cloud/en/latest/tutorials/custom-checks-metadata/

3rd Party Integrations:
  --shodan [SHODAN_API_KEY], -N [SHODAN_API_KEY]
                        Check if any public IPs in your Cloud environments are exposed in Shodan.
  --slack               Send a summary of the execution with a Slack APP in your channel. Environment variables SLACK_API_TOKEN and SLACK_CHANNEL_NAME are required (see more in
                        https://docs.prowler.cloud/en/latest/tutorials/integrations/#slack).

Authentication Modes:
  --profile [PROFILE], -p [PROFILE]
                        AWS profile to launch prowler with
  --role [ROLE], -R [ROLE]
                        ARN of the role to be assumed
  --role-session-name [ROLE_SESSION_NAME]
                        An identifier for the assumed role session. Defaults to ProwlerAssessmentSession
  --mfa                 IAM entity enforces MFA so you need to input the MFA ARN and the TOTP
  --session-duration [SESSION_DURATION], -T [SESSION_DURATION]
                        Assumed role session duration in seconds, must be between 900 and 43200. Default: 3600
  --external-id [EXTERNAL_ID], -I [EXTERNAL_ID]
                        External ID to be passed when assuming role

AWS Regions:
  --region {eu-south-2,af-south-1,ca-central-1,us-west-2,us-east-2,cn-northwest-1,sa-east-1,ap-east-1,us-east-1,ap-northeast-2,me-south-1,cn-north-1,ap-southeast-3,eu-central-1,ap-southeast-4,me-central-1,ap-south-1,ap-northeast-1,eu-central-2,ap-southeast-2,eu-west-2,eu-west-1,us-gov-east-1,ap-southeast-1,ap-northeast-3,us-west-1,eu-north-1,il-central-1,ca-west-1,us-gov-west-1,eu-south-1,ap-south-2,eu-west-3} [{eu-south-2,af-south-1,ca-central-1,us-west-2,us-east-2,cn-northwest-1,sa-east-1,ap-east-1,us-east-1,ap-northeast-2,me-south-1,cn-north-1,ap-southeast-3,eu-central-1,ap-southeast-4,me-central-1,ap-south-1,ap-northeast-1,eu-central-2,ap-southeast-2,eu-west-2,eu-west-1,us-gov-east-1,ap-southeast-1,ap-northeast-3,us-west-1,eu-north-1,il-central-1,ca-west-1,us-gov-west-1,eu-south-1,ap-south-2,eu-west-3} ...], --filter-region {eu-south-2,af-south-1,ca-central-1,us-west-2,us-east-2,cn-northwest-1,sa-east-1,ap-east-1,us-east-1,ap-northeast-2,me-south-1,cn-north-1,ap-southeast-3,eu-central-1,ap-southeast-4,me-central-1,ap-south-1,ap-northeast-1,eu-central-2,ap-southeast-2,eu-west-2,eu-west-1,us-gov-east-1,ap-southeast-1,ap-northeast-3,us-west-1,eu-north-1,il-central-1,ca-west-1,us-gov-west-1,eu-south-1,ap-south-2,eu-west-3} [{eu-south-2,af-south-1,ca-central-1,us-west-2,us-east-2,cn-northwest-1,sa-east-1,ap-east-1,us-east-1,ap-northeast-2,me-south-1,cn-north-1,ap-southeast-3,eu-central-1,ap-southeast-4,me-central-1,ap-south-1,ap-northeast-1,eu-central-2,ap-southeast-2,eu-west-2,eu-west-1,us-gov-east-1,ap-southeast-1,ap-northeast-3,us-west-1,eu-north-1,il-central-1,ca-west-1,us-gov-west-1,eu-south-1,ap-south-2,eu-west-3} ...], -f {eu-south-2,af-south-1,ca-central-1,us-west-2,us-east-2,cn-northwest-1,sa-east-1,ap-east-1,us-east-1,ap-northeast-2,me-south-1,cn-north-1,ap-southeast-3,eu-central-1,ap-southeast-4,me-central-1,ap-south-1,ap-northeast-1,eu-central-2,ap-southeast-2,eu-west-2,eu-west-1,us-gov-east-1,ap-southeast-1,ap-northeast-3,us-west-1,eu-north-1,il-central-1,ca-west-1,us-gov-west-1,eu-south-1,ap-south-2,eu-west-3} [{eu-south-2,af-south-1,ca-central-1,us-west-2,us-east-2,cn-northwest-1,sa-east-1,ap-east-1,us-east-1,ap-northeast-2,me-south-1,cn-north-1,ap-southeast-3,eu-central-1,ap-southeast-4,me-central-1,ap-south-1,ap-northeast-1,eu-central-2,ap-southeast-2,eu-west-2,eu-west-1,us-gov-east-1,ap-southeast-1,ap-northeast-3,us-west-1,eu-north-1,il-central-1,ca-west-1,us-gov-west-1,eu-south-1,ap-south-2,eu-west-3} ...]
                        AWS region names to run Prowler against

AWS Organizations:
  --organizations-role [ORGANIZATIONS_ROLE], -O [ORGANIZATIONS_ROLE]
                        Specify AWS Organizations management role ARN to be assumed, to get Organization metadata

AWS Security Hub:
  --security-hub, -S    Send check output to AWS Security Hub and save json-asff outuput.
  --skip-sh-update      Skip updating previous findings of Prowler in Security Hub
  --send-sh-only-fails  Send only Prowler failed findings to SecurityHub

Quick Inventory:
  --quick-inventory, -i
                        Run Prowler Quick Inventory. The inventory will be stored in an output csv by default

AWS Outputs to S3:
  --output-bucket [OUTPUT_BUCKET], -B [OUTPUT_BUCKET]
                        Custom output bucket, requires -M <mode> and it can work also with -o flag.
  --output-bucket-no-assume [OUTPUT_BUCKET_NO_ASSUME], -D [OUTPUT_BUCKET_NO_ASSUME]
                        Same as -B but do not use the assumed role credentials to put objects to the bucket, instead uses the initial credentials.

AWS Based Scans:
  --resource-tag RESOURCE_TAG [RESOURCE_TAG ...], --resource-tags RESOURCE_TAG [RESOURCE_TAG ...]
                        Scan only resources with specific AWS Tags (Key=Value), e.g., Environment=dev Project=prowler
  --resource-arn RESOURCE_ARN [RESOURCE_ARN ...], --resource-arns RESOURCE_ARN [RESOURCE_ARN ...]
                        Scan only resources with specific AWS Resource ARNs, e.g., arn:aws:iam::012345678910:user/test arn:aws:ec2:us-east-1:123456789012:vpc/vpc-12345678

Boto3 Config:
  --aws-retries-max-attempts [AWS_RETRIES_MAX_ATTEMPTS]
                        Set the maximum attemps for the Boto3 standard retrier config (Default: 3)

Scan Unused Services:
  --scan-unused-services
                        Scan unused services

Prowler Fixer:
  --fixer               Fix the failed findings that can be fixed by Prowler

