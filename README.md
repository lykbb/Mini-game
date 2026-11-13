# Mini-game · 小游戏制作的小尝试

这里放一些用纯代码写的小游戏和 3D 小动画实验。
不用任何外部模型或图片文件，所有画面都由代码生成（HTML + JavaScript + Three.js）。

## 游戏列表

| 游戏 | 说明 |
| --- | --- |
| [铅笔港湾 Pencil Harbour](./pencil-harbour/) | 彩色铅笔画风的意大利海港小镇。扮演黄雨衣小画家，在小镇里找齐 8 支彩色铅笔，迎来日落。 |

## 怎么运行

每个游戏都是一个单独的 `index.html`，Three.js 通过 CDN 加载。
在游戏文件夹里起一个本地服务器，然后用浏览器打开：

```bash
cd pencil-harbour
python3 -m http.server 8000
# 浏览器打开 http://localhost:8000
```

## 说明

都是边做边学的小尝试，画面和玩法都还比较粗糙，会慢慢改进。
