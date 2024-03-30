# markdown

This repository is a collection of markdown snippets that can be used to generate README files for projects.
All of these snippets are currently used accros my GitHub projects, and I decided to centralize them in a single repository to make it easier to maintain and update them.
This is possible thanks to the [automd](https://automd.unjs.io) tool that can fetch markdown snippets from other repositories and update them automatically running `bun run automd`.

## Usage

<!-- automd:fetch url="gh:hugorcd/markdown/main/src/local_development.md" -->

### Local development

- Clone this repository
- Install latest LTS version of [Node.js](https://nodejs.org/en/)
- Enable [Corepack](https://github.com/nodejs/corepack) using `corepack enable`
- Install dependencies using `bun install`

<!-- /automd -->

<!-- automd:fetch url="gh:hugorcd/markdown/main/src/contributions.md" -->

## Contributing
To start contributing, you can follow these steps:

1. First raise an issue to discuss the changes you would like to make.
2. Fork the repository.
3. Create a branch using conventional commits and the issue number as the branch name. For example, `feat/123` or `fix/456`.
4. Make changes following the local development steps.
5. Commit your changes following the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification.
6. If your changes affect the code, run tests using `bun run test`.
7. Create a pull request following the [Pull Request Template](https://github.com/HugoRCD/markdown/blob/main/src/pull_request_template.md).
   - To be merged, the pull request must pass the tests/workflow and have at least one approval.
   - If your changes affect the documentation, make sure to update it.
   - If your changes affect the code, make sure to update the tests.
8. Wait for the maintainers to review your pull request.
9. Once approved, the pull request will be merged in the next release !

<!-- /automd -->

## License

<!-- automd:contributors license=Apache author=HugoRCD-->

Published under the [APACHE](https://github.com/HugoRCD/markdown/blob/main/LICENSE) license.
Made by [@HugoRCD](https://github.com/HugoRCD) and [community](https://github.com/HugoRCD/markdown/graphs/contributors) 💛
<br><br>
<a href="https://github.com/HugoRCD/markdown/graphs/contributors">
<img src="https://contrib.rocks/image?repo=HugoRCD/markdown" />
</a>

<!-- /automd -->

<!-- automd:with-automd lastUpdate -->

---

_🤖 auto updated with [automd](https://automd.unjs.io) (last updated: Sat Mar 30 2024)_

<!-- /automd -->
