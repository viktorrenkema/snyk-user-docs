# Introducing Snyk

## What is Snyk?

Snyk is a platform allowing you to scan, prioritize, and fix security vulnerabilities in your code, open source dependencies, container images, and Infrastructure as Code (IaC) configurations.

## Snyk’s developer-first approach

Developers now assemble applications with a combination of proprietary and open-source code, run that code in containers, and then deploy with infrastructure as code configurations with technologies like Kubernetes and Terraform.

A good security process secures each of these components where they are built and maintained. Snyk integrates into DevOps processes to work with developers using the methods each prefers, while following and supporting industry best practices. Snyk integrates directly into your IDEs, workflows, and automation pipelines to add security expertise to your toolkit.

<figure><img src="../.gitbook/assets/image (457).png" alt="Developer Security Platform"><figcaption><p>Developer Security Platform: Products and Developer experience</p></figcaption></figure>

## Use Snyk in your workflow

* **Secure your code**: use [Snyk Open Source](../scan-application-code/snyk-open-source/) to fix vulnerabilities in your open source dependencies and [Snyk Code](../scan-application-code/snyk-code/) to fix vulnerabilities in your source code.
* **Secure your containers**: use [Snyk Container](../scan-containers/) to fix vulnerabilities in container images and Kubernetes applications.
* **Secure your deployment**: and [Snyk Infrastructure as Code (IaC)](../scan-cloud-configurations/snyk-infrastructure-as-code/) to fix misconfigurations in Terraform, CloudFormation, Kubernetes, and Azure templates. Use [Integrated IaC with cloud context](../scan-cloud-configurations/integrated-iac-with-cloud-context/) to fix misconfigurations in Amazon Web Services accounts, Microsoft Azure subscriptions, and Google Cloud projects.

## Choose how to run Snyk

You can run Snyk in the following ways:

* [**Web**](getting-started-with-the-snyk-web-ui.md): the Snyk Web UI ([app.snyk.io](https://app.snyk.io)) provides a browser-based experience, along with functions such as configuration settings, filtering and fixing discovered issues, and reports.
* [**CLI**](../snyk-cli/): the Snyk Command Line Interface enables you to run vulnerability scans on your local machine and integrate Snyk into your pipeline.
* [**IDEs**](../integrations/ide-tools/): the Snyk IDE integrations enable you to embed Snyk in your development environment.
* [**API**](../snyk-api-info/): the Snyk API enables you to integrate with Snyk programmatically, tuning Snyk’s security automation to your specific workflows.

This video shows using the CLI to scan for vulnerabilities.

{% embed url="https://thoughtindustries-1.wistia.com/medias/b8vrvtmnbu" %}
Running Snyk from the command line.
{% endembed %}

## How can Snyk work in my environment?

Snyk tech stacks supported depend on the Snyk product you use:

* **Snyk Open Source**: see [Open Source - Supported languages and package managers](../scan-application-code/snyk-open-source/snyk-open-source-supported-languages-and-package-managers/).
* **Snyk Code**: see [Snyk Code - Supported languages and frameworks](../scan-application-code/snyk-code/snyk-code-language-and-framework-support.md)
* **Snyk Container**: see [Supported operating system distributions](../scan-containers/how-snyk-container-works/supported-operating-system-distributions.md)
* **Snyk Infrastructure as Code**: see [Supported IaC and cloud providers](../scan-cloud-configurations/supported-iac-and-cloud-providers.md)
* **Integrated IaC with cloud context:** see [Supported IaC and cloud providers](../scan-cloud-configurations/supported-iac-and-cloud-providers.md)

## What can Snyk integrate with?

Snyk integrations for your software development process allow you to integrate Snyk into your development and security processes, including source control, CI/CD, and many others.

See [Snyk integrations](../integrations/) and [Snyk for IDEs](../integrations/ide-tools/) for details.

## **What does Snyk cost?**

Snyk has several pricing plans available, from free to Enterprise. See [Snyk Pricing Plans](../more-info/plans.md).

## What happens to my data?

See [How Snyk handles your data](../more-info/how-snyk-handles-your-data.md) for details of Snyk data handling.
