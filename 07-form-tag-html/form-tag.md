# Form Tag
Forms get some information from user

## Explain
Structure :
- `<label for="clientName">` : Text before your input value
    - Adding attribute for for linking input tag
- `<input type="text">` : Insert your data with only text
    - Adding attribute name et id for linking label tag, that can be useful when you want to manipulate data
- `<textarea>` : Put more text, it's like comment section
- `<input type="date">` : Insert your data with only date
- `<input type="radio" name="Period" value="MORNING" id="morning"/>` : Radio button
    - Attribute name : allows you to regroup all radio buttons at the same group
    - Attribute id : allows you to attach input element at label via for attribute
- `<input type="checkbox" name="Period" value="MORNING" id="morning"/>` : Checkbox button
    - Attribute name : allows you to regroup all checkbox buttons at the same group
    - Attribute id : allows you to attach input element at label via for attribute
- `<select>` : Dropdown list
- `<optgroup label="WEB LANGUAGES">` : Group name of your dropdown list
- `<option value="HTML">HTML</option>` : Item from your group name