bookmarklets
============

Collection of bookmarklets.

- [Usage](#usage)
- [Development](#development)

## Usage

You can import the bookmarks in [bookmarklets.html] into any browser you choose. This will add all the bookmarklets at once.

## Development

The source code of each bookmarklet is stored in the `src`.

To create a new bookmarklet:

- Make sure you initialized the repo: `nvm install && nvm use && pnpm install`
- Copy `_template.bookmarklet.js` to `123-name.bookmarklet.js`, with the number and name of your choice. (The number is used to order bookmarklets in the `bookmarklets.html` file.)
- Write your code.
- Run `pnpm start`.

The new bookmarklet should be found in `bookmarklets.html`.
