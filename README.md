# lambda-helloworld-nodejs

A Nodejs version of helloworld for AWS Lambda with some cool GitHub Actions.

## Actions

* [deploy-develop.yml](.github/actions/deploy-develop.yml): Builds and deploys the latest version when code is pushed to the develop branch either on direct commit or a pull request.
* build-package.yml: Builds from the master branch and stores the deployable package as a local GitHub artifact package.
* deploy-package.yml: Deploys the latest created package in the local GitHub artifact package repository.
