## Contribution Guide

- Fork this repository and download the source code using the `git clone` command
- run npm install in the repository to download all the dependencies
- Create your branch and make changes in that branch (Branch name: `dev-<GitHub Username>`)
- Keep your branch up to date
- Make sure the service worker is unregistered in index.js (In development phase)
- Verify your changes thoroughly on the local machine
- Send a pull request with a message describing all the changes made
- Use Material-UI consistently in case you modify/add JSX code (For example use Typography component instead of tags like `<p>`, `<h1>`, `<h2>`)
- Maintain the existing folder structure
- Before making a pull request to the master branch, install dev-dependencies and run eslint scripts (`npm run eslint` or `npm run eslint-fix`) and fix the errors if you get any
- If your pull request fixes an issue, link the issue as show in [docs](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue)

### Commit Message

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit the first line to 72 characters or less
- Reference issues and pull requests liberally after the first line