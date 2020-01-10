# NODE-WIN-MOUSE-CTRL

Fork from [https://github.com/wshxbqq/node-win-mouse](https://github.com/wshxbqq/node-win-mouse)

build with `node 10.14.0`

## usage

`npm install win-mouse-ctrl --save`

```
const mouseCtrl = require('win-mouse-ctrl');
mouseCtrl.moveTo(200, 200);
mouseCtrl.leftDown();
mouseCtrl.leftUp();
mouseCtrl.rightDown();
mouseCtrl.rightUp();
```