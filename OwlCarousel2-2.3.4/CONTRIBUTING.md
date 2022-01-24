Contributing
The issue tracker is the preferred channel for bug reports, feature requests, and submitting pull requests.

Please do not use the issue tracker for personal support requests. Stack Overflow (owl-carousel) is a better place to get help.

Bug reports
A bug is a demonstrable, reproducible problem that is caused by the code in the repository. Good bug reports are extremely helpful, so thanks!

Guidelines for bug reports:

Use the GitHub issue search — check if the issue has already been reported.

Check if the issue has been fixed — try to reproduce it using the latest develop branch in the repository.

Isolate the problem - you NEED to provide a live example — ideally also create a reduced test case. This CodePen, JSFiddle and JS Bin are helpful templates you can fork or clone.

Example:

Short and descriptive example bug report title

A summary of the issue and the browser/OS environment in which it occurs. If suitable, include the steps required to reproduce the bug.

This is the first step
This is the second step
Further steps, etc.
<url> - a link to the reduced test case

Any other information you want to share that is relevant to the issue being reported. This might include the lines of code that you have identified as causing the bug, and potential solutions (and your opinions on their merits).

Feature requests
Feature requests are welcome, but please take a moment to find out whether your idea fits with the scope and aims of the project. It's up to you to make a strong case to convince the project's developers of the merits of this feature.

To get approval for your feature request, please create an issue on the issue tracker with as much detail and context as possible. We'll take a look at it and then [hopefully] apply the "approved for development" tag so someone can get to work on it!

Pull requests
Good pull requests are a fantastic help. They should remain focused in scope and avoid containing unrelated commits.

Adhering to the following process is the best way to get your work included in the project:

Fork the project, clone your fork, and configure the remotes:
```bash
git clone https://github.com/<your-username>/OwlCarousel2.git
cd OwlCarousel2
git remote add upstream https://github.com/OwlCarousel2/OwlCarousel2.git
```
If you cloned a while ago, get the latest changes from upstream:
```bash
git checkout develop
git pull [--rebase] upstream develop
```
Create a new topic branch (off the main project develop branch) to contain your feature, change, or fix:
```bash
git checkout -b <topic-branch-name>
```
Build the distribution before committing to ensure your changes follow the coding standards and all build files are up to date.
```bash
grunt dist
```
Commit your changes in logical chunks. Please adhere to these guidelines. Use Git's interactive rebase feature to tidy up your commits before making them public.

Locally merge (or rebase) the upstream development branch into your topic branch:

```bash
git pull [--rebase] upstream develop
```
Push your topic branch up to your fork:
```bash
git push origin <topic-branch-name>
```
Open a Pull Request with a clear title and description against the develop branch.
By submitting a patch, you agree to allow the project owner to license your work under the terms of the MIT License.