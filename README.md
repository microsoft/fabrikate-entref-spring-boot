# fabrikate-entref-spring-boot
A [Fabrikate](https://github.com/Microsoft/fabrikate) definition for [Project Jackson](https://github.com/Microsoft/entref-spring-boot)

If you're unfamiliar with how to set up your high level definition, read instructions [here](https://github.com/Microsoft/fabrikate#getting-started).

As an example for Project Jackson, you may set up your HLD repo like below:
```
name: sample-app
subcomponents:
  - name: "cloud-native"
    source: "https://github.com/timfpark/fabrikate-cloud-native"
    method: "git"
  - name: "project-jackson"
    source: "https://github.com/microsoft/fabrikate-entref-spring-boot"
    method: "git"
```

This `sample-app` includes this fabrikate definition for `entrf-spring-boot` and `cloud-native`, which are some of the stacks needed to run Project Jackson. 

# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
