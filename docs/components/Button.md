# MMDY/Docs/C/Button

> [!IMPORTANT]
> This covers material FOR RAW version of MMDY (No BEs), therefore you should check up with your BE's documentation on usage, but knowing this is usefull too

## Sources

[scss/c/Button.scss](/scss/c/Button.scss) - SCSS Theme  
[M3 Source](https://m3.material.io/components/buttons) - Official documentation  
[See Demo](https://ann.is-a.dev/MMDY/tests/c/Button.html) - See real-world usages  

## Overview

Base class: `button`  
Special classes: `.disabled`, `.toggle`  
Theme classes: `.elevated`, `.text`, `.outlined` (+`.color`)  
Accepted elements: `<a>`, `<button>`

## Usage

### `.disabled`

Disables the button
> [!important]
> does not actually disable the button, it just tints the button is disabled, use `disabled` (`<button>`s), `href="#"` (`<a>`s) or any other way to really disable the button. This class can also be omitted when `disabled` tag is present (`<button>`-specific).

### `.toggle`

Looks for `mmdy-state="on"` or `mmdy-state="off"` and applies according styles

### `.elevated`

Changes the style to elevated, applies 1st level of elevation on `:hover` and 2nd on `:active`

### `.text`

Removes button background

### `.outlined`

Is basically a `.text` button with an outline. Use `.color` to change the outline color to the accent color
