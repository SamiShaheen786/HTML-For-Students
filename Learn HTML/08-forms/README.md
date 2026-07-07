# 08 - Forms

## Files
| File | What it covers |
|------|---------------|
| `basic-form.html` | form, action, method, label, input, button |
| `input-types.html` | All input types: text, email, password, number, radio, checkbox, file, date, color, range |
| `form-elements.html` | textarea, select, option, optgroup, datalist, fieldset, legend |
| `form-validation.html` | required, minlength, maxlength, min, max, pattern |

## Syntax
```html
<form action="/submit" method="POST">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" />
  <button type="submit">Submit</button>
</form>
```

## Key Points
- `action` — where form data is sent
- `method` — GET (data in URL) or POST (data hidden)
- `label for` must match `input id`
- `name` attribute is what gets sent to the server

## Next →
09 - Inline & Block Elements
