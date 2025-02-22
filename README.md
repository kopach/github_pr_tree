# Better Pull Requests for GitHub

---

> Since maintainer of [original repo](https://github.com/berzniz/github_pr_tree) do not merge PR for quite a while now, I decided to merge most of them to this Fork repo. Then I buiud the extension locally (with `NODE_ENV=production npm run build-firefox` or `NODE_ENV=production npm run build-chrome` and upload to Browser.

---

Chrome and Firefox browser extension to show a file tree on GitHub's Pull Request pages.

- Browse pull requests with an IDE like file tree
- Private repositories support out of the box
- GitHub Enterprise support
- Dark mode
- Other goodies: track viewed files, resizable tree, expand to full width and more

![GitHub Pull Request](assets/screenshot.png "GitHub Pull Request")

## Who made this?

Tal Bereznitskey. Find me on Twitter as [@ketacode](https://twitter.com/ketacode) and on [LinkedIn](https://www.linkedin.com/in/talbereznitskey).

This is an open-source community project and is not endorsed or affiliated with GitHub.

Special thanks goes to [<img src="https://www.toriihq.com/favicon.ico" valign="middle" /> Torii](https://www.toriihq.com) for providing the time and resources to work on this extension.

## Install

Install from the Chrome web store: [Better Pull Requests for GitHub for Chrome](https://chrome.google.com/webstore/detail/nfhdjopbhlggibjlimhdbogflgmbiahc)

Install from the Firefox Browser Add Ons: [Better Pull Requests for GitHub for Firefox](https://addons.mozilla.org/en-US/firefox/addon/better-pull-request-for-github/)

## GitHub Enterprise support

To enable the extension on your organization's domain:

1. Right click on the extension icon
2. Choose "Enable Better Pull Request for GitHub on this domain"
3. Reload the page

![Enterprise Support](assets/enterprise.png "Enterprise Support")

## Development

1. Install:
    ```bash
    $ yarn install
    ```

2. Run
    ```bash
    $ yarn start
    ```

3. Load the unpackaged `build/chrome/development` folder on Chrome's "Manage Extensions" tab   

4. Make changes

5. Click "Reload" on Chrome's "Manage Extensions" tab

## Testing

Run tests using jest:
```bash
$ yarn test
```

## History

Find the change log here: [Changelog](https://github.com/berzniz/github_pr_tree/releases)

