# Gitfred Workflow

A GitHub Workflow for Alfred

Uses the [gitfred script] to cache and search GitHub repos.

[gitfred script]: https://github.com/jsteiner/gitfred

## Features

* Caches repos for instant search.
* Fuzzy search for easy searching.
* Stores repo hits and sorts appropriately for even faster searching.

## Install

1. Clone this repo and symlink in in your Alfred workflows directory.
1. Create a `.env` file in this repo with the following structure:

   ```
   GITHUB_OAUTH_TOKEN=your-oauth-token
   ```

1. Create a [GitHub OAuth token] with `repo` scopes and add it to your `.env`.

[GitHub OAuth token]: https://github.com/settings/tokens/new
