# development-conventions
White Rabbit Dev conventions


We use Waffle.io to manage this repo's issue as a kanban
https://waffle.io/white-rabbit-japan/v-wonderland

### Pull Requests
- Make a branch like `xxx-short-description` where `xxx` is the ticket ID.
  - As soon as you push the branch, waffle puts the ticket into "in progress".
- Create a PR and inside the description of your PR, include `fixes #xxx`.
  - This links the two, both on waffle and on GitHub, and closes the issue if the PR is merged.
- Assign the PR to appropriate persons.

### Code format
- Use prettier with default options.
  - Recommended to use editor i
