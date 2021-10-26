# Spring Boot on Kubernetes

The purpose of this demo is to demonstrate the following:

- How you can use the `Dekorate` kubernetes-spring-stater.
- How `Dekorate` detects that this is a `Spring Boot` web app and automatically configures a service binded to the http port 8080.
- How you can trigger an image build and push after the compilation using JIB and the hook provided by `Dekorate`.
- How you can apply the generated manifests to a target cluster by adding the `dekorate.deploy=true` flag to the compilation command.

This example has been used in Codemotion Spanish edition 2021 and is based on the [Dekorate Spring Boot example](https://github.com/dekorateio/dekorate/blob/cb7e0c2e052a15a4e8909df5f5e615da98d8e1f7/examples/spring-boot-on-kubernetes-example/readme.md#L1-L59)
The slides are available [here](https://github.com/aureamunoz/dekorate-demo-for-codemotion-2021/blob/main/Dekorate%20for%20Codemotion%202021.pdf)