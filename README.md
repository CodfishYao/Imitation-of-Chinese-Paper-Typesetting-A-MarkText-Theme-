# Imitation of Chinese Paper Typesetting(A MarkText Theme)

The repository shares a MarkText theme for exporting HTML or PDF files that mimic the Chinese university paper format.

([点击进入中文版本](/assets/readme/zh_cn.md))该仓库分享了一款MarkText的主题，用以导出HTML或PDF时使得输出的文件模仿中国大学论文格式。


## Installation and Use

1.Download this file(ICPT.theme.css)

2.Open MarkText's [Application Data Directory](https://github.com/marktext/marktext/blob/develop/docs/APPLICATION_DATA_DIRECTORY.md)（It is usually at 'C:\Users\yourUserName\AppData\Roaming' in the Windows）

3.Creat a new folder ‘themes\export’ in the application data directory of MarkText

4.Copy the downloaded file 'ICPT.theme.css' to folder 'export'

5.Restart MarkText

6.Click menu bar, find File→Export，choose PDF(or HTML)

7.Click Theme，Select 'Imitation of Chinese Paper Typesetting'’' from the drop-down list then you can use it!

## Format Modification

### IIndentation of the First Line

If you don't like the default first line indent, you can change line 89 of ICPT.theme.css to 'text-indent: 0em; ', and then indent manually in MarkText.

## Skills

### Add Blank Lines Typesetting PDFS

You can use the HTML tag `<br />` to add blank lines to MarkText to facilitate formatting the exported PDF.

### Signaturee

This can be done using the HTML statement `<p class="name"> your name </p>`. See example.pdf in the assets/example folder.

### Add Caption

You can add a caption to the chart or figure using the HTML statement `<p class="caption"> </p>` as example.pdf in the assets/example folder.

## Declaration

This css file is modified from the example theme file 'academy.theme.css' (form MarkText).