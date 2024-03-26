```js
function Developer(name) {
  this.name = name;
}
Developer.prototype.greet = function () {
  console.log("Hi, I'm", this.name);
};

const davi = new Developer('Davi Alexandre');
davi.greet();
```
