# iWonder Typora Theme

> 一个我想要的Typora主题.
>
> 一个以让文档重点更醒目为原则设计的主题.

> A Typora theme I wanted.
>
> A theme designed to sharpen the focus of the document.

## 特性 / Feature

> 1. 主题配色方案让重点更突出醒目, 详见下方预览.
> 2. 提供更简化的标签快捷键, 配合自定义的标签颜色, 一键修改选中文本颜色.
> 3. iWonder主题仅在Windows系统下做过测试, 无法确定Linux和Mac下效果.
> 4. iWonder主题持续更新中.

> 1. The theme color scheme makes the key points more prominent and eye-catching, as shown in the preview.
> 2. Provide simplified label shortcuts, combined with custom label colors, to modify the selected text color with just one click.
> 3. The iWonder theme has only been tested on Windows systems and cannot determine its effectiveness on Linux and Mac.
> 4. The iWonder theme is constantly being updated.

## 私人订制 / DIY

> 通过修改`iWonder > colorScheme > default.css` 和 `iWonder > fontScheme > default.css`中的配置项, 可以任意修改本主题的字体和颜色.
>
> 进阶：定制多个主题并存.
>
> 示例：假设, 我想要修改一套红色, 宋体字体的主题, 那么我可以：
>
> 1. 复制`iWonder > colorScheme > default.css`并将之重命名为`red.css`, 修改其中的颜色为红色系列.
>
> 2. 复制`iWonder > fontScheme > default.css`并将之重命名为`song.css`, 修改其中的字体为宋体.
>
> 3. 复制`i-w-blue.css`并将之重命名为`i-w-red.css`,
>
>    修改其中`@import url("iWonder/colorScheme/default.css");`文本为`@import url("iWonder/colorScheme/red.css")`,
>
>    修改其中`@import url("iWonder/fontScheme/default.css");`文本为`@import url("iWonder/fontScheme/song.css")`.
>
> 4. Typora中切换名为`IWRed`的主题.

> You can modify the font and color of this theme arbitrarily by modifying the configuration items in `iWonder > colorScheme > default.css` and `Font > fontScheme > default.css`.
>
> Advanced: customize the coexistence of multiple themes.
>
> Example: suppose I want to change the theme of a set of red and song font, then I can:
>
> 1. Copy `red > colorScheme > default.css` and rename it to `red.css`, and change the color to red series.
>
> 2. Copy `iWonder > fontScheme > default.css` and rename it `song.css`, and change the font to Song font.
>
> 3. Copy `i-w-blue.css` and rename it `i-w-red.css`.
>
>    Modify `@ import url ("iWonder/colorScheme/default.css");` text to `@ import url ("iWonder/colorScheme/red.css")`.
>
>    Modify `@ import url ("iWonder/fontScheme/default.css");` text to `@ import url ("iWonder/fontScheme/song.css")`.
>
> 4. Switch the Typora theme named `IWRed`.

## 安装方式 / Install

>> **一键安装✨**
>
>> 1. [点击此处下载.](https://github.com/ReidLv/theme.typora.iWonder/releases/latest)
>> 2. 解压安装包, 然后双击运行安装包中的`setup.bat`脚本.
>> 3. Typora中切换主题(主题名格式：`IWxxxx`).
>
>> **手动安装**
>>
>> 1. [点击此处下载.](https://github.com/ReidLv/theme.typora.iWonder/releases/latest)
>> 2. 解压安装包, 将安装包中所有内容粘贴到主题目录.主题目录可通过`Typora > 菜单 > 主题 > 打开主题文件夹`打开.
>> 3. Typora中切换主题(主题名格式：`IWxxxx`).
>

> >**Quick Install✨**
> >
> >1. [DownLoad.](https://github.com/ReidLv/theme.typora.iWonder/releases/latest)
> >2. Unzip the installation package, and double-click to run the `setup.bat` script in the installation package.
> >3. Switch Typora theme. (theme name format：`IWxxxx`).
>
> > **Step by step Install**
> >
> > 1. [DownLoad.](https://github.com/ReidLv/theme.typora.iWonder/releases/latest)
> > 2. Unzip and paste everything in the installation package into the theme folder. The theme folder can be opened from`Typora > menu> themes > open themes folder`.
> > 3. Switch Typora theme. (theme name format：`IWxxxx`).

## 预览 / Preview

<img src="ref/demo-img-01.png" alt="demo-img-01" style="zoom: 33%;" />

<img src="ref/demo-img-02.png" alt="demo-img-02" style="zoom:33%;" />

<img src="ref/demo-img-03.png" alt="demo-img-03" style="zoom:33%;" />

<img src="ref/demo-img-04.png" alt="demo-img-04" style="zoom:33%;" />

![缩略图](ref/iWonder.png)

## 快捷键 / ShortcutKeys

| Function   | 功能       | 快捷键         |
| ---------- | ---------- | -------------- |
| Find       | 查找       | `Ctrl+F`       |
| Replace    | 替换       | `Ctrl+R`       |
| Strong     | 加粗       | `Ctrl+B`       |
| Emphasis   | 斜体       | `Ctrl+I`       |
| Strike     | 删除线     | `Ctrl+D`       |
| Underline  | 下划线     | `Ctrl+U`       |
| Highlight  | 高亮       | `Ctrl+H`       |
| Hyperlink  | 超链接     | `Ctrl+L`       |
| Code       | 代码块     | `Ctrl+K`       |
| CodeFences | 多行代码块 | `Ctrl+Shift+K` |
| Image      | 图片       | `Ctrl+Shift+I` |

