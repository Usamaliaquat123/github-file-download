# 🚀 Chrome extension to download each github file

Automatically adds repository size to GitHub's repository summary.

## Screenshot

XXX

## Private Repository

To enable viewing size of private repositories;

1. Install extension from chrome webstore, if you haven't.
2. Go to https://github.com/settings/tokens to generate your personal access token.
3. Click on the Github Repo Size extension (this extension)'s icon aside the address bar.
4. Paste your access token there in the prompt box.

### Temporarily override then token

You can set `x-github-token` in `localStorage` to your access token, and the extension will use this value even if you've previously set token.

    localStorage.setItem('x-github-token', <YOUR-PERSONAL-ACCESS-TOKEN>)

and then remove it to use previously set token;

    localStorage.removeItem('x-github-token')

## Development

1. Clone this repo
2. Go to chrome extensions [chrome://extensions](chrome://extensions)
3. Enable developer mode
4. Click on load unpacked extension and select this cloned repo

## License

MIT
