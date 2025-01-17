# This repo is now Archived under Pulsar-Edit, as it is now bundled into the core editor [PR#374](https://github.com/pulsar-edit/pulsar/pull/374)

# Markdown Preview package

Show the rendered HTML markdown to the right of the current editor using <kbd>ctrl-shift-m</kbd>.

It is currently enabled for `.markdown`, `.md`, `.mdown`, `.mkd`, `.mkdown`, `.ron`, and `.txt` files.

![markdown-preview](https://cloud.githubusercontent.com/assets/378023/10013086/24cad23e-6149-11e5-90e6-663009210218.png)

## Customize

By default Markdown Preview uses the colors of the active syntax theme. Enable `Use GitHub.com style` in the __package settings__ to make it look closer to how markdown files get rendered on github.com.

![markdown-preview GitHub style](https://cloud.githubusercontent.com/assets/378023/10013087/24ccc7ec-6149-11e5-97ea-53a842a715ea.png)

To customize even further, the styling can be overridden in your `styles.less` file. For example:

```css
.markdown-preview.markdown-preview {
  background-color: #444;
}
```
