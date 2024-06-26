
<h1 align="center">GitHub Advanced Security Bootcamp</h1>


> This bootcamp is designed to help familiarize you with GitHub Advanced Security (GHAS) so that you can better understand how to use it in your own repositories.

## Prerequisites

- You must have a GitHub account. If you don't have, see "[Creating an account on GitHub.](https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github)"

- Import the follwoing repo to your personal github account, choose **Public** visibility for this labs purpose. Or Fork the repository
https://github.com/CanarysPlayground/ghcap-github-ghas.git

## 🏫 Agenda

We will go over the following topics:


##### Exercise 1: Dependabot: [link](exercises/lab%201%20-%20dependabot.md)
- [x] Enabling Dependabot alerts
- [x] Reviewing the dependency graph
- [x] Viewing and managing results
- [x] Enabling Dependabot security updates
- [x] Configuring Dependabot security updates
- [x] Working with Dependency Review

##### Exercise 2: Secret scanning: [link](exercises/lab%202%20-%20secret-scanning.md)
- [x] Enabling secret scanning
- [x] Viewing and managing results
- [x] Excluding files from secret scanning
- [x] Custom patterns for secret scanning
- [x] Managing access to alerts

##### Exercise 3: Code scanning: [link](exercises/lab%203%20-%20code-scanning.md)

- [x] Enabling code scanning
- [x] Reviewing any failed analysis jobs
- [x] Using context and expressions to modify build
- [x] Reviewing and managing results
- [x] Triaging a result in a PR

</details>

## :books: Resources
- [About code scanning](https://docs.github.com/en/github/finding-security-vulnerabilities-and-errors-in-your-code/about-code-scanning)
- [About Dependabot Alerts](https://docs.github.com/en/free-pro-team@latest/github/managing-security-vulnerabilities/about-alerts-for-vulnerable-dependencies)
- [About secret scanning](https://docs.github.com/en/github/administering-a-repository/about-secret-scanning)
- [Events that trigger workflows](https://docs.github.com/en/free-pro-team@latest/actions/reference/events-that-trigger-workflows)
- [Configuring the CodeQL workflow for compiled languages](
https://docs.github.com/en/free-pro-team@latest/github/finding-security-vulnerabilities-and-errors-in-your-code/configuring-the-codeql-workflow-for-compiled-languages)
- [Configuring code scanning](https://docs.github.com/en/free-pro-team@latest/github/finding-security-vulnerabilities-and-errors-in-your-code/configuring-code-scanning)
- [Configuring notifications for Dependabot alerts](https://docs.github.com/en/free-pro-team@latest/github/managing-security-vulnerabilities/configuring-notifications-for-vulnerable-dependencies#configuring-notifications-for-dependabot-alerts)
- [Customizing dependency updates](https://docs.github.com/en/free-pro-team@latest/github/administering-a-repository/customizing-dependency-updates)
- [Configuration options for the dependabot.yml file](https://docs.github.com/en/free-pro-team@latest/github/administering-a-repository/configuration-options-for-dependency-updates)
- [Filter pattern cheat sheet](https://docs.github.com/en/free-pro-team@latest/actions/reference/workflow-syntax-for-github-actions#filter-pattern-cheat-sheet)
- [Running additional queries](
https://docs.github.com/en/free-pro-team@latest/github/finding-security-vulnerabilities-and-errors-in-your-code/configuring-code-scanning#running-additional-queries)
- [Troubleshooting the CodeQL workflow](https://docs.github.com/en/free-pro-team@latest/github/finding-security-vulnerabilities-and-errors-in-your-code/troubleshooting-the-codeql-workflow)
- [Code scanning API](https://docs.github.com/en/free-pro-team@latest/rest/reference/code-scanning)
- [Secret scanning API](https://docs.github.com/en/rest/reference/secret-scanning)
- [GraphQL API](https://docs.github.com/en/free-pro-team@latest/graphql)
  - [RepositoryVulnerabilityAlert](https://docs.github.com/en/free-pro-team@latest/graphql/reference/objects#repositoryvulnerabilityalert)
- [REST API](https://docs.github.com/en/free-pro-team@latest/rest)
