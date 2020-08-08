# WebsiteTemplates
These are the templates that our rendering component uses to build pages for the website by combining them with the
translation files.

## Usage

In order to change how one of the pages will look when it is rendered by our
[PageRenderer]((https://github.com/FoldingCommunity/PageRenderer)) component, you need to change the HTML markup in the
files in this repository.

Note that we are currently using a simplified version of [Mustache](http://mustache.github.io/) to insert the translated
strings into the templates. Therefore, all the strings used in the templates should be surrounded by triple curly
braces, which looks like this: `{{{ some headline here }}}`

The strings used there **have to** match the `msgid` values in the translation files. Please use the `en-US` files in
the [Translate](https://github.com/FoldingCommunity/Translate) repository as source of truth.

## Introducing new Strings

At the moment we do not have a well established process yet.

If you see the need to make any changes to the strings shown on the website (modifications to existing strings or
introducing new ones), please align this with the project team first, preferably in `#translate-general` in our Dev
Discord. 