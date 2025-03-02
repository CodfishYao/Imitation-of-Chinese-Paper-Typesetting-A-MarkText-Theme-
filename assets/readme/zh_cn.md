# Imitation of Chinese Paper Typesetting(A MarkText Theme)

该仓库分享了一款MarkText的主题，用以导出HTML或PDF时使得输出的文件模仿中国大学论文格式。

## 安装和使用方式

1.下载该文件

2.打开MarkText的[应用数据文件夹](https://github.com/marktext/marktext/blob/develop/docs/APPLICATION_DATA_DIRECTORY.md)（Windows系统种MarkText的应用数据文件夹通常在‘C:\Users\你的用户名\AppData\Roaming’中）

3.在MarkText的应用数据文件夹中新建文件夹‘themes\export’

4.将下载的文件复制到‘export’文件夹中

5.重启MarkText软件

6.点击菜单栏，找到File→Export，选择HTML或PDF

7.点击Theme，在下拉框中选择‘Imitation of Chinese Paper Typesetting’即可使用该主题

## 格式修改

### 首行缩进

如果您不喜欢默认首行缩进，可以将ICPT.theme.css第89行修改为`text-indent: 0em;`，然后在MarkText中进行手动的缩进。

## 使用技巧

### 排版PDF时增加空行

可以使用HTML标签`<br />`来在MarkText中增加空行，以便于排版导出的PDF。

### 署名

可以使用HTML语句`<p class="name">你的名字</p>`来署名，署名的效果见assets/example文件夹里的example.pdf

### 增加题注

可以使用HTML语句`<p class="caption">题注</p>`来对图表插入题注，效果见assets/example文件夹里的example.pdf

## 声明

本文件修改自MarkText自带的示例主题文件academic.theme.css
