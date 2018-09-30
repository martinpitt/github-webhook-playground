Summary
-------

This throws together some code from [Cockpit](https://github.com/cockpit-project/cockpit)
and [Cockpituous](https://github.com/cockpit-project/cockpituous) to show how
to conveniently interact with the GitHub API from Python, and how to set up a
web hook.

Credentials
-----------

 * For interacting with GitHub, create a [Personal Access Token](https://github.com/settings/tokens) with the appropriate permissions; for editing labels etc. you at least need `public_repo`.  Put that token into `~/.config/github-token`.
