[![Build Status](https://travis-ci.org/advanced-rest-client/anypoint-text-field.svg?branch=stage)](https://travis-ci.org/advanced-rest-client/anypoint-text-field)  

# anypoint-text-field

`<anypoint-text-field>` single line text input styled for the Anypoint platform as a Polymer
powered web component

It may include an optional error message.
```
<anypoint-text-field required error-message="Value is required"></anypoint-text-field>
```

It may include a custom validator(s).
```
<anypoint-text-field validator="my-validator" error-message="Value is required"></anypoint-text-field>
```
See `Anypoint.AnypointValidatableBehavior` for API and examples.

### Styling

See `anypoint-text-container` for styling options.



### Events
| Name | Description | Params |
| --- | --- | --- |
| change | Fired when the input changes due to user interaction. | __none__ |
# anypoint-text-container


The `<anypoint-text-container>` is a container for a `label` and input text styled to match the
Anypoint platform styling.

### Styling

`<anypoint-text-field>` provides the following custom properties and mixins for styling:

Custom property | Description | Default
----------------|-------------|----------
`--anypoint-text-container` | Mixin applied to the input container | `{}`
`--anypoint-text-container-disabled` | Mixin applied to the disabled container | `{}`
`--anypoint-text-container-border` | Mixin applied to the border element on the left and right hand side of the input | ``
`--anypoint-text-container-border-focused` | Mixin applied to the border element on the left and right hand side of the input | ``
`--anypoint-text-container-border-color` | Color of the right and left border of the input | `--anypoint-color-aluminum4`
`--anypoint-text-container-border-focused-color` | Color of the right and left border of the input when the input is focused | `--anypoint-color-steel2`
`--anypoint-text-container-invalid-color,` | Error color | `--anypoint-color-danger`
`--anypoint-text-container-label-color` | Color of the label | `--anypoint-color-aluminum5`
`--anypoint-text-container-label` | Mixin applied to the label | `{}`
`--anypoint-text-container-label-floating` | Mixin applied to the floating label | `{}`
`--anypoint-text-container-label-focus` | Mixin applied to the label when focused | `{}`
`--anypoint-text-container-focus-color` | Color applied to the label and input when focused | `--anypoint-color-aluminum5`
`--anypoint-text-field-prefix` | Mixin applied to any prefix element added to the container | `{}`
`--anypoint-text-field-suffix` | Mixin applied to any suffix element added to the container | `{}`
`--anypoint-text-container-input-color` | Color of the input control | `--anypoint-color-steel5`
`--anypoint-text-container-input` | Mixin applied to the input control | ``

# anypoint-text-textarea

`<anypoint-text-field>` is a mu;lti line text input styled for the Anypoint platform
as a Polymer powered web component

### Example
```
<anypoint-text-textarea></anypoint-text-textarea>
```

### Styling
See `anypoint-text-container` for styling options.



### Events
| Name | Description | Params |
| --- | --- | --- |
| change | Fired when the input changes due to user interaction. | __none__ |
# anypoint-validation-result

The `<anypoint-validation-result>` is a container for an error message or list of validation
rules if the input element uses `validator`s.

### Styling

Custom property | Description | Default
----------------|-------------|----------
`--anypoint-validation-result-container` | Mixin applied to the element | `{}`
`--anypoint-validation-result-border-color` | Border color of the popover | `--anypoint-color-aluminum3`
`--anypoint-validation-result-left-border` | Color of the right border of the popover | `--anypoint-color-steel4`
`--anypoint-text-container-invalid-color` | Color of error messages and borders when corresponding form control is invalid | `--anypoint-color-danger`
`--anypoint-validation-result-message-size` | Font size of the validation message. | `12px`

