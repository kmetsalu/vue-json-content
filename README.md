# vue-json-content

A Vue component that shows a pretty printed json. 

This isn't particularly useful, it's used as a demo for how to publish Vue components to NPM!

## Installation

```bash
npm i --save-dev vue-json-content
```

### Browser

Include the script file, then install the component with `Vue.use(VueJsonContent);` e.g.:

```html
<script type="text/javascript" src="node_modules/vuejs/dist/vue.min.js"></script>
<script type="text/javascript" src="node_modules/vue-json-content/dist/vue-json-content.min.js"></script>
<script type="text/javascript">
  Vue.use(VueJsonContent);
</script>
```

### Module

```js
import VueJsonContent from 'vue-json-content';
```

## Usage

Once installed, it can be used in a template as simply as:

```html
<div v-json-content="json"></div>
```
