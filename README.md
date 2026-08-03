# AWS CLI (aws-cli)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The AWS Command Line Interface (AWS CLI) is a unified tool to manage AWS services from the command line. With just one tool to download and configure, you can control multiple AWS services and automate them through scripts. AWS CLI v2 supports all AWS services with auto-completion, AWS SSO, and improved performance. It is open-source, available on Linux, macOS, and Windows, and is the official CLI for Amazon Web Services.

**URL:** [https://aws.amazon.com/cli/](https://aws.amazon.com/cli/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, CLI, Cloud Computing, Command Line Interface, DevOps, Open Source

## Timestamps

- **Created:** 2026-03-25
- **Modified:** 2026-04-19

## APIs

### AWS CLI
The AWS CLI v2 is the official command-line interface for Amazon Web Services, providing unified access to all AWS services from the terminal with auto-completion, AWS SSO support, and improved performance over v1.

**Human URL:** [https://aws.amazon.com/cli/](https://aws.amazon.com/cli/)

#### Tags:

 - AWS, CLI, Command Line Interface, DevOps, Open Source

#### Properties

- [Documentation](https://docs.aws.amazon.com/cli/latest/userguide/)
- [GettingStarted](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
- [APIReference](https://docs.aws.amazon.com/cli/latest/reference/)
- [GitHubRepository](https://github.com/aws/aws-cli)

## Common Properties

- [Website](https://aws.amazon.com/cli/)
- [Documentation](https://docs.aws.amazon.com/cli/)
- [GettingStarted](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
- [GitHubRepository](https://github.com/aws/aws-cli)
- [GitHubOrganization](https://github.com/aws)
- [ReleaseNotes](https://github.com/aws/aws-cli/blob/v2/CHANGELOG.rst)
- [Support](https://github.com/aws/aws-cli/issues)
- [StackOverflow](https://stackoverflow.com/questions/tagged/awscli)

## Features

| Name | Description |
|------|-------------|
| Unified AWS Service Access | Control all AWS services from a single command-line tool with consistent syntax and output formatting. |
| Auto-Completion | Shell auto-completion for commands, subcommands, options, and resource names in bash, zsh, and fish. |
| AWS SSO Support | Native AWS IAM Identity Center (SSO) integration for credential management and multi-account access. |
| Output Formatting | Multiple output formats including JSON, YAML, text, and table, with JMESPath query filtering. |
| Credential Management | Supports named profiles, environment variables, instance metadata, and credential process plugins. |
| Wizard Commands | Interactive step-by-step wizards for complex workflows like IAM role creation and DynamoDB table setup. |
| Waiters | Built-in wait commands to poll until AWS resources reach desired states like running or available. |
| Pagination Control | Automatic pagination with configurable page size and support for --no-paginate and --page-size flags. |
| Streaming Output | Stream large binary outputs like EC2 console logs and Lambda function logs directly to stdout. |
| Plugin System | Extensible plugin architecture for adding custom commands and credential providers. |

## Use Cases

| Name | Description |
|------|-------------|
| Infrastructure Automation | Automate AWS infrastructure provisioning, configuration, and teardown in CI/CD pipelines and scripts. |
| Multi-Account Management | Manage multiple AWS accounts and regions using named profiles and AWS Organizations. |
| Resource Querying | Query and filter AWS resource inventories with JMESPath expressions and output formatting. |
| Batch Operations | Process multiple AWS resources in bulk using shell scripting loops and CLI output piping. |
| Developer Workflows | Speed up development workflows with quick access to S3, Lambda, DynamoDB, and other services. |

## Integrations

| Name | Description |
|------|-------------|
| AWS IAM Identity Center | Native SSO integration for credential vending and multi-account access management. |
| AWS CloudShell | Pre-installed in AWS CloudShell for browser-based CLI access without local installation. |
| AWS CodeBuild | Available in CodeBuild build environments for CI/CD pipeline automation. |
| GitHub Actions | Used in GitHub Actions workflows via the configure-aws-credentials action. |
| Homebrew | Installable via Homebrew on macOS for easy installation and updates. |
| Windows Package Manager | Available via winget for installation on Windows systems. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
