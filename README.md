<p align="center">
  <br>
    <img src="awesome-actions.png" width="150"/>
  <br>
</p>

# Awesome Actions [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [<!--lint ignore no-dead-urls-->![GitHub Actions status | sdras/awesome-actions](https://github.com/correia-jpv/fucking-awesome-actions/workflows/Lint%20Awesome%20List/badge.svg)](https://github.com/correia-jpv/fucking-awesome-actions/actions?workflow=Lint+Awesome+List)

> A curated list of awesome things related to GitHub Actions.

Actions are triggered by GitHub platform events directly in a repo and run on-demand workflows either on Linux, Windows or macOS virtual machines or inside a container in response. With GitHub Actions you can automate your workflow from idea to production.

## Contents

- [Official Resources](#official-resources)
  - [Workflow Examples](#workflow-examples)
  - [Official Actions](#official-actions)
  - [Create your Actions](#create-your-actions)
- [Community Resources](#community-resources)
  - [GitHub Tools and Management](#github-tools-and-management)
  - [Collection of Actions](#collection-of-actions)
  - [Utility](#utility)
  - [Static Analysis](#static-analysis)
  - [Dynamic Analysis](#dynamic-analysis)
  - [Monitoring](#monitoring)
  - [Pull Requests](#pull-requests)
  - [GitHub Pages](#github-pages)
  - [Notifications and Messages](#notifications-and-messages)
  - [Deployment](#deployment)
  - [External Services](#external-services)
  - [Frontend Tools](#frontend-tools)
  - [Machine Learning Ops](#machine-learning-ops)
  - [Build](#build)
  - [Database](#database)
  - [Networking](#networking)
  - [Localization](#localization)
  - [Fun](#fun)
  - [Cheat Sheet](#cheat-sheet)
- [Tutorials](#tutorials)

## Official Resources

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Official Site](https://github.com/features/actions))
- 🌎 [Official Documentation](help.github.com/en/actions)
- [Official Actions organization](https://github.com/actions)
  - <b><code>&nbsp;11360⭐</code></b> <b><code>&nbsp;&nbsp;3358🍴</code></b> [actions/virtual-environments](https://github.com/actions/virtual-environments)) - GitHub Actions virtual environments.
  - <b><code>&nbsp;&nbsp;5343⭐</code></b> <b><code>&nbsp;&nbsp;1088🍴</code></b> [actions/runner](https://github.com/actions/runner)) - The Runner for GitHub Actions.
- 🌎 [GitHub Blog Announcement](github.blog/2018-10-17-action-demos/)

### Workflow Examples

- <b><code>&nbsp;10315⭐</code></b> <b><code>&nbsp;&nbsp;6099🍴</code></b> [actions/starter-workflows](https://github.com/actions/starter-workflows)) - Starter workflow management.
- <b><code>&nbsp;&nbsp;&nbsp;252⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;229🍴</code></b> [actions/example-services](https://github.com/actions/example-services)) - Example workflows using service containers.

### Official Actions

<!--lint disable no-dead-urls-->

#### Workflow Tool Actions

Tool actions for your workflow.

<!--lint ignore awesome-spell-check-->

- <b><code>&nbsp;&nbsp;6629⭐</code></b> <b><code>&nbsp;&nbsp;2020🍴</code></b> [actions/checkout](https://github.com/actions/checkout)) - Setup your repository on your workflow.
- <b><code>&nbsp;&nbsp;3590⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;855🍴</code></b> [actions/upload-artifact](https://github.com/actions/upload-artifact)) - Upload artifacts from your workflow.
- <b><code>&nbsp;&nbsp;1579⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;583🍴</code></b> [actions/download-artifact](https://github.com/actions/download-artifact)) - Download artifacts from your build.
- <b><code>&nbsp;&nbsp;4904⭐</code></b> <b><code>&nbsp;&nbsp;1331🍴</code></b> [actions/cache](https://github.com/actions/cache)) - Cache dependencies and build outputs in GitHub Actions.
- <b><code>&nbsp;&nbsp;4556⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;462🍴</code></b> [actions/github-script](https://github.com/actions/github-script)) - Write a script for GitHub API and the workflow contexts.

#### Actions for GitHub Automation

Automate management for issues, pull requests, and releases.

- <b><code>&nbsp;&nbsp;1358⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;320🍴</code></b> [actions/create-release](https://github.com/actions/create-release)) - An Action to create releases via the GitHub Release API.
- <b><code>&nbsp;&nbsp;&nbsp;702⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;196🍴</code></b> [actions/upload-release-asset](https://github.com/actions/upload-release-asset)) - An Action to upload a release asset via the GitHub Release API.
- <b><code>&nbsp;&nbsp;&nbsp;794⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;351🍴</code></b> [actions/first-interaction](https://github.com/actions/first-interaction)) - An action for filtering pull requests and issues from first-time contributors.
- <b><code>&nbsp;&nbsp;1498⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;388🍴</code></b> [actions/stale](https://github.com/actions/stale)) - Marks issues and pull requests that have not had recent interaction.
- <b><code>&nbsp;&nbsp;2214⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;441🍴</code></b> [actions/labeler](https://github.com/actions/labeler)) - An action for automatically labelling pull requests.
- <b><code>&nbsp;&nbsp;&nbsp;388⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87🍴</code></b> [actions/delete-package-versions](https://github.com/actions/delete-package-versions)) - Delete versions of a package from GitHub Packages.

#### Setup Actions

Set up your GitHub Actions workflow with a specific version of your programming languages.

- <b><code>&nbsp;&nbsp;4252⭐</code></b> <b><code>&nbsp;&nbsp;1422🍴</code></b> [actions/setup-node: Node.js](https://github.com/actions/setup-node))
- <b><code>&nbsp;&nbsp;1910⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;621🍴</code></b> [actions/setup-python: Python](https://github.com/actions/setup-python))
- <b><code>&nbsp;&nbsp;1518⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;581🍴</code></b> [actions/setup-go: Go](https://github.com/actions/setup-go))
- <b><code>&nbsp;&nbsp;1027⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;508🍴</code></b> [actions/setup-dotnet: .NET core sdk](https://github.com/actions/setup-dotnet))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [actions/setup-haskell: Haskell (GHC and Cabal)](https://github.com/actions/setup-haskell))
- <b><code>&nbsp;&nbsp;1671⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;786🍴</code></b> [actions/setup-java: Java](https://github.com/actions/setup-java))
- <b><code>&nbsp;&nbsp;&nbsp;175⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [actions/setup-ruby: Ruby](https://github.com/actions/setup-ruby))
- <b><code>&nbsp;&nbsp;&nbsp;154⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [actions/setup-elixir: Elixir](https://github.com/actions/setup-elixir))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [actions/setup-julia: Julia](https://github.com/julia-actions/setup-julia))

### Create your Actions

#### JavaScript and TypeScript Actions

- <b><code>&nbsp;&nbsp;5349⭐</code></b> <b><code>&nbsp;&nbsp;1570🍴</code></b> [actions/toolkit](https://github.com/actions/toolkit)) - The GitHub ToolKit for developing GitHub Actions.
- <b><code>&nbsp;&nbsp;&nbsp;270⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;241🍴</code></b> [actions/hello-world-javascript-action](https://github.com/actions/hello-world-javascript-action)) - A template to demonstrate how to build a JavaScript action.
- <b><code>&nbsp;&nbsp;1068⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;416🍴</code></b> [actions/javascript-action](https://github.com/actions/javascript-action)) - Create a JavaScript Action.
- <b><code>&nbsp;&nbsp;2242⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;531🍴</code></b> [actions/typescript-action](https://github.com/actions/typescript-action)) - Create a TypeScript Action.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [actions/http-client](https://github.com/actions/http-client)) - A lightweight HTTP client optimized for use with actions, TypeScript with generics and async await.

#### Docker Container Actions

- <b><code>&nbsp;&nbsp;&nbsp;176⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;178🍴</code></b> [actions/hello-world-docker-action](https://github.com/actions/hello-world-docker-action)) - A template to demonstrate how to build a Docker action.
- <b><code>&nbsp;&nbsp;&nbsp;138⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [actions/container-toolkit-action](https://github.com/actions/container-toolkit-action)) - Template repo for creating container actions using actions/toolkit.

## Community Resources

### GitHub Tools and Management

- <b><code>&nbsp;&nbsp;&nbsp;191⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Declaratively setup GitHub Labels](https://github.com/lannonbr/issue-label-manager-action))
- <b><code>&nbsp;&nbsp;&nbsp;212⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [Action to sync GitHub labels in the declarative way](https://github.com/micnncim/action-label-syncer))
- <b><code>&nbsp;&nbsp;&nbsp;201⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [Add releases to GitHub](https://github.com/elgohr/Github-Release-Action))
- <b><code>&nbsp;&nbsp;&nbsp;787⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;209🍴</code></b> [Publish a docker image to Dockerhub](https://github.com/elgohr/Publish-Docker-Github-Action))
- <b><code>&nbsp;&nbsp;&nbsp;154⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [Create an issue using content from a file](https://github.com/peter-evans/create-issue-from-file))
- <b><code>&nbsp;&nbsp;4834⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;525🍴</code></b> [Publish GitHub Releases with Assets](https://github.com/softprops/action-gh-release))
- <b><code>&nbsp;&nbsp;&nbsp;336⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97🍴</code></b> [GitHub Project Automation+](https://github.com/alex-page/github-project-automation-plus)) - Automate GitHub Project cards with any webhook event.
- <b><code>&nbsp;&nbsp;&nbsp;254⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Run GitHub Actions Locally with a web interface](https://github.com/phishy/wflow))
- <b><code>&nbsp;63807⭐</code></b> <b><code>&nbsp;&nbsp;1661🍴</code></b> [Run GitHub Actions Locally in Terminal](https://github.com/nektos/act))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [Build and Publish Android debug APK](https://github.com/ShaunLWM/action-release-debugapk))
- <b><code>&nbsp;&nbsp;&nbsp;140⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [Generate sequential build numbers for GitHub Actions](https://github.com/einaregilsson/build-number))
- <b><code>&nbsp;&nbsp;1241⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;236🍴</code></b> [Push Git changes to GitHub repository without authentication difficulties](https://github.com/ad-m/github-push-action))
- <b><code>&nbsp;&nbsp;&nbsp;120⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Generate release notes based on your events](https://github.com/Decathlon/release-notes-generator-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Create a GitHub wiki page based on the provided markdown file](https://github.com/Decathlon/wiki-page-creator-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Label your Pull Requests auto-magically (using committed files)](https://github.com/Decathlon/pull-request-labeler-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [Add Label to your Pull Requests based on the author team name](https://github.com/JulienKode/team-labeler-action))
- <b><code>&nbsp;&nbsp;&nbsp;167⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [Get a list of file changes with PR/Push](https://github.com/trilom/file-changes-action))
- <b><code>&nbsp;&nbsp;&nbsp;169⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [Use private actions in any workflow](https://github.com/InVisionApp/private-action-loader))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Label Your Issues Using the Issue's Contents](https://github.com/damccorm/tag-ur-it))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Rollback a GitHub Release](https://github.com/author/action-rollback))
- <b><code>&nbsp;&nbsp;&nbsp;320⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [Lock Closed Issues and Pull Requests after a Period of Inactivity](https://github.com/dessant/lock-threads))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Get Commit Difference Count Between Two Branches](https://github.com/jessicalostinspace/commit-difference-action))
- <b><code>&nbsp;&nbsp;&nbsp;141⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Generate Release Notes Based on Git References](https://github.com/metcalfc/changelog-generator))
- <b><code>&nbsp;&nbsp;&nbsp;469⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [Enforce Policies on GitHub Repositories and Commits](https://github.com/talos-systems/conform))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Auto Label Issue Based on Issue Description](https://github.com/Renato66/auto-label))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Update Configured GitHub Actions to the Latest Versions](https://github.com/fabasoad/ghacu))
- <b><code>&nbsp;&nbsp;&nbsp;334⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [Create Issue Branch](https://github.com/robvanderleek/create-issue-branch))
- <b><code>&nbsp;&nbsp;&nbsp;358⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [Remove Old Artifacts](https://github.com/c-hive/gha-remove-artifacts))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Expose Git Commit Data As Environment Variables](https://github.com/rlespinasse/git-commit-data-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Sync Defined Files/Binaries to Wiki or External Repositories](https://github.com/kai-tub/external-repo-sync-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [Create/Update/Delete a GitHub Wiki Page Based on Any File](https://github.com/Andrew-Chen-Wang/github-wiki-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Prow GitHub Actions](https://github.com/jpmcb/prow-github-actions)) - Automation of policy enforcement, chat-ops, and automatic PR merging.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Check GitHub Status in your Workflow](https://github.com/crazy-max/ghaction-github-status))
- <b><code>&nbsp;&nbsp;&nbsp;150⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [Manage Labels on GitHub (create/rename/update/delete) as Code](https://github.com/crazy-max/ghaction-github-labeler))
- <b><code>&nbsp;&nbsp;&nbsp;122⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [Continuous Distribution of Funding to your Project Contributors and Dependencies](https://github.com/protontypes/libreselery))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Herald Rules for GitHub: Add Subscribers, Assignees, Labels, and More to Your PR](https://github.com/gagoar/use-herald-action))
- <b><code>&nbsp;&nbsp;&nbsp;233⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [GitHub Codeowners Validator](https://github.com/mszostok/codeowners-validator)) - Ensures the correctness of your GitHub CODEOWNERS file. It supports public and private GitHub repositories and also GitHub Enterprise installations.
- <b><code>&nbsp;&nbsp;&nbsp;110⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Copybara Action](https://github.com/olivr/copybara-action)) - Move and transform code between repositories (ideal to maintain several repos from one monorepo).

### Collection of Actions

- <b><code>&nbsp;&nbsp;1476⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;258🍴</code></b> [Use HashiCorp's Terraform](https://github.com/hashicorp/setup-terraform))
- <b><code>&nbsp;&nbsp;&nbsp;311⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [GitHub Actions for Yarn 1](https://github.com/Borales/actions-yarn))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [GitHub Actions for Yarn 2](https://github.com/sergioramos/yarn-actions))
- <b><code>&nbsp;&nbsp;&nbsp;133⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [GitHub Actions for Golang](https://github.com/cedrickring/golang-action))
- [GitHub Actions for R and accompanying #rstats package](http://maxheld.de/ghactions/)
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [GitHub Actions for WordPress](https://github.com/10up/actions-wordpress/))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [GitHub Actions for Composer](https://github.com/MilesChou/composer-action))
- <b><code>&nbsp;&nbsp;2420⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;231🍴</code></b> [GitHub Actions for Flutter](https://github.com/subosito/flutter-action))
- <b><code>&nbsp;&nbsp;3061⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;381🍴</code></b> [GitHub Actions for PHP](https://github.com/shivammathur/setup-php))
- [GitHub Actions for Rust](https://github.com/actions-rs)
- <b><code>&nbsp;&nbsp;&nbsp;189⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [GitHub Actions for Android](https://github.com/Malinskiy/action-android))
- [GitHub Actions for Logtalk and Prolog](https://github.com/logtalk-actions)
- <b><code>&nbsp;&nbsp;&nbsp;181⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [GitHub Actions for Deno](https://github.com/denolib/setup-deno))
- <b><code>&nbsp;&nbsp;1039⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;122🍴</code></b> [GitHub Actions for Unity](https://github.com/webbertakken/unity-actions))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Octions - GitHub Actions for GitHub REST API](https://github.com/maxkomarychev/octions))
- <b><code>&nbsp;&nbsp;&nbsp;163⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [GitHub Actions for Docker](https://github.com/docker/github-actions))
- <b><code>&nbsp;&nbsp;&nbsp;120⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [GitHub Actions for AWS](https://github.com/clowdhaus/aws-github-actions))
- [Actions Hub](https://github.com/actionshub)

### Utility

- <b><code>&nbsp;&nbsp;1342⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;273🍴</code></b> [Setup `ssh-agent`](https://github.com/webfactory/ssh-agent)) - Run `ssh-agent` with additional SSH keys to access private repositories.
- <b><code>&nbsp;&nbsp;&nbsp;205⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [GitHub Actions Badges for your README](https://github.com/atrox/github-actions-badge))
- <b><code>&nbsp;&nbsp;&nbsp;456⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [GitHub Actions for Python project with poetry](https://github.com/abatilo/actions-poetry))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [GitHub Actions for Python project with pyenv](https://github.com/gabrielfalcao/pyenv-action))
- <b><code>&nbsp;&nbsp;1242⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;141🍴</code></b> [GitHub Actions to compile LaTeX documents](https://github.com/xu-cheng/latex-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Update Maxmind Databases](https://github.com/meetup/maxmind-updater))
- <b><code>&nbsp;&nbsp;3204⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;309🍴</code></b> [Debug with SSH over tmate](https://github.com/mxschmitt/action-tmate)) - Debug the Action directly by providing a SSH connection.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [Unlock git-crypt files](https://github.com/sliteteam/github-action-git-crypt-unlock))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Golang CGO cross compiler](https://github.com/crazy-max/ghaction-xgo))
- <b><code>&nbsp;&nbsp;&nbsp;727⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;164🍴</code></b> [Run your job on another architecture: arm32, aarch64 and others](https://github.com/uraimo/run-on-arch-action))
- <b><code>&nbsp;&nbsp;&nbsp;237⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Generate a table of contents](https://github.com/technote-space/toc-generator))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Automatically add Label or Assignee to an Issue](https://github.com/Naturalclar/issue-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Action to send LGTM reaction as image or GIF when we say lgtm](https://github.com/micnncim/action-lgtm-reaction))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Generate build numbers across multiple scopes](https://github.com/zyborg/gh-action-buildnum))
- <b><code>&nbsp;&nbsp;&nbsp;139⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [Publish GitHub release artifacts](https://github.com/skx/github-action-publish-binaries))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Jekyll Diff Action](https://github.com/David-Byrne/jekyll-diff-action)) - Diffs the built Jekyll site after a change, and comments the result back to GitHub.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [Branch Protection Bot](https://github.com/benjefferies/branch-protection-bot)) - Temporarily disable and re-enable "Include administrators" option in branch protection.
- <b><code>&nbsp;&nbsp;&nbsp;103⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Wait for commit statuses](https://github.com/WyriHaximus/github-action-wait-for-status)) - Wait until all statuses and checks are successful or any of them has failed and set its status output accordingly.
- <b><code>&nbsp;&nbsp;&nbsp;191⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [Get Latest Tag](https://github.com/WyriHaximus/github-action-get-previous-tag)) - Get the previous tag from git.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Create Milestone](https://github.com/WyriHaximus/github-action-create-milestone)) - Create a new open milestone given the title and description.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Close Milestone](https://github.com/WyriHaximus/github-action-close-milestone)) - Close the given milestone.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [Action to enforce branch naming rules](https://github.com/deepakputhraya/action-branch-name))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Expose slug of some GitHub variables](https://github.com/marketplace/actions/github-slug))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [awesome-lint as a GitHub Action](https://github.com/max/awesome-lint))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Edit JSON File](https://github.com/deef0000dragon1/json-edit-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Build Slate documentation](https://github.com/Decathlon/slate-builder-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Read Properties](https://github.com/christian-draeger/read-properties)) - Read values from `.properties` files.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Write Properties](https://github.com/christian-draeger/write-properties)) - Write values to `.properties` files.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [Autotag](https://github.com/butlerlogic/action-autotag)) - Automatically generate a new tag when the manifest file (i.e. `package.json`) version changes.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [Apply templates with Jinja2](https://github.com/cuchi/jinja2-action)) - Use the Jinja2 template engine to generate files from templates.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Has Changes](https://github.com/UnicornGlobal/has-changes-action)) - Check if there are code changes from previous steps.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Mind Your Language Action](https://github.com/tailaiw/mind-your-language-action)) - Detect offensive comments in issues and pull requests, and warn senders.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [YAML/JSON/XML Converter](https://github.com/fabasoad/yaml-json-xml-converter-action)) - Converts YAML/JSON/XML file formats interchangeably.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [NSFW Detection](https://github.com/fabasoad/nsfw-detection-action)) - Detect NSFW content in committed files.
- <b><code>&nbsp;&nbsp;&nbsp;228⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [Has Changed Path](https://github.com/MarceloPrado/has-changed-path)) - Conditionally run actions based on changed paths.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Linguist](https://github.com/fabasoad/linguist-action)) - Checks a repository and produces information about used languages in output.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Twilio Voice Call](https://github.com/fabasoad/twilio-voice-call-action/)) - Make Twilio voice call with defined text.
- <b><code>&nbsp;&nbsp;&nbsp;320⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [Setup Xcode](https://github.com/maxim-lobanov/setup-xcode)) - Switch between pre-installed versions of Xcode for macOS images.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Setup Xamarin](https://github.com/maxim-lobanov/setup-xamarin)) - Switch between pre-installed versions of Xamarin and Mono for macOS images.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Memer Action](https://github.com/Bhupesh-V/memer-action)) - A GitHub Action for Programmer Memes xD.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Setup Cocoapods](https://github.com/maxim-lobanov/setup-cocoapods)) - Setup specific version of Cocoapods.
- <b><code>&nbsp;&nbsp;&nbsp;124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [Public IP](https://github.com/haythem/public-ip)) - Queries GitHub actions runner's public IP address.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [GitHub Actions for Lazarus/FPC](https://github.com/gcarreno/setup-lazarus))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Twilio Fax](https://github.com/fabasoad/twilio-fax-action/)) - Sends a document by fax using your Twilio account.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [Setup Kubernetes tools](https://github.com/yokawasa/action-setup-kube-tools)) - Install Kubernetes tools (kubectl, kustomize, helm, kubeval, conftest, and yq) on the runner.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Setup Elastic Cloud Control Tool](https://github.com/yokawasa/action-setup-ecctl)) - Install a specific version of ecctl on the runner.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [PowerShell Script](https://github.com/Amadevus/pwsh-script)) - Run PowerShell scripts with workflow contexts (e.g. `$github.token`) and cmdlets, return value => action output.
- <b><code>&nbsp;&nbsp;&nbsp;183⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Upload and Scan Files with VirusTotal](https://github.com/crazy-max/ghaction-virustotal))
- <b><code>&nbsp;&nbsp;&nbsp;350⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [Import a GPG Key](https://github.com/crazy-max/ghaction-import-gpg))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Compress with UPX](https://github.com/crazy-max/ghaction-upx)) - The Ultimate Packer for eXecutables.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Pull the New Go Module Version Into the Proxy Cache](https://github.com/andrewslotin/go-proxy-pull-action)) - Ensures the latest version of your Go module is in the proxy cache. Also updates the pkg.go.dev documentation upon release.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Delete Run Artifacts](https://github.com/marketplace/actions/delete-run-artifacts)) - Deletes all artifacts at the end of a workflow run.
- <b><code>&nbsp;&nbsp;&nbsp;187⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [GitHub Environment Variables Action](https://github.com/FranzDiebold/github-env-vars-action)) - Expose environment variables such as the branch/tag name, repository slug, and ref slug.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [GitHub Action Locks](https://github.com/abatilo/github-action-locks/blob/master/README.md)) - Guarantee atomic execution of your GitHub Action workflows.
- <b><code>&nbsp;&nbsp;2552⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;299🍴</code></b> [Paths Filter](https://github.com/dorny/paths-filter)) - Conditionally run actions based on files modified by PR, feature branch or pushed commits.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Minisauras](https://github.com/TeamTigers/minisauras)) -  Pulls all the JavaScript and CSS files from your base branch, minify them and creates a pull-request with a new branch.
- <b><code>&nbsp;&nbsp;&nbsp;145⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Website to GIF](https://github.com/PabloLec/website-to-gif)) - Turn any webpage into a GIF to display on your README, docs, etc.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Interactive Inputs - Runtime workflow inputs](https://github.com/boasiHQ/interactive-inputs)) - Add dynamic inputs at runtime for your GitHub Actions workflows

#### Environments

- <b><code>&nbsp;&nbsp;&nbsp;454⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [Create an envfile](https://github.com/SpicyPizza/create-envfile))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Export global environment variables for succeeding build steps](https://github.com/zweitag/github-actions))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Programmatically set environment variables for use in subsequent steps](https://github.com/allenevans/set-env))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Install Conda environments for Python](https://github.com/goanpeca/setup-miniconda))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Setup NativeScript](https://github.com/hrueger/setup-nativescript))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Create a JSON Environment File](https://github.com/schdck/create-env-json))

#### Dependencies

- <b><code>&nbsp;&nbsp;&nbsp;668⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [Install NPM Dependencies with Caching](https://github.com/bahmutov/npm-install))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Highlight New NPM Dependencies](https://github.com/hiwelo/new-dependencies-action)) - Comments on pull requests newly added NPM dependencies information.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Cache NPM Dependencies](https://github.com/c-hive/gha-npm-cache))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Cache Yarn Dependencies](https://github.com/c-hive/gha-yarn-cache))

#### Semantic Versioning

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Next SemVers](https://github.com/WyriHaximus/github-action-next-semvers)) - Output the next version for major, minor, and patch version based on the given semver version.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Get latest SemVer and branch name given a search string](https://github.com/jessicalostinspace/github-action-get-regex-branch))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Cut Release Branch](https://github.com/jessicalostinspace/cut-release-action)) - Cuts a release branch given a branch prefix and optional semantic version.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Increment Semantic Version](https://github.com/christian-draeger/increment-semantic-version)) - Bump a given semantic version (SemVer), depending on given release type.

### Static Analysis

- <b><code>&nbsp;&nbsp;&nbsp;101⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [PHPStan Static code analyzer Action](https://github.com/OskarStark/phpstan-ga))
- <b><code>&nbsp;&nbsp;1710⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;200🍴</code></b> [GraphQL Inspector Action](https://github.com/kamilkisiela/graphql-inspector))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [PowerShell static analysis with PSScriptAnalyzer](https://github.com/devblackops/github-action-psscriptanalyzer))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Run tfsec, with reviewdog output on the PR](https://github.com/reviewdog/action-tfsec))

#### Testing

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [Run Tests through Puppeteer, the Headless Chrome Node API](https://github.com/ianwalter/puppeteer))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [xUnit Slack Reporter: Sends summary of tests from xUnit reports to a Slack channel](https://github.com/ivanklee86/xunit-slack-reporter))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Run codeception tests](https://github.com/joelwmale/codeception-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Run TestCafe tests](https://github.com/DevExpress/testcafe-action))
- <b><code>&nbsp;&nbsp;&nbsp;232⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;142🍴</code></b> [Run Unity tests](https://github.com/webbertakken/unity-test-runner))
- <b><code>&nbsp;&nbsp;1399⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;366🍴</code></b> [Run Cypress E2E tests](https://github.com/cypress-io/github-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Test Ansible roles with Molecule](https://github.com/robertdebock/molecule-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Run performance testing with artillery.io](https://github.com/kenju/github-actions-artillery))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Detect Flaky Tests with BuildPulse](https://github.com/Workshop64/buildpulse-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Display Inline Code Annotations for Jest Tests](https://github.com/IgnusG/jest-report-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [Run Julia tests](https://github.com/julia-actions/julia-runtest))

#### Linting

- <b><code>&nbsp;&nbsp;&nbsp;190⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [PHP Coding Standards Fixer Action](https://github.com/OskarStark/php-cs-fixer-ga))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Runs Hadolint against a Dockerfile within a repository](https://github.com/burdzwastaken/hadolint-action))
- <b><code>&nbsp;&nbsp;&nbsp;249⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [Run ESLint, with reviewdog output on the PR](https://github.com/reviewdog/action-eslint))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [JavaScript-based linter for \*.workflow files](https://github.com/OmarTawfik/github-actions-js))
- <b><code>&nbsp;&nbsp;&nbsp;113⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [Lint terraform files using tflint, with reviewdog output on the PR](https://github.com/reviewdog/action-tflint))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [autopep8: Automatically formats Python code to conform to the PEP 8 style guide](https://github.com/peter-evans/autopep8))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Run `ergebnis/composer-normalize` to ensure your PHP project has a normalized `composer.json`](https://github.com/ergebnis/composer-normalize-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Run `stolt/lean-package-validator` to ensure your package has only the required `runtime` artifacts](https://github.com/raphaelstolt/lean-package-validator-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Run Go lint checks on PR event](https://github.com/ArangoGutierrez/GoLinty-Action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Node.js - Automatically run the `format` and/or `lint` script used by the package](https://github.com/MarvinJWendt/run-node-formatter))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Stylelinter - GitHub Action that runs stylelint](https://github.com/exelban/stylelint))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Run stylelint, with reviewdog output on the PR](https://github.com/reviewdog/action-stylelint))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [PyCodeStyle Action - A GitHub Action that leaves a comment on your PR with pycodestyle (autopep8) feedback](https://github.com/ankitvgupta/pycodestyle-action))
- <b><code>&nbsp;&nbsp;2734⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;404🍴</code></b> [wemake-python-styleguide - The strictest and most opinionated python linter ever, with optional reviewdog output on the PR](https://github.com/wemake-services/wemake-python-styleguide))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [Run TSLint with status checks and file diff annotations](https://github.com/mooyoul/tslint-actions))
- <b><code>&nbsp;&nbsp;&nbsp;376⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [Lint Pull Request commits with commitlint](https://github.com/wagoid/commitlint-github-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Run vint, with reviewdog output on the PR](https://github.com/reviewdog/action-vint))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [Run mispell, with reviewdog output on the PR](https://github.com/reviewdog/action-misspell))
- <b><code>&nbsp;&nbsp;&nbsp;231⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [Run golangci-lint, with reviewdog output on the PR](https://github.com/reviewdog/action-golangci-lint))
- <b><code>&nbsp;&nbsp;&nbsp;110⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Run shellcheck, with reviewdog output on the PR](https://github.com/reviewdog/action-shellcheck))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Catch insensitive, inconsiderate writing in your markdown docs](https://github.com/theashraf/alex-action))
- <b><code>&nbsp;&nbsp;&nbsp;294⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Run dotenv-linter - Lints your .env files like a charm, with optional reviewdog output on the PR](https://github.com/wemake-services/dotenv-linter))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Run dotenv-linter, with reviewdog output on the PR](https://github.com/mgrachev/action-dotenv-linter))
- <b><code>&nbsp;&nbsp;&nbsp;595⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;143🍴</code></b> [Show and auto-fix linting errors for many programming languages](https://github.com/samuelmeuli/lint-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [PHP_CodeSniffer With Annotations](https://github.com/chekalsky/phpcs-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Linter for markdown (with presets)](https://github.com/avto-dev/markdown-lint))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Stylelint problem matcher to create annotations](https://github.com/xt0rted/stylelint-problem-matcher))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Run sqlcheck on the PR to identifies anti-patterns in SQL queries](https://github.com/yokawasa/action-sqlcheck))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Validate Fastlane Supply Metadata Against the Play Store Guidelines](https://github.com/ashutoshgngwr/validate-fastlane-supply-metadata))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Run Golint to lint your Golang code](https://github.com/Jerome1337/golint-action))

#### Security

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [A vulnerability scanner for your docker images](https://github.com/phonito/phonito-scanner-action))
- <b><code>&nbsp;&nbsp;&nbsp;317⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Automatically approve and merge Dependabot updates](https://github.com/ridedott/dependabot-auto-merge-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Run dlint security linter on your Python code](https://github.com/xen0l/dlint-check))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [AWS Secrets Manager Actions](https://github.com/say8425/aws-secrets-manager-actions)) - Define AWS Secrets Manager secrets to environment values.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Linting your AWS IAM policy documents for correctness and security issues](https://github.com/xen0l/iam-lint))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Secret Spreader](https://github.com/webfactory/secret-spreader)) - Not an action per se, but a tool to manage Actions Secrets across a list of repositories.
- <b><code>&nbsp;&nbsp;&nbsp;323⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [Secrets Sync Action](https://github.com/google/secrets-sync-action)) - Action syncs secrets across multiple repositories.
- <b><code>&nbsp;&nbsp;&nbsp;568⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;192🍴</code></b> [Snyk Test Action](https://github.com/snyk/actions))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Manage Your GitHub Actions Secrets With A Simple CLI](https://github.com/unfor19/githubsecrets))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [SecretHub](https://github.com/secrethub/actions)) - Have a single source of truth for your secrets and load them into GitHub Actions on demand.

#### Code Coverage

- <b><code>&nbsp;&nbsp;&nbsp;606⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;230🍴</code></b> [Scan code with SonarCloud](https://github.com/sonarsource/sonarcloud-github-action))
- <b><code>&nbsp;&nbsp;1557⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;224🍴</code></b> [Send your code coverage to codecov.io](https://github.com/codecov/codecov-action))
- <b><code>&nbsp;&nbsp;&nbsp;206⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [Publishing code coverage to CodeClimate](https://github.com/paambaati/codeclimate-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Update repository go report card](https://github.com/creekorful/goreportcard-action))

### Dynamic Analysis

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Run Gofmt to check Golang code formatting](https://github.com/Jerome1337/gofmt-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Run Goimports to check Golang imports order](https://github.com/Jerome1337/goimports-action))

### Monitoring

- <b><code>&nbsp;&nbsp;&nbsp;345⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [Audit a webpage with Google Chrome's Lighthouse tests](https://github.com/jakejarvis/lighthouse-action))
- <b><code>&nbsp;&nbsp;&nbsp;497⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [Runs Lighthouse and posts results to PRs and Slack](https://github.com/foo-software/lighthouse-check-action))
- <b><code>&nbsp;&nbsp;1218⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87🍴</code></b> [Run Lighthouse in CI using GitHub Actions](https://github.com/treosh/lighthouse-ci-action))
- <b><code>&nbsp;&nbsp;&nbsp;150⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Continuous Benchmarking and Benchmark Visualization for Go](https://github.com/bobheadxi/gobenchdata))
- <b><code>&nbsp;&nbsp;&nbsp;460⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86🍴</code></b> [Size Limit Action](https://github.com/andresz1/size-limit-action)) - Comments cost comparison of your JS in PRs and rejects them if limit is exceeded.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Check bundlephobia](https://github.com/carlesnunez/check-my-bundlephobia)) - Comments new and modified package size according to bundlephobia.io website and rejects PR on threshold surpassed.

### Pull Requests

- <b><code>&nbsp;&nbsp;&nbsp;123⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;73🍴</code></b> [Set PR Reviewers Based on Assignees](https://github.com/pullreminders/assignee-to-reviewer-action))
- <b><code>&nbsp;&nbsp;&nbsp;173⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [Open or Update PR on Branch Push (with Branch Selection)](https://github.com/vsoch/pull-request-action))
- <b><code>&nbsp;&nbsp;&nbsp;699⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;143🍴</code></b> [Automatically Rebase a PR](https://github.com/cirrus-actions/rebase))
- <b><code>&nbsp;&nbsp;&nbsp;192⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;132🍴</code></b> [Label PR once it has a Specified Number of Approvals](https://github.com/pullreminders/label-when-approved-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Add Labels to a PR based on Matched File Patterns](https://github.com/banyan/auto-label))
- <b><code>&nbsp;&nbsp;&nbsp;445⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [Auto-Approve PRs](https://github.com/hmarr/auto-approve-action))
- <b><code>&nbsp;&nbsp;&nbsp;346⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [Automatically add Reviewers to PR based on the Configuration File](https://github.com/kentaro-m/auto-assign-action))
- <b><code>&nbsp;&nbsp;&nbsp;258⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [Add Labels to a PR based on Branch Name Patterns](https://github.com/TimonVS/pr-labeler-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [Add Labels to a PR based on Total Size of the Diff](https://github.com/pascalgn/size-label-action))
- <b><code>&nbsp;&nbsp;&nbsp;893⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;216🍴</code></b> [Automatically merge PRs That Are Ready](https://github.com/pascalgn/automerge-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [Verify That PRs Contain a Ticket Reference](https://github.com/vijaykramesh/pr-lint-action))
- <b><code>&nbsp;&nbsp;2413⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;480🍴</code></b> [Create a PR for Changes to your Repository in the Actions Workspace](https://github.com/peter-evans/create-pull-request))
- <b><code>&nbsp;&nbsp;&nbsp;120⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [Lint a PR](https://github.com/seferov/pr-lint-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [ChatOps for PRs](https://github.com/machine-learning-apps/actions-chatops))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [Prefix Title and Body of a PR Based on Text Extracted from Branch Name](https://github.com/tzkhan/pr-update-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Block Autosquash Commits](https://github.com/xt0rted/block-autosquash-commits-action))
- <b><code>&nbsp;&nbsp;&nbsp;830⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;391🍴</code></b> [Automatically Bump and Tag on Merge](https://github.com/anothrNick/github-tag-action))
- <b><code>&nbsp;&nbsp;&nbsp;142⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Automatically Update PRs with Outdated Checks and Squash and Merge the Ones Matching All Branch Protections](https://github.com/tibdex/autosquash))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Merge Pal - Automatically Update and Merge PRs](https://github.com/maxkomarychev/merge-pal-action))
- <b><code>&nbsp;&nbsp;&nbsp;137⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81🍴</code></b> [Enforce naming convention on pull request title](https://github.com/deepakputhraya/action-pr-title))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Pull Request Stuck Notifier](https://github.com/jrylan/github-action-stuck-pr-notifier))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Lint pull request name with commitlint (Awesome if you squash merge !)](https://github.com/JulienKode/pull-request-name-linter-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Block PR merges when Checks for target branches are failing](https://github.com/cirrus-actions/branch-guard))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Get generated static site screenshots updated by Pull Request](https://github.com/ssowonny/diff-pages-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Add Labels Depending if the Pull Request Still in Progress](https://github.com/AlbertHernandez/working-label-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [Ticket Check Action](https://github.com/neofinancial/ticket-check-action)) - Automatically add a ticket or issue number to the start of all Pull Request titles.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Pull Request Lint With Regex](https://github.com/MorrisonCole/pr-lint-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Pull Request Landmines](https://github.com/tylermurry/github-pr-landmine))
- <b><code>&nbsp;&nbsp;&nbsp;195⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Annotate a GitHub Pull Request Based on a Checkstyle XML-Report](https://github.com/staabm/annotate-pull-request-from-checkstyle))
- <b><code>&nbsp;&nbsp;&nbsp;379⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80🍴</code></b> [Pull Request Stats](https://github.com/flowwer-dev/pull-request-stats)) -  Print relevant stats about reviewers.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Pull Request Description Enforcer](https://github.com/derkinderfietsen/pr-description-enforcer)) - Enforces description on pull requests.

### GitHub Pages

- <b><code>&nbsp;&nbsp;&nbsp;263⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98🍴</code></b> [Deploy a Zola site to GitHub Pages](https://github.com/shalzz/zola-deploy-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Build Hugo static content site and publish it to gh-pages branch](https://github.com/khanhicetea/gh-actions-hugo-deploy-gh-pages))
- <b><code>&nbsp;&nbsp;&nbsp;120⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [Build a Jekyll site—with Custom Jekyll Plugins & Build Scripts—and deploy it back to the Gh-Pages Branch](https://github.com/BryanSchuetz/jekyll-deploy-gh-pages))
- 🌎 [Google Dataset Search Metadata](www.github.com/openschemas/extractors/) - And other schema.org extractors to make datasets discoverable from GitHub pages.
- <b><code>&nbsp;&nbsp;4992⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;416🍴</code></b> [GitHub Actions for deploying to GitHub Pages with Static Site Generators](https://github.com/peaceiris/actions-gh-pages))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [GitHub Action for Hexo](https://github.com/heowc/action-hexo))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Deploy Google Analytics stats to GitHub Pages](https://github.com/cristianpb/analytics-google))
- <b><code>&nbsp;&nbsp;3538⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;745🍴</code></b> [A Jupyter Notebook Blogging Platform Powered by GitHub Actions, Pages and Jekyll](https://github.com/fastai/fastpages))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Deploy A Static Site to GitHub Pages](https://github.com/appleboy/gh-pages-action)) - Deploy to custom directory and ignore folder/file.
- <b><code>&nbsp;&nbsp;&nbsp;478⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55🍴</code></b> [Deploy to GitHub Pages with Advanced Settings](https://github.com/crazy-max/ghaction-github-pages))

### Notifications and Messages

- <b><code>&nbsp;&nbsp;&nbsp;438⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [Send a Discord notification](https://github.com/Ilshidur/action-discord))
- <b><code>&nbsp;&nbsp;&nbsp;274⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [Post a Slack message as a bot](https://github.com/pullreminders/slack-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Send an SMS from GitHub Actions using Nexmo](https://github.com/nexmo-community/nexmo-sms-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Send an SMS from GitHub Actions using Clockworksms](https://github.com/bharathvaj1995/clockwork-sms-action))
- <b><code>&nbsp;&nbsp;&nbsp;938⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;112🍴</code></b> [Send a Telegram Message](https://github.com/appleboy/telegram-action))
- <b><code>&nbsp;&nbsp;&nbsp;115⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Send a File or Text Message to Discord (custom define color, username or avatar)](https://github.com/appleboy/discord-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Collaborate on tweets using pull requests](https://github.com/gr2m/twitter-together))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [Send a Push Notification via Push by Techulus](https://github.com/techulus/push-github-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Send email with SendGrid](https://github.com/peter-evans/sendgrid-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Send a Push Notification via Join](https://github.com/ShaunLWM/action-join))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [New package version checker for npm](https://github.com/MeilCli/npm-update-check-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [New package version checker for NuGet](https://github.com/MeilCli/nuget-update-check-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [New package version checker for Gradle](https://github.com/MeilCli/gradle-update-check-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Send a Push Notification via Pushbullet](https://github.com/ShaunLWM/action-pushbullet))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Create an Outlook Calendar Event using Microsoft Graph](https://github.com/anoopt/ms-graph-create-event))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Watch for GitHub Wiki page changes and post to Slack](https://github.com/benmatselby/gollum-page-watcher-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Send an SMS using MessageBird](https://github.com/nikitasavinov/messagebird-sms-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Reply to Stale Bots](https://github.com/c-hive/fresh-bot))
- <b><code>&nbsp;&nbsp;&nbsp;193⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Send an Embed Message to Discord](https://github.com/sarisia/actions-status-discord))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Keep Your PRs in Sync With Teamwork Tasks](https://github.com/Teamwork/github-sync))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Send Microsoft Teams Notification](https://github.com/opsless/ms-teams-github-actions))

### Deployment

- <b><code>&nbsp;&nbsp;&nbsp;376⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [Deploy to Netlify](https://github.com/netlify/actions))
- 🌎 [Deploy a Probot App using Actions](probot.github.io/docs/deployment/#github-actions)
- <b><code>&nbsp;&nbsp;&nbsp;116⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Deploy a playlist to Spotify](https://github.com/swinton/SpotHub))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Deploy VS Code extensions with vsce](https://github.com/lannonbr/vsce-action))
- <b><code>&nbsp;&nbsp;&nbsp;139⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Purge Cloudflare cache after updating a website](https://github.com/jakejarvis/cloudflare-purge-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [Deploy your DNS configuration using DNS Control](https://github.com/koenrh/dnscontrol-action))
- <b><code>&nbsp;&nbsp;&nbsp;130⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [Deploy a Theme to Shopify](https://github.com/pgrimaud/action-shopify))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Trigger multiple GitLab CI Pipeline](https://github.com/appleboy/gitlab-ci-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [Trigger multiple Jenkins Jobs](https://github.com/appleboy/jenkins-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [GitHub Action for Homebrew Tap](https://github.com/izumin5210/action-homebrew-tap))
- <b><code>&nbsp;&nbsp;1412⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;146🍴</code></b> [Copy files and artifacts via SSH](https://github.com/appleboy/scp-action))
- <b><code>&nbsp;&nbsp;5492⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;631🍴</code></b> [Executing remote ssh commands](https://github.com/appleboy/ssh-action))
- <b><code>&nbsp;&nbsp;1046⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;100🍴</code></b> [Publish a Python distribution package to PyPI](https://github.com/pypa/gh-action-pypi-publish))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Deploy Static Website to Azure Storage](https://github.com/feeloor/azure-static-website-deploy))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Cross platform Chocolatey CLI to build and publish packages](https://github.com/crazy-max/ghaction-chocolatey))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Deploy iOS Pod Library to Cocoapods](https://github.com/michaelhenry/deploy-to-cocoapods-github-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [GitHub Action for TencentCloud Serverless](https://github.com/Juliiii/action-scf))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Publish npm (pre)releases](https://github.com/epeli/npm-release/))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Deploy a static site to Surge.sh](https://github.com/yavisht/deploy-via-surge.sh-github-action-template))
- <b><code>&nbsp;&nbsp;&nbsp;919⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84🍴</code></b> [GitHub Action for GoReleaser, a release automation tool for Go projects](https://github.com/goreleaser/goreleaser-action))
- <b><code>&nbsp;&nbsp;4351⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;400🍴</code></b> [FTP Deploy Action, Deploys a GitHub project to a FTP server using GitHub actions](https://github.com/SamKirkland/FTP-Deploy-Action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Publish Article to Dev.to](https://github.com/tylerauerbeck/publish-to-dev.to-action))
- <b><code>&nbsp;&nbsp;&nbsp;608⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;102🍴</code></b> [Action For Semantic Release](https://github.com/cycjimmy/semantic-release-action))
- <b><code>&nbsp;&nbsp;&nbsp;107⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Deploy a Collection to Ansible Galaxy](https://github.com/artis3n/ansible_galaxy_collection))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Publish module to Puppet Forge](https://github.com/barnumbirr/action-forge-publish))
- <b><code>&nbsp;&nbsp;&nbsp;700⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;216🍴</code></b> [Build and publish Electron apps](https://github.com/samuelmeuli/action-electron-builder))
- <b><code>&nbsp;&nbsp;&nbsp;101⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [Publish a Maven package](https://github.com/samuelmeuli/action-maven-publish))
- <b><code>&nbsp;&nbsp;&nbsp;375⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [Build and deploy a theme to Ghost CMS](https://github.com/TryGhost/action-deploy-theme))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Deploy an Ansible role to Ansible Galaxy](https://github.com/robertdebock/galaxy-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Publish one or more JS modules to a registry](https://github.com/author/action-publish))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Publish a package with 2FA using Slack](https://github.com/erezrokah/2fa-with-slack-action))
- <b><code>&nbsp;&nbsp;&nbsp;327⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [Serialize Workflow Runs in Continuous Deployment Pipelines](https://github.com/softprops/turnstyle))
- <b><code>&nbsp;&nbsp;&nbsp;347⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [Netlify Deploy GitHub Action for each commit](https://github.com/nwtgck/actions-netlify))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Run Ansible Playbooks](https://github.com/arillso/action.playbook))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [Publish a Python Distribution Package to Anaconda Cloud](https://github.com/fcakyon/conda-publish-action))
- <b><code>&nbsp;&nbsp;&nbsp;225⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [Deploy VS Code Extension to Visual Studio Marketplace or the Open VSX Registry](https://github.com/HaaLeo/publish-vscode-extension))
- <b><code>&nbsp;&nbsp;&nbsp;140⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78🍴</code></b> [Deploy a YouTube Video to Anchor.fm Podcast](https://github.com/Schrodinger-Hat/youtube-to-anchorfm))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Deploy with AWS CodeDeploy](https://github.com/webfactory/create-aws-codedeploy-deployment))

#### Docker

- <b><code>&nbsp;&nbsp;&nbsp;350⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [Update a Docker Hub repository description from README.md](https://github.com/peter-evans/dockerhub-description))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [Publish Docker Images to the GitHub Package Registry (GPR)](https://github.com/machine-learning-apps/gpr-docker-publish))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Update a repository's "Full description" on Docker Hub](https://github.com/mpepping/github-actions/tree/master/docker-hub-metadata))
- <b><code>&nbsp;&nbsp;&nbsp;124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [Build and publish docker images to any registry using Kaniko](https://github.com/outillage/kaniko-action))
- <b><code>&nbsp;&nbsp;&nbsp;125⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Monitor and limit your docker image size](https://github.com/wemake-services/docker-image-size-limit))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Publish Docker Images to the Amazon Elastic Container Registry (ECR)](https://github.com/appleboy/docker-ecr-action))
- <b><code>&nbsp;&nbsp;&nbsp;345⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [Build And Push Your Docker Images Caching Each Stage To Reduce Build Time](https://github.com/whoan/docker-build-with-cache-action))
- <b><code>&nbsp;&nbsp;&nbsp;226⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [Set up Docker Buildx](https://github.com/crazy-max/ghaction-docker-buildx))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Convert Branch or Tag Name Into Docker-Compatible Image Tag](https://github.com/ankitvgupta/ref-to-tag-action/))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Update a Container Repository Description From README.md](https://github.com/marketplace/actions/update-container-description-action)) - Supported Registries: Docker Hub, Quay, Harbor.

#### Kubernetes

- <b><code>&nbsp;&nbsp;&nbsp;273⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [Deploy to any Cloud or Kubernetes Using Pulumi](https://github.com/pulumi/actions))
- <b><code>&nbsp;&nbsp;&nbsp;218⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [Deploy to Kubernetes with kubectl](https://github.com/steebchen/kubectl))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Get Kubeconfig File From Google Kubernetes Engine (GKE)](https://github.com/machine-learning-apps/gke-kubeconfig))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [Kustomize Kubernetes Config YAMLs](https://github.com/karancode/kustomize-github-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Create a Kubernetes Cluster for Testing Using Krucible](https://github.com/Krucible/krucible-github-action))

#### AWS

- <b><code>&nbsp;&nbsp;1069⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;489🍴</code></b> [Sync/upload a directory to an AWS S3 bucket](https://github.com/jakejarvis/s3-sync-action))
- <b><code>&nbsp;&nbsp;&nbsp;427⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [Deploy Lambda code to an existing function](https://github.com/appleboy/lambda-action))

#### Terraform

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Generate terraform documentation](https://github.com/Dirrk/terraform-docs)) - Uses terraform-docs to generate docs for terraform modules.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [An example of using Terraform to validate and apply GitHub administration](https://github.com/asgharlabs/github-terraform/tree/master/.github/workflows))

### External Services

- <b><code>&nbsp;&nbsp;&nbsp;208⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [Use a Jenkinsfile](https://github.com/jonico/jenkinsfile-runner-github-actions))
- <b><code>&nbsp;&nbsp;&nbsp;939⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;202🍴</code></b> [GitHub Action for Firebase](https://github.com/w9jds/firebase-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [GitHub Action for Contentful Migration CLI](https://github.com/Shy/contentful-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [GitHub Actions for Pixela (a-know/pi)](https://github.com/peaceiris/actions-pixela))
- <b><code>&nbsp;&nbsp;&nbsp;242⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [GitHub Action for Google Cloud Platform (GCP)](https://github.com/exelban/gcloud))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Upload files to any OpenStack Swift service provider](https://github.com/iksaku/openstack-swift-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [GitHub Action for sending Stack Overflow posts to Slack](https://github.com/logankilpatrick/StackOverflowBot))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Assume AWS role](https://github.com/nordcloud/aws-assume-role/))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Generate Custom Response using JSONbin](https://github.com/fabasoad/jsonbin-action))

### Frontend Tools

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Execute Gradle task](https://github.com/MrRamych/gradle-actions))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [JS Build Actions](https://github.com/elstudio/actions-js-build)) - Run Grunt or Gulp build tasks and commit file changes.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [GitHub Action for Gatsby CLI](https://github.com/jzweifel/gatsby-cli-github-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Runs a WebPageTest audit and prints the results as commit comment](https://github.com/JCofman/webPagetestAction))
- <b><code>&nbsp;&nbsp;1499⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90🍴</code></b> [GitHub Actions for Hugo extended](https://github.com/peaceiris/actions-hugo))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Generate OG Image](https://github.com/BoyWithSilverWings/generate-og-image)) - Generate customisable open graph images from Markdown files.
- <b><code>&nbsp;&nbsp;&nbsp;315⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [GitHub Actions for mdBook](https://github.com/peaceiris/actions-mdbook))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Setup Mint](https://github.com/fabasoad/setup-mint-action)) - Setup Mint (programming language for writing single page applications).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Gatsby AWS S3 Deployment](https://github.com/jonelantha/gatsby-s3-action)) - Deploy Gatsby to S3 (supports CloudFront).

### Machine Learning Ops

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Submitting Argo Workflows (Cloud Agnostic)](https://github.com/machine-learning-apps/actions-argo))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Submitting Argo Workflows to GKE](https://github.com/machine-learning-apps/gke-argo))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Query Experiment Tracking Results From Weights & Biases](https://github.com/machine-learning-apps/wandb-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;73⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Run Parameterized Jupyter Notebooks](https://github.com/yaananth/run-notebook))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [Compile, Deploy and Run Kubeflow Pipeline](https://github.com/NikeNano/kubeflow-github-action))
- <b><code>&nbsp;&nbsp;&nbsp;145⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [Automatically Dockerize A Data-Science Repo As A Jupyter Server](https://github.com/jupyterhub/repo2docker-action))
- <b><code>&nbsp;&nbsp;&nbsp;129⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [Azure Machine Learning With GitHub Actions](https://github.com/machine-learning-apps/ml-template-azure))

### Build

- <b><code>&nbsp;&nbsp;&nbsp;191⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [run-cmake](https://github.com/lukka/run-cmake)) - Multi platform action to build C/C++ software with 🌎 [CMake](cmake.org) and 🌎 [Ninja](ninja-build.org/).
- <b><code>&nbsp;&nbsp;&nbsp;212⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [run-vcpkg](https://github.com/lukka/run-vcpkg)) - Multi platform action to build and install C/C++ dependencies with <b><code>&nbsp;25045⭐</code></b> <b><code>&nbsp;&nbsp;6917🍴</code></b> [vcpkg](https://github.com/microsoft/vcpkg)).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Build Go applications for multiplatform](https://github.com/izumin5210/action-go-crossbuild))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [Generate ~/.m2/settings.xml for Maven builds](https://github.com/whelk-io/maven-settings-xml-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Run Pascal Script](https://github.com/fabasoad/pascal-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Setup Brainfuck](https://github.com/fabasoad/setup-brainfuck-action)) - Setup brainfuck interpreter.
- <b><code>&nbsp;&nbsp;&nbsp;530⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83🍴</code></b> [Publish Go Binaries to GitHub Release Assets](https://github.com/wangyoucao577/go-release-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Setup COBOL](https://github.com/fabasoad/setup-cobol-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Check Gradle version](https://github.com/madhead/check-gradle-version)) - Keep your Gradle version up to date.

### Database

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Setup Cassandra Schema](https://github.com/fabasoad/setup-cassandra-action)) - Running scripts from the provided folder on top of Cassandra cluster.

### Networking

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Setup ZeroTier](https://github.com/zerotier/github-action)) - Connect your runner to a ZeroTier network.

### Localization

- <b><code>&nbsp;&nbsp;&nbsp;151⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Find and automatically fix typos and grammar issues in your code](https://github.com/sobolevn/misspell-fixer-action))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Translation](https://github.com/fabasoad/translation-action)) - Translate text from any language to any language.

### Fun

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Add equivalent of a like button in your README](https://github.com/ariary/Readme-Like-Button)) - Visualize community approval on some part of your readme (can be used as a poll).

### Cheat Sheet

- 🌎 [GitHub Actions Branding Cheat Sheet](haya14busa.github.io/github-action-brandings/)

## Tutorials

- 🌎 [Continuous deployment of Next.js app with Up](medium.com/@romanenko/simple-ci-for-next-js-projects-with-apex-up-github-actions-6f0b1b9a5400)
- 🌎 [Converting Docker-based Actions to JavaScript/TypeScript](httgp.com/converting-github-actions-from-docker-to-javascript/)
- 🌎 [GitHub Actions CI for Swift/iOS Projects](medium.com/rosberryapps/github-actions-ci-for-swift-projects-c129baceed1a)
- 🌎 [Working with GitHub Actions](jeffrafter.com/working-with-github-actions)
- 🌎 [GitHub Actions for Rails Developers](www.youtube.com/watch?v=gGUXydw22zw)
- 🌎 [GitHub Actions Advent Calendar](www.edwardthomson.com/blog/github_actions_advent_calendar.html)
- 🌎 [Zero Downtime Laravel Deployments with GitHub Actions](atymic.dev/blog/github-actions-laravel-ci-cd/)
- 🌎 [Building Custom GitHub Actions Pluralsight Course](www.pluralsight.com/courses/building-custom-github-actions/)
- 🌎 [Continuously Deploying Django to DigitalOcean with Docker and GitHub Actions](testdriven.io/blog/deploying-django-to-digitalocean-with-docker-and-github-actions/)
- 🌎 [Deploying Self-Hosted GitHub Actions Runners with Docker](testdriven.io/blog/github-actions-docker/) - Deploy self-hosted GitHub Actions runners with Docker and Docker Swarm to DigitalOcean.
- 🌎 [Setup Auto-scaled self-hosted GitHub Actions Runners on AWS Spot-instances](040code.github.io/2020/05/25/scaling-selfhosted-action-runners)
- 🌎 [Getting the Gist of GitHub Actions](gist.github.com/br3ndonland/f9c753eb27381f97336aa21b8d932be6)

> Please don't hesitate to make a PR if you have more resources to share. Check out [contributing.md](contributing.md) for more information.

## Source
<b><code>&nbsp;26313⭐</code></b> <b><code>&nbsp;&nbsp;1537🍴</code></b> [sdras/awesome-actions](https://github.com/sdras/awesome-actions))