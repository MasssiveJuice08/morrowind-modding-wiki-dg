---
{"dg-publish":true,"permalink":"/mmw-design-and-planning/custom-formatting-features/","tags":["MMW-Development"]}
---

Custom formatting features implemented for use in the Morrowind Modding Wiki

# Formatting
## 'Image Wrap'
![Patches_ESP-Replacer_1_Conflict.png|+side](/img/user/Assets/Guides/Patches/Tutorial%20-%20Create%20an%20ESP%20Replacer%20Patch/Patches_ESP-Replacer_1_Conflict.png)
You can set an embedded image in a page to be on either the left or right side of a page, with text wrapping around it.

To orient it to the left, use either:
- `![[IMAGE\PATH.png|-side]]` or
- `![[IMAGE\PATH.png|lside]]`

To orient it to the right, use either:
- `![[IMAGE\PATH.png|+side]]` or
- `![[IMAGE\PATH.png|rside]]`

# Callouts
In addition to the default [Obsidian Callouts](https://help.obsidian.md/Editing+and+formatting/Callouts), MMW also adds the following custom Callouts:

## `> [!figure]`
> [!figure]
> ![Patches_ESP-Replacer_1_Conflict.png](/img/user/Assets/Guides/Patches/Tutorial%20-%20Create%20an%20ESP%20Replacer%20Patch/Patches_ESP-Replacer_1_Conflict.png)
> `[!figure]` is intended to be used for captioning images. Long term-goal is to add custom Morrowind-themed icons for custom callouts.