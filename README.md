# Development Conventions

White Rabbit Dev conventions

We use Waffle.io to manage GitHub issues as kanban boards.

### Pull Requests

- Make a branch like `xxx-short-description` where `xxx` is the ticket ID.
  - As soon as you push the branch, waffle puts the ticket into "in progress".
- Create a PR and inside the description of your PR, include `fixes #xxx`.
  - This links the two, both on waffle and on GitHub, and closes the issue if the PR is merged.
- Assign the PR to appropriate persons.

### Code Style

- Use prettier with the configuration provided in [prettier directory](https://github.com/white-rabbit-japan/development-conventions/blob/master/prettier/). The rest of the options are taken from Prettier's default config.
  - Recommended to use in VSCode editor after saving file changes.
