# Dev Environment

### Font FiraCode

https://github.com/tonsky/FiraCode

#### Install the fonts on a Mac

```bash
$ brew tap homebrew/cask-fonts
$ brew cask install font-fira-code
```

#### Install on VS Code

In the menu, go to preferences: `Preferences`, `Settings` or `Cmd`+`,`

select `Font` and
enter "'Fira Code'" in the input box `Font Family`
and check box `Enables/Disables font ligatures` under "Font Ligatures" to enable the special ligatures.

Or simply paste the following in `settings.json`:

```
"editor.fontFamily": "'Fira Code'",
"editor.fontLigatures": true,
```

Alternative: to use Retina weight `"editor.fontFamily": "FiraCode-Retina"`
