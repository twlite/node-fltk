# fltk

Native fltk bindings for Node.

# Example

```js
const { Application } = require("fltk");

const app = new Application();
app.setBackgroundColor("red");

const window = app.createWindow({
    width: 512,
    height: 512,
    name: "Node FLTK"
});

window.show();

app.run();
```

##### Output

![preview](https://raw.githubusercontent.com/archaeopteryx1/node-fltk/main/assets/example.png)