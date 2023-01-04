Build & Test GraphQL-JS on Harness CI
=======================================
This is a fork of GraphQL JS project. This project is used for testing Harness CI's capabilities by the CME team at Harness. Please follow [these instructions](https://github.com/harness-community/graphql-js/blob/trunk/.harness/README.md) on how to clone this repo and see the results yourself.


- [Harness Fast CI Blog Announcement](https://harness.io/blog/announcing-speed-enhancements-and-hosted-builds-for-harness-ci)
- [Get Started with Harness CI](https://harness.io/products/continuous-integration)

## Setting up this pipeline on Harness CI Hosted Builds

1. Create a [GitHub Account](https://github.com) or use an existing one

2. Fork [this repository](https://github.com/harness-community/kafka/fork) into your GitHub account. 

3. If you are new to Harness CI, signup for [Harness CI](https://app.harness.io/auth/#/signup)
  * Select the `Continuous Integration` module and choose the `Starter pipeline` wizard to create your first pipeline using the forked repo from #2.
  * Go to the newly created pipeline and hit the `Triggers`tab. If everything went well, you should see two triggers auto-created. A `Pull Request`trigger and a `Push`trigger. For this exercise, we only need `Pull Request`trigger to be enabled. So, please disable or delete the `Push`trigger.

4. If you are an existing Harness CI user, create a new pipeline to use the cloud option for infrastructure and setup the PR trigger.

