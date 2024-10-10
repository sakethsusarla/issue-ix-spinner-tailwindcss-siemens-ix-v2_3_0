### [Issue](https://github.com/siemens/ix/issues/1511) 👈

### Waiting for fix ...

### Expected Behavior

The `ix-spinner` component should render correctly when using Siemens IX v2.

### Actual Behavior

After updating to Siemens IX v2, the `ix-spinner` component does not render anymore. It was working with the previous versions of the dependencies.

### Additional Information

My observation is that if I comment out `@import 'tailwindcss/base';` in the `src/styles.scss`, the `ix-spinner` component renders again. However, if I include this import, it does not render.

### Dependencies Before Update

```
"@siemens/ix-angular": "^1.6.0",
"@siemens/ix-echarts": "^1.6.0",
"@siemens/ix-icons": "^1.0.4",
```