# AWS CLI (aws-cli)
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
