# cDIF extension for VS Code

This extension provides support (syntax highlighting and snippets) for the [cDIF](https://github.com/mkacct/cdif/blob/main/spec.md) language. cDIF is a textual data interchange format for representing configurations and other structured data.

This extension is up to date with cDIF version 1.0.1.

## Icons

The provided default [file icon](res/cdif-seti.svg) is intended to fit VS Code's default Seti file icon theme. If you're using [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons) (or a different file icon theme that supports custom icons), you may be interested in the [logo icon](res/cdif-icon.svg).

If you're using the [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme), I recommend simply using the following custom icon clone. Add the following object to the `material-icon-theme.languages.customClones` array in your VS Code settings:

```json
{
    "name": "cdif",
    "ids": ["cdif"],
    "base": "json",
    "color": "#ff4081"
}
```
