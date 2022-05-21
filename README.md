HTML buttons
---
Collection of buttons with effect. All **CSS** in different **SASS** file, so you can check and modify easily.

* `style.scss`: the main style file
* `_hover.scss`: The hover button stuffs
* `_neon.scss`: The neon button stuffs
* `_variables.scss`: there are the variables
* `_index`: it just collect all the scss files and forward to the main file. 

The variable names are  elf-evident.
Variables for the main document:
* **$body_background**: linear gradient for the background
* **$body_background_01**: linear gradient for the background
* **$back_dark**: dark background for the `<section>` or`<div>`
* **$back_light**: light background for the `<section>` or`<div>`

Hover button variables:
* **$textColor**: color for the text on the button
* **$mainBackground**: the main color of the button
* **$hoverBackground**: the color for the hover effect
* **$hoverOpacity**: the opacity of the hover effect
* **$buttonShadow**: shadow for the button

Neon button variables:
* **$pinkNeon**: the color for the pink button
* **$greenNeon**: the color for the green button
* **$blueNeon**: the color for the blue button
* **$redNeon**: the color for the button
* **$neonFontColor**: the color for the red button
The text on the button is the same as the base color of the button
---
Please do not modify the **CSS** file directly, because the **SCSS** file will overwrite it anyway. But if you do not use the **SCSS** files, you can modify it.