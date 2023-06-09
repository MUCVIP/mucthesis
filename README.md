# 中央民族大学学位论文LaTeX模板

这是一个**非官方**的中央民族大学学位论文LateX模板  
**本模板仅供交流学习使用，实际使用中造成的任何损失由使用者个人承担**

## 文件列表

| 文件名 | 类型 | 描述 |
|:-----:|:---:|:--|
| `main.tex` | tex文本 | 主tex文件 |
| `chapter` | 目录 | 包含各章节文件，包括封面、双语摘要、正文、参考 |
| `format-reference` | 目录 | 学校发布的doc格式参考文件 |
| `images` | 目录 | 图片存放目录 |
<!-- | `-` |  |  | -->

## 使用方法

### 如何修改正文

正文中各种宏的调用参看`chapter`目录下的文件。

### 如何插入封面

使用目录`format-reference`下的文件编辑并生成pdf格式的封面  
可以使用Microsoft print to pdf工具将word文件打印到pdf文件  
注意只输出封面，后面的页不用输出

封面文件保存到`chapters/titlepage.pdf`  
编译文档时即可插入封面

### 如何插入参考文献

参考文献全部插入到`chapters/reference.bib`中  
该文件参考格式为BibTex，各文献平台都支持输出该格式的参考

调用`gbt7714`宏包在文末自动插入的参考格式符合[GB/T 7714-2015](https://baike.baidu.com/item/%E4%BF%A1%E6%81%AF%E4%B8%8E%E6%96%87%E7%8C%AE%E2%80%94%E5%8F%82%E8%80%83%E6%96%87%E7%8C%AE%E8%91%97%E5%BD%95%E8%A7%84%E5%88%99/57092464)
之规定

## LICENSE

[LaTeX Project Public License v1.3c](https://choosealicense.com/licenses/lppl-1.3c/)
