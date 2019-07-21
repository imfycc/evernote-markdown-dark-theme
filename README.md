# 印象笔记 Markdown 暗色主题

印象笔记终于支持 Markdown 了 🚀 ，但是主题略显单薄。所以自定义了一套暗色风格的 Markdown 主题。欢迎大家尝鲜 🎉 并 star。

## 使用

1、下载本主题中的 `style.css` 文件。

2、修改印象笔记的文件。

要修改的文件在这个路径下：

```
/Applications/印象笔记.app/Contents/Resources/common-markdown-mac/
```

如果你想使用亮色主题，修改该目录下的 `index.html` 文件（文末提供了一个亮色主题）。

如果你想使用暗色主题，修改该目录下的 `index_darkmode.html` 文件。

* 方法一（如果你对命令行比较亲切）😸：

  在终端使用 `vi` 编辑器，打开以下文件，命令如下：

  ```bash
  vi /Applications/印象笔记.app/Contents/Resources/common-markdown-mac/index_darkmode.html
  ```

* 方法二（如果你对界面操作比较亲切）😸：

  在应用程序文件夹找到印象笔记，鼠标右键 -> 显示包内容，按照上面的路径找到 `/index_darkmode.html` 文件。

在原来 <link> 标签的下面插入一行：

```css
<link href="这里写你存放 style.css 的路径" rel="stylesheet">
```

如下：

![image](https://user-images.githubusercontent.com/9588284/61593067-5b6e0500-ac0d-11e9-835d-861b6272aba1.png)

3、重启印象笔记，使其生效。


## 开发

印象笔记编辑器是使用的一个开源编辑器 [tui.editor](https://github.com/nhn/tui.editor)，你可以在这个[页面](https://nhn.github.io/tui.editor/api/latest/tutorial-example12-customize-toolbar.html#)审查元素，找到每一个元素对应的 `class`，然后配置自己的颜色主题 💪 。

## 效果

![image](https://user-images.githubusercontent.com/9588284/61592774-3e840280-ac0a-11e9-8e00-a51e498e6f9f.png)


## 相关

[evernote-markdown-vue](https://github.com/timothyzhw/evernote-markdown-vue)

> 一套印象笔记亮色主题


