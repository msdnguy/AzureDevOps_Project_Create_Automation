
# Azure Pipelines: Automate the creation of Team Projects Securely by adding a default branch policy and approvers during creation.

This repository contains sample project  demonstrating how to implement automated creation of a Team Project in an existing Azure DevOps Organization.  Additionally the project will initiallize a default repo, apply a branch policy on the master branch, add the project admininstrators as the auto populated approvers on a pull request.  Finally we add a group rule on the organization to map an AAD group to the project and role.

We leverage the Azure DevOps REST APIs documented at https://docs.microsoft.com/en-us/rest/api/azure/devops/?view=azure-devops-rest-6.0

The powershell script leverages an OauthToken that must be created. Details on obtaining an Oauth token to use at https://docs.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/oauth

Details on using the token in a powershell script
https://powershell.org/2019/04/azure-devops-enable-allow-scripts-to-access-the-oauth-token-using-powershell/


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
