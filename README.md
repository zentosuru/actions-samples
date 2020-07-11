# actions-samples

A collection of GitHub Actions samples and tips


![](assets/logo.png)



| Sample | Description | status |
| ---- | ---- | ---- |
| [Go project release workflow](.github/workflows/go-release.yml) |  Simple Go lang project release workflow sample where [actions/create-release](https://github.com/actions/create-release) and [ actions/upload-release-asset](https://github.com/actions/upload-release-asset) are used | [![Go Release Project](https://github.com/yokawasa/actions-samples/workflows/Go%20Release%20Project/badge.svg)](https://github.com/yokawasa/actions-samples/actions?query=workflow%3A%22Go+release+project%22) |
| [Matrix build pattern](.github/workflows/matrix.yml) | Matrix builds using [jobs.<job_id>.strategy.matrix](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions#jobsjob_idstrategymatrix) workflow syntax  | [![Matrix Build Pattern](https://github.com/yokawasa/actions-samples/workflows/Matrix%20Build%20Pattern/badge.svg)](https://github.com/yokawasa/actions-samples/actions?query=workflow%3A%22Matrix+build+pattern%22)|
| [Installer with multiple platforms](.github/workflows/installer.yml) | Sample of installing httping using installer on multiple platforms. For suppored platforms, please see [Supported runners and hardware resources](https://docs.github.com/en/actions/reference/virtual-environments-for-github-hosted-runners#supported-runners-and-hardware-resources) | [![Installer with multiple platforms](https://github.com/yokawasa/actions-samples/workflows/Installer%20with%20multiple%20platforms/badge.svg)](https://github.com/yokawasa/actions-samples/actions?query=workflow%3A%22Installer+with+multiple+platforms%22) |
| [Run on containers](.github/workflows/run-on-containers.yml) | Running on containers using [jobs.<job_id>.container](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions#jobsjob_idcontainer) and [jobs.<job_id>.steps.uses](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions#jobsjob_idstepsuses) workflow syntaxes | [![Run on ontainers](https://github.com/yokawasa/actions-samples/workflows/Run%20on%20ontainers/badge.svg)](https://github.com/yokawasa/actions-samples/actions?query=workflow%3A%22Run+on+ontainers%22)|
| [Service containers](.github/workflows/service-containers.yml) | [Service containers](https://docs.github.com/en/actions/configuring-and-managing-workflows/about-service-containers) sample worlflow where you run a db client script that requires access to a Postgres database using [PostgreSQL service containers](https://docs.github.com/en/actions/configuring-and-managing-workflows/creating-postgresql-service-containers) | [![Postgres Service Containers](https://github.com/yokawasa/actions-samples/workflows/Postgres%20Service%20Containers/badge.svg)](https://github.com/yokawasa/actions-samples/actions?query=workflow%3A%22Postgres+Service+Containers%22) |
