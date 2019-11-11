# amplify-form-section



<!-- Auto Generated Below -->


## Properties

| Property                 | Attribute                  | Description                                                           | Type                                | Default                                                                                                                           |
| ------------------------ | -------------------------- | --------------------------------------------------------------------- | ----------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| `handleSubmit`           | --                         | (Required) Function called upon submission of form                    | `(inputEvent: Event) => void`       | `undefined`                                                                                                                       |
| `headerText`             | `header-text`              | Used for form section header                                          | `string`                            | `'Amplify'`                                                                                                                       |
| `overrideStyle`          | `override-style`           | (Optional) Overrides default styling                                  | `boolean`                           | `false`                                                                                                                           |
| `primaryFooterContent`   | `primary-footer-content`   |                                                                       | `FunctionalComponent<{}> \| string` | `(     <amplify-button type="submit" overrideStyle={this.overrideStyle}>       {this.submitButtonText}     </amplify-button>   )` |
| `secondaryFooterContent` | `secondary-footer-content` |                                                                       | `FunctionalComponent<{}> \| string` | `null`                                                                                                                            |
| `submitButtonText`       | `submit-button-text`       | (Optional) Used as a the default value within the default footer slot | `string`                            | `'Submit'`                                                                                                                        |


## Dependencies

### Used by

 - [amplify-confirm-sign-in](../amplify-confirm-sign-in)
 - [amplify-confirm-sign-up](../amplify-confirm-sign-up)
 - [amplify-forgot-password](../amplify-forgot-password)
 - [amplify-sign-in](../amplify-sign-in)
 - [amplify-sign-up](../amplify-sign-up)

### Depends on

- [amplify-button](../amplify-button)
- [amplify-section](../amplify-section)

### Graph
```mermaid
graph TD;
  amplify-form-section --> amplify-button
  amplify-form-section --> amplify-section
  amplify-confirm-sign-in --> amplify-form-section
  amplify-confirm-sign-up --> amplify-form-section
  amplify-forgot-password --> amplify-form-section
  amplify-sign-in --> amplify-form-section
  amplify-sign-up --> amplify-form-section
  style amplify-form-section fill:#f9f,stroke:#333,stroke-width:4px
```

----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*