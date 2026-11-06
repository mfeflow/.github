# Contributor ladder

How people move from a first pull request to maintainer in the mfeflow org. Each step maps to a GitHub repository role.

| Step        | GitHub role | What you can do                                                                                                              |
| ----------- | ----------- | ---------------------------------------------------------------------------------------------------------------------------- |
| Contributor | none        | Open issues, discussions and pull requests.                                                                                  |
| Triager     | Triage      | Label and close issues, close duplicates, request reviews. No pushes, and your approval does not count as a required review. |
| Committer   | Write       | Push branches, review and approve pull requests. `main` still takes changes only through a pull request with green CI.       |
| Maintainer  | Maintain    | Share project decisions, manage release notes and settings that do not need admin.                                           |

## How to move up

- **Triager:** a few helpful pull requests, reviews or issue answers.
- **Committer:** about five merged pull requests or reviews over at least four weeks, with good calls on tests and scope.
- **Maintainer:** a committer who has helped steadily for months and wants to share the work.

Ask in an issue or a discussion, or a maintainer nominates you. The current maintainers decide together.

## What every step keeps

- Releases are published only by CI, and the release job needs a maintainer's approval. No step gives anyone an npm token.
- Commits on `main` must be signed. Committers and maintainers need two-factor authentication on their GitHub account.
- After six months without activity, access goes back one step. You can come back at any time.

## Who is where

| Person                                                             | Step       |
| ------------------------------------------------------------------ | ---------- |
| Sanjeev Sharma ([speedsharmaai](https://github.com/speedsharmaai)) | Maintainer |
| Giorgio Boa ([gioboa](https://github.com/gioboa))                  | Triager    |
