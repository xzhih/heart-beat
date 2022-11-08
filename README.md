# threejs 3D心跳

只有一个文件，下载后双击打开就看到了。

html 文件里有一些控制的参数，可以自己调整。

```js
  let backguandColor = 0x000000; //背景颜色 hex色值
  let heartColor = "vec3(1,0,0)"; //心形颜色 GLSL vec3色值 紫色: vec3(0.627,0,0.627)
  let heartEdgeColor = "vec3(1,1,1)"; //心形边缘颜色 GLSL vec3色值 可以在这里转换 https://airtightinteractive.com/util/hex-to-glsl/
  let particleSize = 4; // 粒子大小
  let particleLoose = 100; // 稀疏程度 值越大粒子越少
  let particleSpeed = 30; // 粒子运动速度
  let rotationSpeedX = 0; // 爱心X旋转速度(上下旋转) 值越大旋转越快 负数为反向旋转 0为不旋转
  let rotationSpeedY = 1; // 爱心Y旋转速度(左右旋转)
  let heartEdgeSize = 2; // 爱心边缘颜色范围大小
```
