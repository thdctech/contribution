# Contribution Guide
We use a simple form of [gitflow](http://datasift.github.io/gitflow/IntroducingGitFlow.html).
For each change to be made, create a branch out from `staging`.

### Naming
For branch names, use either
- `feat`: for new features.
- `fix`: for bug fixes.
- `experimental`: for proposed features that haven't been accepted into the development timeline.

For `feat` and `fix` branche prefixes, your naming convention should follow `<prefix>/<issue-no>`. When making your commits in said branches, use [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/) as a guide.

#### PR
[Pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) titles have to look like `[brannch-name]: <descriptive title here>`.
And it's description must link to the github issue you're solving and also have a description of:
- the problems you faced and how to recreate them.
- how you solved them.
- possible drawbacks and tradeoffs.
- how to test your solution.

For each task assigned to you, there'd be a supervisor, when you are done with the task, and have created the [PR](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests), assign it to your supervisor and [@thedarkkid](https://github.com/thedarkkid) (if he isn't already your supervisor).

Have Fun!
