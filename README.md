# Baby
```
バビロン上での、操作変数は$ダラーヘッドとする。
多くは、バビロン上でプログラムし、ベイビーにわたす口を作る。
操作変数は最少の方がよい。グローバルで足りる程度の。
各種プレーン、平面はオンオフ出来るように口を作る。

$logShow=true

三次元迷宮に必要な事。
２０ｘ２０のマップを三次元化する。
地面タイルを作る。
壁タイルを作る。
タイルに文字を書く。
一行メッセージタイルを作る。
三行メッセージタイルを作る。
左右側面タイルを作る。
地面を作る。
東西南北を回転させる。カメラ移動。

```
```
var map ={}; //object for multiple key presses
scene.actionManager = new BABYLON.ActionManager(scene);
scene.actionManager.registerAction(new BABYLON.ExecuteCodeAction(BABYLON.ActionManager.OnKeyDownTrigger, function (evt) {								
map[evt.sourceEvent.key] = evt.sourceEvent.type == "keydown";
}));

scene.registerAfterRender(function() {	
if(map[" "]) {//if space key
}
return scene
}

```
