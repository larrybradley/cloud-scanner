# Cloud Scanner


**Note:** this is a fork of the [Microsoft Cloud Scanner](https://github.com/Microsoft/cloud-scanner), originally built by the Microsoft Commercial Software Engineering team.  This project was forked for demonstration purposes only; please contribute changes back to the original project.

## Developer Documentation
[Read the API docs](https://microsoft.github.io/cloud-scanner/)

## Introduction

Core library for Cloud Scanner project, which is a workflow for discovering and documenting cloud resources across multiple accounts or subscriptions with the intent to store, update tags, and/or perform other generic resource related operations.

Dependent upon adapter projects such as [cloud-scanner-azure](https://github.com/Microsoft/cloud-scanner-azure) and [cloud-scanner-generic](https://github.com/Microsoft/cloud-scanner-generic) for the registry of service providers.

For an example of usage within an Azure Functions environment, see [cloud-scanner-azure-functions-sample](https://github.com/Microsoft/cloud-scanner-azure-functions-sample).


## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.
