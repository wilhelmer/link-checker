# link-checker-2

This extension checks links in `.md`, `.txt`, and `.rst` files for their status and for repository freshness.

This is an updated fork of [link-checker](https://github.com/terakilobyte/link-checker).

## Features

Automatically check links for their response code, and in the case of GitHub repositories, their freshness.

![link-checking](images/link-checking.png)

## Requirements

If you want to use the GitHub functionality, you need a [Github Developer API Key](https://github.com/settings/tokens).

Once you have an API key with full **repos** permissions, define an environmental variable called `LINK_CHECKER_TOKEN`.

For example, if you use `zsh`:

```sh
echo "LINK_CHECKER_TOKEN=<API Key>" >> ~/.zshrc
```

## Extension Settings

## Known Issues

## Release Notes

### 1.0.3

Fixed issue with HTML tags immediately following a Markdown hyperlink.

### 1.0.2 

Added icon.

### 1.0.1

Updated link detection. Only links that start with http(s):// will be checked.

### 1.0.0

Initial release of Link Checker.

**Enjoy!**
