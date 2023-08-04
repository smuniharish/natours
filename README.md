| Parameter | Type     | Description | Default| **Required* |
| -------- | ------- | -------| ------- | ----- |
| `itemsList` | `items[]` | the list of objects having label value pairs | None | True |
| `isRequired` | `boolean` | to make it whether it will be required or not | None | True |
| `defaultValue` | `item` | object of label value pair | None | False |
| `disabled` | `boolean` | whether the input is disabled or not | false | False |
| `multiple` | `boolean` | if its true, allows to select multiple values | false | False |
| `min` | `number` | if multiple is true,we can restrict the minimum items to pick | 0 | False |
| `max` | `number` | if multiple is true,we can restrict the maximum items to pick | 100 | False |
| `minError` | `string` | customizing the error on not satisfies the Minimum picks | 'Min Selection Expected !!!' | False |
| `maxError` | `string` | customizing the error on not satisfies the Maximum picks | 'Max Selections reached !!!' | False |
| `validError` | `string` | customizing the error on not Valid | 'Given value is not valid !!!' | False |
| `onChangeCallBack` | `function` | it will triggers when the value changes | None | False |
| `onSelectItemCallBack` | `funtion` | function to call on select item | None | False |
| `onPressItemCallBack` | `function` | function to callback when the picker will be pressed | #a8a8a8 | False |
| `onOpenCallBack` | `funtion` | function to call when the picker is opened | None | False |
| `onCloseCallBack` | `function` | function to callback when the picker is closed | #a8a8a8 | False |
