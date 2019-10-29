# Digital Inclusion – Contribution Guidelines

We think that it is great that you want to contribute. Never made an open source contribution before? Wondering how contributions work in the in our project? Here are a few tips to help you get started!

## Issues

There should be an Issue for all the work done on this project. If you want to contribute, please find an appropriate Issue first. You can find them in the Issues tab or on the Project Board.

## Project Board

[The project board on Github](https://github.com/digital-inclusion/core/projects/1) is where we manage the workflow, in Kanban methodology. Make sure you only have one Issue In Progress! :)

## Step by step instructions

1. Find an **Issue** that you are interested in addressing or a feature that you would like to add. Note the Issue number, e.g. #1.
2. Fork the repository associated with the issue to your local GitHub organization. This means that you will have a copy of the repository under `your-GitHub-username/repository-name`.
3. Clone the repository to your local machine using `git clone https://github.com/github-username/repository-name.git`.
4. Create a new branch for your fix, indexed by the Issue number using `git checkout -b 1-splash-page`.
5. Make the appropriate changes for the issue you are trying to address or the feature that you want to add.
6. Use `git add insert-paths-of-changed-files-here` to add the file contents of the changed files to the "snapshot" git uses to manage the state of the project, also known as the index.
7. Use `git commit -m "Insert a message of the changes made here and issue number e.g. #1"` to store the contents of the index with a descriptive message.
8. Push the changes to the remote repository using `git push origin branch-name-here`.
9. Using Github in the browser, submit a pull request to the upstream repository.
10. Title the pull request with the short description of the changes made and the issue or bug number associated with your change. For example, you can title an issue like so "Added more log outputting to resolve #4352".
11. In the description of the pull request, add the line ```Resolves: #1``` where `#1` is the Issue number. Below that, explain the changes that you made, any issues you think exist with the pull request you made, and any questions you have for the maintainer. It's OK if your pull request is not perfect (no pull request is), the reviewer will be able to help you fix any problems and improve it!
12. Wait for the pull request to be reviewed by a maintainer.
13. Make changes to the pull request if the reviewing maintainer recommends them.
14. Celebrate your success after your pull request is merged!

## Where can I go for help?

If you need help, you can ask questions on our Slack `digitalinclusion-hq.slack.com`
