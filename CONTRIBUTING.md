## Contributing

We ♥ contributors! By participating in this project, you agree to abide by the Ruby for Good [code of conduct].

**First:** if you're unsure or afraid of *anything*, just ask or submit the issue or pull request anyways. You won't be yelled at for giving your best effort. The worst that can happen is that you'll be politely asked to change something. We appreciate any sort of contributions, and don't want a wall of rules to get in the way of that.

[code of conduct]: https://github.com/rubyforgood/code-of-conduct

Here are the basic steps to submit a pull request. Make sure that you're working on an [open issue]–if the relevant issue doesn't exist, open it!

[open issue]: https://github.com/rubyforgood/cep/issues

1. Claim an issue on [our issue tracker][open issue] by assigning it to yourself (core team member) or commenting. If the issue doesn't exist yet, open it.

2. Fork the repo.

3. Run the tests. We only take pull requests with passing tests, and it's great to know that you have a clean slate: `bundle exec rake`

4. Add a test for your change. If you are adding functionality or fixing a  bug, you should add a test!

5. Make the test pass.

6. Push to your fork and submit a pull request. Include the issue number (ex. `Resolves #1`) in the PR description.

7. For any changes, please create a feature branch and open a PR for it when you feel it's ready to merge. Even if there's no real disagreement about a PR, at least one other person on the team needs to look over a PR before merging. The purpose of this review requirement is to ensure shared knowledge of the app and its changes and to take advantage of the benefits of working together changes without any single person being a bottleneck to making progress.

At this point you're waiting on us–we'll try to respond to your PR quickly. We may suggest some changes or improvements or alternatives.

Some things that will increase the chance that your pull request is accepted:

* Use Rails idioms and helpers
* Include tests that fail without your code, and pass with it
* Update the documentation, the surrounding one, examples elsewhere, guides, whatever is affected by your contribution
