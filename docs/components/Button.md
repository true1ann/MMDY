# MMDY/Docs/C/Button

> [!IMPORTANT]
> This covers material FOR RAW version of MMDY (No BEs), therefore you should check up with your BE's documentation on usage, but knowing this is usefull too

## Files

Source: [scss/c/Button.scss](/scss/c/Button.scss)
Test: [tests/c/Button.html](/tests/c/Button.html)

## Explanation

`<insert base button style image>`

Class: `button`; Subclasses: `.disabled`, `.elevated`, `.outlined`, `.text`; Modifier classes: `.toggle`

`<insert button styles images>`

`.toggle` Buttons have a special use: they accept `mmdy-state` field to tell if a button is checked or not. Later an `<input type="checkbox">`-based toggle button will be supported
