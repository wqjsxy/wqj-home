<p>
<strong><h2>WayneのHome</h2></strong>
</p>

主页修改自[無名の主页](https://github.com/imsyy/home)

![無名の主页](https://s2.loli.net/2022/07/14/K5JigfvDoNewtuS.webp)

>主页的 Logo 字体已经过压缩，若用本站 Logo 以外的字母会变回默认字体

>天气 API 需 [自行申请](https://www.tianqiapi.com/)，或更换其他 API [【和风天气】](https://dev.qweather.com/) [【ROLL】](https://www.mxnzp.com/doc/list)

### Demo
>由于 CDN 缓存原因，查看最新效果可能需要 `Ctrl` + `F5` 强制刷新浏览器缓存

- [WayneのHome](https://soga.ml/)

### 功能

- [x] 载入动画
- [x] 站点简介
- [x] Hitokoto 一言
- [x] 日期及时间
- [x] 实时天气
- [x] 时光进度条
- [x] 音乐播放器
- [x] 移动端适配

### 音乐

>本项目采用了基于 `MetingJS` 的 `Aplayer` 音乐播放器，可实现快速自定义歌单  
>*仅支持 **中国大陆地区**，其他区域请将以下内容替换 `music.js` 以实现音乐播放器的正常使用

更改 `music.js` 的参数即可实现自定义歌单列表

```js
let server = "tencent"; //netease: 网易云音乐; tencent: QQ音乐; kugou: 酷狗音乐; xiami: 虾米; kuwo: 酷我
let type = "playlist"; //song: 单曲; playlist: 歌单; album: 唱片
let id = "7476871946"; //封面 ID / 单曲 ID / 歌单 ID
```

### 插件

* [Bootstrap](https://getbootstrap.com/)
* [iziToast](https://izitoast.marcelodolza.com/)
* [Font Awesome](https://fontawesome.com/)
* [jQuery](https://jquery.com/)
* [Aplayer](https://aplayer.js.org/)

### API

* [MetingAPI By injahow](https://api.injahow.cn/meting/)
* [小歪 API](https://api.ixiaowai.cn/)
* [天气 API](https://www.tianqiapi.com/)
* [Hitokoto 一言](https://hitokoto.cn/)

<a title="Copyright" target="_blank" href="https://soga.ml/"><img src="https://img.shields.io/badge/Copyright%20%C2%A9%202022--2022-Wayne-red"></a>
