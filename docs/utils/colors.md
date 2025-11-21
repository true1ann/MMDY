# MMDY/Docs/U/colors

## Sources

[scss/u/colors.scss](/scss/u/colors.scss) - SCSS Theme  

## Explanation

<details>

<summary>Setup your color pallete</summary>
Colors, in any webpage are the most important part of an UI engine. You can get your color pallete on the [Official M3 Theme Generator by Google](https://material-foundation.github.io/material-theme-builder/).

1. Open the Website (read above)
2. Tweak the theme to match your idea
3. Press 'Pick your fonts' (button)
4. Press 'Export theme' (button)
5. Press 'Export' (dropdown)
6. Press 'Web (CSS)' (list item)

After exporting as **CSS**, make sure the variable rules are properly injected in the webpage. Normally, youd want to change `.dark`/`.light`/... classes in each file to `:root`, this works best for one-theme projects, otherwise control `md-sys` colors by importing both themes and controlling the class of `body` element.

</details>

---

You can apply colors with these classes:

- `primary` - The default applied color.
- `secondary`
- `tertiary`
- `error`

> [!IMPORTANT]
> MMDY's planned feature is to also allow Custom colors, but its planned and is not implemented yet.
