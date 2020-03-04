# slakio

Open-source web live chat with slack integration


Installation
============


With npm
--------

If you have npm-based project (e.g. SPA like React/Vue) you can run:

```bash
npm install slakio --save
```

Then in your code

```js
import slakio from 'slakio'
...
slakio({
  slakio_server_domain: 'https://slakio.mycomp.com'
})
```

By including script
-------------------

You can download latest `slakio-*.min.js` here https://github.com/devforth/slakio/releases/ 


Then insert `<script>` e.g to `<head>` section of your HTML file:
```html
<script src="/xxx/slakio-x.x.x.min.js"></script>
```
Then in your code (`body` section, `onclick` handler, etc):
```html
<script>
  slakio(<options>)
</script>
```