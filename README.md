# FOSS MEC — Git Escape Contributions

Welcome to the first contributions repository for the **FOSS MEC Git & Linux
Escape** competition. The repository is private while the event is being set up.

## Contributors

Thank you to everyone who helps build the FOSS MEC community! Contributions
are recorded in the `contributors/` directory. Once the event is public,
GitHub's [contributors graph](https://github.com/FossMec/first-contributions/graphs/contributors)
will also list contributors whose changes have been merged.

## How to complete the challenge

1. Fork this repository to your own GitHub account.
2. Create a branch, for example `challenge/<your-claim>`.
3. Add a file named exactly:

   ```text
   contributors/<your-claim>.md
   ```

   Your claim looks like `mec-7q2k9` and is shown in the competition panel.

4. Put this content in the file (replacing the claim with yours):

   ```markdown
   # FOSS MEC Contribution

   Challenge: mec-7q2k9
   Status: completed
   ```

5. Commit, push the branch to your fork, and open a pull request against this
   repository's default branch.
6. Wait for the **Validate Contribution** workflow to comment your personal
   flag on the pull request.
7. Return to the competition terminal and run `foss submit <flag>`.

## Rules

- Change exactly one file: `contributors/<claim>.md`.
- Do not modify workflows, source files, or other contributors' files.
- The claim must belong to your competition session.
- One claim can only be used by one pull request.
- The workflow never runs code from your pull request. It reads PR metadata
  through the GitHub API and asks the competition server to verify it.

## Privacy

The competition only stores your GitHub numeric user ID and login to bind the
pull request to your session. No email address is requested or stored.
