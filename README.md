<img src="http://lengyibai.gitee.io/img-bed/img/lyb.png" style="width:200px;margin:0 auto;border-radius:50%" />

<p style="font-size:50px;font-weight:bold;width:100%;text-align:center;color:#fff;text-shadow:0 0 15px">冷弋白</p>
<p style="text-align:center;color:#aaa;position: relative;top:-10px;text-shadow:0 0 10px"><a href='https://wpa.qq.com/msgrd?v=3&uin=1329670984&site=qq&menu=yes' style='text-decoration: none;
'>点击此处联系我</a></p>



# Vscode主题定制

![vscode](http://lengyibai.gitee.io/theme-customization/img/vscode.png)

## SynthWave '84

> 代码荧光主题
>
> 以管理员身份运行`Vscode`
>
> 安装扩展 > `Ctrl + Shift + P` > 搜索`84` > 鼠标点击`synthwave84.enableNeon` > 右下角弹窗 > 点击`Reset`按钮重启`Vscode` > 重启完成 > Ctrl + Shift +P > 搜索`打开设置(json)` > 将`"synthwave84.brightness"`值修改为`1`，如果没有则添加 > 重启`Vscode`，如果荧光不明显则再重启一次

## vscode-live2d

> 右下角看板娘
>
> 以管理员身份运行`Vscode`
>
> 安装扩展 > `Ctrl + Shift + P` > 搜索`打开设置(json)` > 删除带有`vscode-live2d`前缀的内容 > 将下列参数粘贴进去 >  重启`Vscode`

```json
"vscode-live2d.model": "Pio",
"vscode-live2d.modelHeight": 500,
"vscode-live2d.English": true,
"vscode-live2d.opacity": 0.5,
"vscode-live2d.pointerPenetration": true,
"vscode-live2d.talk": false,
"vscode-live2d.moveY": -150,
"vscode-live2d.moveX": -75,
```

> 如果看板娘没有出现 > 打开路径（`Vscode`安装在哪个盘？`C or D`） `C:\Program Files (x86)\Microsoft VS Code\resources\app\out\vs\code\electron-browser\workbench` > 编辑`workbench.html` > 将`head`标签内容更改如下 > 重启`Vscode`

```html
<head>
  <meta charset="utf-8" />
  <meta http-equiv="Content-Security-Policy" content="default-src 'none'; img-src 'self' https: data: blob: vscode-remote-resource:; media-src 'none'; frame-src 'self' vscode-webview: https://*.vscode-webview-test.com; object-src 'self'; script-src 'self' 'unsafe-inline' 'unsafe-eval'; style-src 'self' 'unsafe-inline'; connect-src 'self' https:; font-src 'self' https: vscode-remote-resource:;"/>
</head>
```

## indent-rainbow

> 彩色缩进
>
> 安装扩展 > `Ctrl + Shift + P` > 搜索`打开设置(json)` > 删除带有`indentRainbow`前缀的内容 >  将下列参数粘贴进去 > 重启`Vscode`

```json
"indentRainbow.colors": [
  "rgba(255, 0, 0, 0.15)",
  "rgba(255, 115, 0, 0.15)",
  "rgba(229, 255, 0, 0.15)",
  "rgba(0, 255, 21, 0.15)",
  "rgba(0, 255, 242, 0.15)",
  "rgba(0, 110, 255, 0.15)",
  "rgba(38, 0, 255, 0.15)",
  "rgba(183, 0, 255, 0.15)",
  "rgba(255, 0, 170, 0.15)"
],
```

## Power Mode

> 代码粒子效果
>
> 安装扩展 > `Ctrl + Shift + P` > 搜索`打开设置(json)` > 删除带有`powermode`前缀的内容 >  将下列参数粘贴进去 > 重启`Vscode`

```json
"powermode.enabled": true,
"powermode.comboThreshold": 1,
"powermode.explosionDuration": 1500,
"powermode.explosionSize": 20,
"powermode.shakeIntensity": 0,
```

## Bracket Pair Colorizer

> 带颜色的`{}`，点击括号会有线条首尾相连，区分代码块

## vscode-icons

> 文件及文件夹图标

# 附赠

## Typora主题

> 我魔改的主题，灵感来自`Vscode`的`SynthWave '84`主题
>
> 并额外增加了灰调主题
>
> 下载上面的`灰.css`或`紫.css` > 打开`Typora`  > 点击文件 > 偏好设置 > 外观 > 打开主题文件夹 > 将`css文件`粘贴到此文件夹 > 重启`Typora` > 点击主题 > 选择`lyb`
>
> 额外附赠破解版的`Typora`

**灰**

![typora](http://lengyibai.gitee.io/theme-customization/img/gray.png)

**紫**

![typora](http://lengyibai.gitee.io/theme-customization/img/purple.png)

**代码截图文件在这里：[Web前端笔记.md](https://gitee.com/lengyibai/web-notes/blob/master/HTML+CSS+JS/Web/Web.md#reduce-%E9%AB%98%E7%BA%A7%E8%AF%AD%E6%B3%95%E5%90%88%E9%9B%86)**

