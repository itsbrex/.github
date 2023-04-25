# 🌟 Contributing

🎉 Contributions are always welcome, no matter how large or small. Before contributing, please read the [code of conduct](CODE_OF_CONDUCT.md).

Some thoughts to help you contribute to this project:

## 🗣️ Recommended Communication Style

1. 📸 Always leave screenshots for visual changes.
2. 📝 Always leave a detailed description in the pull request. Leave nothing ambiguous for the reviewer.
3. 💻 Always review your code first. Do this by leaving comments in your coding noting questions or interesting things for the reviewer.
4. 🤝 Always communicate. Whether it is in the issue or the pull request, keeping the lines of communication helps everyone around you.

## 🛠️ Setup (forks are preferred)

```sh
$ git clone https://github.com/itsbrex/<repository-name>
$ cd <repository-name>
$ npm install
```

## 🏗️ Building

```sh
$ npm run build
```

## 🧪 Testing

For running the test suite, use the following command. Since the tests run in watch mode by default, some users may encounter errors about too many files being open. In this case, it may be beneficial to [install watchman](https://facebook.github.io/watchman/docs/install.html).

```sh
# the tests will run in watch mode by default
$ npm run test
```

## 🤝 Pull Requests

### We actively welcome your pull requests, however linking your work to an existing issue is preferred.

1. 🍴 Fork the repo and create your branch from `main`.
2. 📛 Name your branch something that is descriptive to the work you are doing, for example, "adds-new-thing" or "fixes-mobile".
3. 🧪 If you've added code that should be tested, add tests.
4. 📖 If you've changed APIs, update the documentation.
5. 📸 If you make visual changes, screenshots are required.
6. ✔️ Ensure the test suite passes.
7. 🚨 Make sure you address any lint warnings.
8. 🚀 If you make the existing code better, please let us know in your PR description.
9. 📝 A PR description and title are required. The title is required to begin with: "feat:" or "fix:"
10. 🔗 Link to an issue in the project. Unsolicited code is welcomed, but an issue is required to announce your intentions. PRs without a linked issue will be marked invalid and closed.

### PR Validation

Examples for valid PR titles:

- fix: Correct typo.
- feat: Add support for Node 12.
- refactor!: Drop support for Node 6.

_Note that since PR titles only have a single line, you have to use the ! syntax for breaking changes._

See [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) for more examples.

### 🏗️ Work in progress

GitHub has support for draft pull requests, which will disable the merge button until the PR is marked as ready for merge.

## 🐛 Issues

If you plan to contribute a change based on an open issue, please assign yourself by commenting on the following word `.take`. Issues that are not assigned are assumed open, and to avoid conflicts, please assign yourself before beginning work on any issues.

If you would like to contribute to the project for the first time, please consider checking the **bug** or **good first issue** labels.
