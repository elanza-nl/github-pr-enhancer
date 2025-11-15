# GitHub Show Reviewer

A Chrome extension that displays reviewers directly in the GitHub Pull Request list view.

[Chrome Web Store / github-show-reviewer](https://chromewebstore.google.com/detail/github-show-reviewer/oiooodcehfplbgnamghfcnklebcdohhd?authuser=0&hl=ja)

![Reviwer List](docs/show_reviwer_list.png)

## Features

- Display reviewer names
  - Supports team reviewers
  - Shows users who have already reviewed
  - Displays "None" when no reviewers are assigned
- Click on a reviewer/team reviewer to filter PRs by that assignee

![Show Reviewer](docs/github_show_reviewer.gif)

## Installation

**Chrome Web Store:**  
[Chrome Web Store / github-show-reviewer](https://chromewebstore.google.com/detail/github-show-reviewer/oiooodcehfplbgnamghfcnklebcdohhd?authuser=0&hl=ja)

**For Developers:**

1. Clone this repository
2. Open Chrome and navigate to `chrome://extensions`
3. Enable "Developer mode" in the top right corner
4. Click "Load unpacked" and select the extension directory

## Configuration

For private repositories or to increase API rate limits, you need to configure your GitHub Personal Access Token.

1. Open Chrome and navigate to `chrome://extensions`
2. Find "GitHub Show Reviewer" and click "Details"
3. Click "Extension options"
4. The GitHub Show Reviewer Settings page will open as shown below

![Settings Page](docs/github_access_token_setting.png)

5. Click "Create a token here" link
6. GitHub's "New personal access token (classic)" page will open
7. Check the `repo` scope (required for private repositories)
8. Generate the token and copy it
9. Paste the token in the input field and click "Save"
