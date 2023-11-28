# hyksk_webfont

汉仪空山楷 web font

⚠️ 源字体是从[chinaz](https://font.chinaz.com/220328172150.htm)下载。商业使用需购买授权。


## 使用说明

1，引入 CSS 文件。

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/bofeng/hyksk_webfont/dist/hyksk.css" />
```


2，应用字体样式

```css
body {
    font-family: hyksk, sans-serif;
}
```


## How to build

1. Use git to clone this repo, or fork it.
1. Delete all files under the source folder.
1. Delete all files under the dist folder.
1. Download the HYKSK font, put all .ttf files into the source folder.
1. Run `pnpm install` and `pnpm run build`. you will be able to see the generated files under the dist folder.
