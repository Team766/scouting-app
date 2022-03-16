# Making a Google Form for this project

You can't use any old form for this, it is reccomended to create a new one that follows this template.

## Text Entry

You can make text entry boxes as you usually would. HTML will use `<input type="text">`

### Text Entry (Long Response)

These should also be made as usual, but the form will use the `<textarea>` element instead of `<input>`

## Checkboxes (Yes/No)

Ex: Do you like to read long README files?<br><br><input type="checkbox"> YES<br><input type="checkbox"> NO<br><br>
Instead of using the boxes, use a text input. On the HTMl document, we would re-word the question and remove the NO box. If the box is selected, the form output will read "false, true", if it is not selected, "FALSE"".<br><br>
<input type="checkbox" checked> I like to read long README files -> false, true<br> <input type="checkbox"> I like to read long README files -> FALSE

## Dropdown Menus

EX: <select><option>SELECT MENU</option><option>SELECT MENU</option></select>
<br><br>
In the google form, use text entry rather than dropdowns. In the html, however, you will make it a dropdown menu that fills the Google Form text.