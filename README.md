# keep2md

It is a script to copy Google Keep notes into markdown files.

## Features

* Generate multiple files;
* Rename duplicate files.

## Important

* It requires Google Service account;
* Don't forget to configure `keep2md.config.js`;
* Unfortunately, it doesn't support empty titles.

## Installation

```
git clone https://github.com/luisfloat/keep2md.git
cd cv/
npm install
```

## How to use?

1. Selected all Google Keep notes and click "Copy to Google Docs";
2. Open the generated document and copy the document ID in the URL into the `.env` (`DOC_ID=<id>`);
3. Add your Google Service account as the collaborator to the document;
4. Run: `npm run start`

## Author

<a href="https://twitter.com/luisfloat"><img src="https://img.shields.io/badge/-Twitter-333333?style=flat-square&amp;logo=twitter" alt="Twitter"/></a> <a href="https://github.com/luisfloat"><img src="https://img.shields.io/badge/-GitHub-333333?style=flat-square&amp;logo=github" alt="GitHub"/></a> <a href="https://instagram.com/luisfloat"><img src="https://img.shields.io/badge/-Instagram-333333?style=flat-square&amp;logo=instagram" alt="Instagram"/></a> <a href="mailto:contact@luisfloat.com"><img src="https://img.shields.io/badge/-Gmail-333333?style=flat-square&amp;logo=gmail" alt="Gmail"/></a>