
# Azure Pipelines: Automate the creation of Team Projects Securely by adding a default branch policy and approvers during creation.

This repository contains sample project  demonstrating how to implement automated creation of a Team Project in an existing Azure DevOps Organization.  Additionally the project will initiallize a default repo, apply a branch policy on the master branch, add the project admininstrators as the auto populated approvers on a pull request.  Finally we add a group rule on the organization to map an AAD group to the project and role.
## Available samples

The following sample projects specify the main technologies used. A team that uses comparable tools and frameworks should be able to refer to the sample and update their existing tests to incorporate automated accessibility checks.

* **[Sample 1: typescript-selenium-webdriver-sample](./typescript-selenium-webdriver-sample)**: 
  * Useful for teams using Selenium and TypeScript/JavaScript. 
  
* **[Sample 2: CSharpSeleniumWebdriverSample](./csharp-selenium-webdriver-sample)**: 
  * Useful for teams using Selenium and C#. 

*Are we missing a sample you'd like to see? [File a sample request](https://github.com/microsoft/axe-pipelines-samples/issues/new?assignees=&labels=sample_request&template=feature_request.md&title=Sample+Request%3A+%3Csample+name+here%3E) or [submit a pull request](./CONTRIBUTING.md)!*

## Disclaimer

Automated accessibility tests can detect some common accessibility problems such as missing or invalid properties. But most accessibility problems can only be discovered through manual testing. We recommend [Accessibility Insights](https://accessibilityinsights.io/docs/en/web/overview), a free and open source dev tool that walks you though assessing a website for 100% [WCAG 2.0 AA](https://www.w3.org/WAI/WCAG21/quickref/?currentsidebar=%23col_overview&versions=2.0&levels=aaa) coverage.

## Contributing

This project welcomes contributions and suggestions. Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
