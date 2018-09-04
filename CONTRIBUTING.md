Contributing to ECS-Terraform
=======================

The easiest ways to contribute to `ECS-Terraform` are:


  * Creating a new [issue].
  * Forking the repository, make your contribution and submit a pull request.
    See [Git Flow](#git-flow) for further information.

[issue]: https://github.com/utkarsh-devops/ECS-Terraform/issues/new

Git Flow
--------
We chose to use the [Git flow branching model][flow] for `ECS-Terraform`, so you are
kindly required to follow the same model when you make your contributions. This
basically means that:

  * If you are fixing a bug, you can create a *hotfix* branch from the affected
  release (preferably, the latest one) and send a pull request from that branch.
  * If you are creating a new feature, please checkout the `develop` branch and
  send a pull request from there.
  * I won't consider pull request coming from the `master` branch and if I do, I
    won't be quick.

[flow]: http://nvie.com/posts/a-successful-git-branching-model/

Coding Conventions and Style
----------------------------
Terraform's guide for syntax and general best practices are used. Check https://www.terraform.io/docs/enterprise/guides/recommended-practices/index.html for more info.


