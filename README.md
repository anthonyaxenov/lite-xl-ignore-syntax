# env syntax support plugin for lite-xl

[Lite-XL](https://lite-xl.com/) is lightweight, fast and customizable open-source code editor.

This plugin adds extra syntax highlighting for such fyletypes:
* `.gitignore`
* `.dockerignore` 
* and any other `.blablablaignore` which has identical simple syntax rules.

Supported highlighting:
* comments;
* excluded (ignored) patterns;
* included (not-ignored) patterns.

You can use any of [these files](https://github.com/github/gitignore) to check how plugin works (just rename it to `.gitignore` or `.dockerignore`).

## How to install

To install a plugin:

* Drop `language_env.lua` file in:
    * Linux: `~/.config/lite-xl/plugins/`
    * MacOS: `~/.config/lite-xl/plugins/`
    * Windows: `C:\Users\(username)\.config\lite-xl\plugins\`
* If lite-xl is already opened then `Ctrl+Shift+P => rst => <Enter>` to reboot editor's core and load plugin immidiately.

## License

[The MIT License](LICENSE)
