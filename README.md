# vue-directive-waves

Use the wave effect in Vue2. Based on [Waves](https://github.com/fians/Waves).

> Vue1.x see the [1.0 Tag](https://github.com/yscoder/vue-directive-waves/tree/1.0).

## Install

```
npm install vue-directive-waves --save
```

## Example

Add directive in the template.

```html
<template>
    <button v-waves></button>
</template>
```

References in the script.

```js
var Vue = require('vue');
var Waves = require('vue-directive-waves');

Vue.use(Waves);
```

## Modifiers

Default modifiers is `v-waves.block`. 

```html
<button v-waves.button></button>
<button v-waves.button.float></button>
<button v-waves.button.light></button>

<span v-waves.circle></span>
<span v-waves.circle.float></span>
<span v-waves.circle.light></span>

<div v-waves.block></div>
<div v-waves.block.float></div>
```

## Config

Same as [Waves](http://fian.my.id/Waves/#api).

```js
Vue.use(Waves, {
    duration: 500,
    delay: 200
});
```


## License

MIT
