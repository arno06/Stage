Stage
============

* Stage
* Container
* Sprite
* Bitmap
* Spritesheet
* FPSMeter
* MouseEvent

Dependencies
-----------
* Class
* Event
* M4

Samples
-----------
```js
var domContainer = document.getElementById('stageParent');
var stage = new Stage(800, 600, domContainer);
var sprite = new Sprite();
sprite.beginFill("rgb(255, 0, 0)");
sprite.drawRectangle(-50, -50, 100, 100);
sprite.endFill();
sprite.x = 400;
sprite.y = 300;
stage.addChild(sprite);
stage.addChild(new FPS());
```

Check [samples folder](https://github.com/arno06/Stage/tree/master/samples) for more