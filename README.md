Some custom styles for the Stylus web browser plugin.

[简体中文说明](./README-zh.md)

---

## Usage
First, you'll need the `Stylus` browser plugin, it should be available on main-stream web browsers.
Then find the stylesheet you need (listed below), copy the file content, and open the Stylus plugin, create a new stylesheet, paste the copied content, Stylus will pop up a dialog and tell you to import the stylesheet.

The stylesheet imported can be edited, disabled or deleted.

## Files
### archlinux-manpage-color.css
Replace pure black background and white text with softer slate blue background and darker text.

### dark-sphinx_rtd_theme.css
The theme `sphinx_rtd_theme` does not have a dark mode, however it has been used by many documentation sites, so I wrote one for my personal usage.

It's not perfect, but it works for me.

### github-no-round-avatars.css
Square avatars in user's profile, repositories page, the top right corner and somewhere else. The status circle was also moved.

### mdn-hide-ads.css
This stylus rule is useless if you have AD blocker plugins such as `uBlock Origin` installed. But if you don't have any AD blocker plugins, this one might help.

### restore-stylus-action-button-text.css
Since `Stylus` has changed it's text labels to icons at the top of the editor, this stylesheet is used to make that text back
by using `::after`, see [this comment](https://github.com/openstyles/stylus/issues/2167#issuecomment-4914419195).

### zshell-doc.css
This stylesheet was written for a user-side dark mode for zshell documentation site.
