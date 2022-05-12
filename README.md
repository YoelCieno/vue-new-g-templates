# New Vue File

在 VS Code 中快速创建 vue 组件。

### Install

- Quickly VS Code create `newVueComponent`
- Plugin newVueComponent source in VS Code is (https://marketplace.visualstudio.com/items?itemName=wtto00.newVueComponent)

### Use

Right-click the directory in the resource manager, select Create Vue Component , enter the component name, and you can quickly create a Vue component

### Settings

| key                            | type    | values               | description                                   |
| ------------------------------ | ------- | -------------------- | --------------------------------------------- |
| newVueComponent.vue3           | boolean | true/false           | To use Vue3 version                            |
| newVueComponent.ts             | boolean | true/false           | To use typescripttypescript                           |
| newVueComponent.scriptSeparate | boolean | true/false           | script files are separated                      |
| newVueComponent.scrpitSetup    | boolean | true/false           | to use script setup mode (invalid when vue3=false) |
| newVueComponent.style          | string  | css/scss/less/stylus | select css preprocessing language                           |
| newVueComponent.styleSeparate  | boolean | true/false           | style files are separated separately                        |
| newVueComponent.styleScoped    | boolean | true/false           | the style is component isolated                        |
| newVueComponent.folder         | boolean | true/false           | to create a directory with the same name                              |

### Default Setting

```json
{
  "newVueComponent.vue3": true,
  "newVueComponent.ts": false,
  "newVueComponent.scriptSeparate": false,
  "newVueComponent.scrpitSetup": false,
  "newVueComponent.style": "css",
  "newVueComponent.styleSeparate": false,
  "newVueComponent.styleScoped": true,
  "newVueComponent.folder": true
}
```
