# actions-samples

A collection of GitHub Actions samples and tips


![](assets/logo.png)



| Sample | Description | status |
| ---- | ---- | ---- |
| [Environment variables](.github/workflows/env.yml) | Dump default [enviroment variables](https://docs.github.com/en/actions/configuring-and-managing-workflows/using-environment-variables) for each GitHub Actions in a workflow | [![Environment variables](https://github.com/yokawasa/actions-samples/workflows/Environment%20variables/badge.svg)](https://github.com/yokawasa/actions-samples/actions?query=workflow%3A%22Environment+variables%22) |
| [Contexts](.github/workflows/contexts.yml) | Dump [contexts](https://docs.github.com/en/actions/reference/context-and-expression-syntax-for-github-actions#contexts) for each GitHub Actions in a workflow | [![Environment variables](https://github.com/yokawasa/actions-samples/workflows/Contexts/badge.svg)](https://github.com/yokawasa/actions-samples/actions?query=workflow%3A%22Contexts%22) |
| [REST API with GITHUB_TOKEN](.github/workflows/github-token.yml) | Create issue on commit using REST API [authenticating with the GITHUB_TOKEN](https://docs.github.com/en/actions/configuring-and-managing-workflows/authenticating-with-the-github_token) | [![REST API with GITHUB_TOKEN](https://github.com/yokawasa/actions-samples/workflows/REST%20API%20with%20GITHUB_TOKEN/badge.svg)](https://github.com/yokawasa/actions-samples/actions?query=workflow%3A%22REST+API+with+GITHUB_TOKEN%22) |
| [Go project release](.github/workflows/go-release.yml) |  Simple Go lang project release workflow sample where [actions/create-release](https://github.com/actions/create-release) and [actions/upload-release-asset](https://github.com/actions/upload-release-asset) are used | [![Go Release Project](https://github.com/yokawasa/actions-samples/workflows/Go%20Release%20Project/badge.svg)](https://github.com/yokawasa/actions-samples/actions?query=workflow%3A%22Go+release+project%22) |
| [Matrix build](.github/workflows/matrix.yml) | Matrix builds using [jobs.<job_id>.strategy.matrix](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions#jobsjob_idstrategymatrix) workflow syntax  | [![Matrix Build Pattern](https://github.com/yokawasa/actions-samples/workflows/Matrix%20Build%20Pattern/badge.svg)](https://github.com/yokawasa/actions-samples/actions?query=workflow%3A%22Matrix+build+pattern%22)|
| [Sharing data between steps in a job](.github/workflows/share-data-steps.yml) | Sample of sharing data between steps in a job using files, [set-env](https://docs.github.com/en/actions/reference/workflow-commands-for-github-actions#setting-an-environment-variable), and [set-output](https://docs.github.com/en/actions/reference/workflow-commands-for-github-actions#setting-an-output-parameter) | [![Sharing data between steps](https://github.com/yokawasa/actions-samples/workflows/Sharing%20data%20between%20steps/badge.svg)](https://github.com/yokawasa/actions-samples/actions?query=workflow%3A%22Sharing+data+between+steps%22) |
| [Sharing data between jobs in a workflow](.github/workflows/share-data-jobs.yml) | Sample of sharing data between jobs in a workflow using [actions/upload-artifact](https://github.com/actions/upload-artifact) and [actions/download-artifact](https://github.com/actions/download-artifact) | [![Sharing data between jobs](https://github.com/yokawasa/actions-samples/workflows/Sharing%20data%20between%20jobs/badge.svg)](https://github.com/yokawasa/actions-samples/actions?query=workflow%3A%22Sharing+data+between+jobs%22) |
| [Installer with multiple platforms](.github/workflows/installer.yml) | Sample of installing httping using installer on multiple platforms. For suppored platforms, please see [Supported runners and hardware resources](https://docs.github.com/en/actions/reference/virtual-environments-for-github-hosted-runners#supported-runners-and-hardware-resources) | [![Installer with multiple platforms](https://github.com/yokawasa/actions-samples/workflows/Installer%20with%20multiple%20platforms/badge.svg)](https://github.com/yokawasa/actions-samples/actions?query=workflow%3A%22Installer+with+multiple+platforms%22) |
| [Run on containers](.github/workflows/run-on-containers.yml) | Running on containers using [jobs.<job_id>.container](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions#jobsjob_idcontainer) and [jobs.<job_id>.steps.uses](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions#jobsjob_idstepsuses) workflow syntaxes | [![Run on ontainers](https://github.com/yokawasa/actions-samples/workflows/Run%20on%20ontainers/badge.svg)](https://github.com/yokawasa/actions-samples/actions?query=workflow%3A%22Run+on+ontainers%22)|
| [Service containers](.github/workflows/service-containers.yml) | [Service containers](https://docs.github.com/en/actions/configuring-and-managing-workflows/about-service-containers) sample worlflow where you run a db client script that requires access to a Postgres database using [PostgreSQL service containers](https://docs.github.com/en/actions/configuring-and-managing-workflows/creating-postgresql-service-containers) | [![Postgres Service Containers](https://github.com/yokawasa/actions-samples/workflows/Postgres%20Service%20Containers/badge.svg)](https://github.com/yokawasa/actions-samples/actions?query=workflow%3A%22Postgres+Service+Containers%22) |
| [Cache dependencies](.github/workflows/cache.yml) | Sample of caching dependencies and build outputs to improve workflow execution time using [actions/cache](https://github.com/actions/cache) | [![Cache dependencies](https://github.com/yokawasa/actions-samples/workflows/Cache%20dependencies/badge.svg)](https://github.com/yokawasa/actions-samples/actions?query=workflow%3A%22Cache+dependencies%22) |
| [ChatOps with github-script](.github/workflows/github-script-chatops.yml) | Sample of achieving ChatOps that assign user to an issue using [action/github-script](https://github.com/actions/github-script). There are alot more things you can do with github-script. Find many samples [here](https://github.com/actions/github-script) | [![ChatOps with github-script](https://github.com/yokawasa/actions-samples/workflows/ChatOps%20with%20github-script/badge.svg)](https://github.com/yokawasa/actions-samples/actions?query=workflow%3A%22ChatOps+with+github-script%22)|
| [Vulnerability Scan with Trivy](.github/workflows/trivy-scan.yml) | Vulnerability Scan using [homoluctus/gitrivy](https://github.com/homoluctus/gitrivy), a GitHub Action that scan vulnerability using [Trivy](https://github.com/aquasecurity/trivy) |[![Vulnerability Scan with Trivy](https://github.com/yokawasa/actions-samples/workflows/Vulnerability%20Scan%20with%20Trivy/badge.svg)](https://github.com/yokawasa/actions-samples/actions?query=workflow%3A%22Vulnerability+Scan+with+Trivy%22) |
| [Setup Kube tools with custom action](.github/workflows/setup-kube-tools.yml) | Setup Kubernetes tools using custom TypeScript action, [yokawasa/action-setup-kube-tools](https://github.com/yokawasa/action-setup-kube-tools). Please see [this](https://docs.github.com/en/actions/creating-actions/creating-a-javascript-action) for detail of creating custom TS or JS action | [![Setup Kubernetes Tools](https://github.com/yokawasa/actions-samples/workflows/Setup%20Kubernetes%20Tools/badge.svg)](https://github.com/yokawasa/actions-samples/actions?query=workflow%3A%22Setup+Kubernetes+Tools%22) |

## Tips
- [How to refer versioned actions](docs/versioned-actions.md)
- [GitHub Actions 101 Slides](https://speakerdeck.com/yokawasa/zozotechbook1-ch03-githubactions) (Sorry only in Japanease)

## Contributing
Bug reports and pull requests are welcome on GitHub at https://github.com/yokawasa/actions-samples
