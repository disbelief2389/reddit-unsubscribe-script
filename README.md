## One-Click Install
Click the link below to install the script directly in Tampermonkey:
[Install Reddit Unsubscribe Script](https://raw.githubusercontent.com/username/repo-name/main/reddit-unsubscribe.user.js)

# Reddit Unsubscribe Script

This is a Tampermonkey script to automatically unsubscribe from all Reddit subreddits in bulk. It’s ideal for users who want to declutter their Reddit subscriptions.

## Features
- Detects all subscribed subreddits.
- Automatically clicks the "Leave" button for each subreddit.
- Includes retries for dynamic content loading.

## Requirements
- [Tampermonkey](https://www.tampermonkey.net/) (a browser extension for running user scripts).

## Installation
1. Install Tampermonkey for your browser:
   - [Chrome](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
   - [Firefox](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)
   - [Edge](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
2. Click the "Raw" button on the script file in this repository.
3. Tampermonkey will prompt you to install the script. Click **Install**.

## Usage
1. Navigate to [Reddit’s subscription page](https://www.reddit.com/subreddits).
2. The script will automatically find and click the "Leave" buttons for all subscribed subreddits.
3. Monitor progress in the browser console (`Ctrl+Shift+I` or `Cmd+Option+I`).

## Troubleshooting
- Ensure you’re logged in to Reddit.
- Refresh the subscription page if no buttons are detected.

## Contributing
Feel free to submit pull requests or open issues for bug fixes or new features.

## License
[MIT](LICENSE)
