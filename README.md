# yoloc

YOLO-level verifier

## Usage

* Web: https://yoloc-6zw6p3u7ya-uc.a.run.app/
* CLI: `yoloc --repo <github repo> --image <image path>`

## Requirements

* go v1.18
* Some checks require a GitHub API token. To make your GitHub token accessible to the program, create an environment variable named `GITHUB_TOKEN` and set it equal to your personal GitHub API token. For instance, `export GITHUB_TOKEN='long_token_string_here`. See this [GitHub documentation](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) for help creating an API token.

## Installation

```
go install chainguard.dev/yoloc@latest
```
