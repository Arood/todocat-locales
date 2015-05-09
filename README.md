# TodoCat Locales

This repository contains the files that are used by TodoCat to display different languages. **At this moment the only way to contribute is by editing this repository and doing a pull request.** We are currently looking into which tool to use to make this process easier.

Translations are done with a slightly modified version of [i18n-node](https://github.com/mashpie/i18n-node/pull/157). The master-branch of this repository contains the same files as TodoCat is currently using.

## Instructions for non-GIT users

These instructions are for users who want to contribute today, but may not be too familiar with GitHub. Each step requires that you have an account that you are logged into on GitHub.

### About JSON

The language files are stored in a format called JSON. To quote [Wikipedia](http://en.wikipedia.org/wiki/JSON):

> JSON is an open standard format that uses human-readable text to transmit data objects consisting of attribute–value pairs. It is used primarily to transmit data between a server and web application, as an alternative to XML.

### Modifying an existing language

First open the language-file you would like to edit by clicking its filename. Then, click on the pencil-icon to the right ("Edit this file").

You will now see an editor, where each line is a string used by TodoCat. The first part in orange (called the "key") is the original english translation. On the right side of the colon you see the translation, or **null** if it hasn't been translated yet.

On the bottom of the page you'll see a box called "Commit your changes". Enter a fitting title for your change and optionally add a description (if you modify an existing line, please tell us why here). When you're done, click on the green "Commit changes" button.

### Adding a new language

To create a new language, we should begin with copying the original english translation to our clipboard. Do this by opening **en.json**, click the "Raw"-button, select all the text and copy.

Then return to the start page of this repository and click on the + sign next to the repository name, right above the file list box. Paste the text from **en.json** into the text editor and apply your translations.

The name of the file needs to be the [ISO 639-1](http://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) code of your language, with the file extension `.json`.

When you're done, scroll down to enter some information about your translation, and then click the "Commit new file" button.