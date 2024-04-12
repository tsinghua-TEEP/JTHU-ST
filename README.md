> 基于 [JBUAA](https://github.com/Htallone/JBUAA) 和 [THU_emp](https://www.overleaf.com/latex/templates/thu-emp-qing-hua-da-xue-jin-dai-wu-li-shi-yan-bao-gao-mo-ban/mbgqcryqhwqd)

# 清华大学学报（自然科学版）LaTeX模板（非官方）

# LaTeX Template (unofficial) for Journal of Tsinghua University

**!!!!! 注意，你清学报目前不接收LaTex稿件 !!!!!**
**上传tex源文件及pdf文件将收到回信：缺少稿件Word版。**
**仅作为满足课程作业要求用，本仓库将没有长期维护**
**当前格式不符合投稿要求，仅满足个人需求**

- `jthu-st.cls` 模板文件
- `cite.sty` `GB.cpx` 引用样式、中文支持相关文件（文件内有原作者信息）
- `TempExample.tex` 正文内容
- `TempExample.bib` 参考文献
- `image\` 目录下是正文中用到的图片文件

在完整安装 texlive 2016 或者 texlive 2017条件下，直接在命令行按顺序运行如下命令即可

```
xelatex TempExample.tex  
bibtex TempExample  
xelatex TempExample.tex  
xelatex TempExample.tex
```

最终生成 `TempExample.pdf` 文件

-----

Symbol 文件夹下是《变量符号说明》生成文档
增加了符号在文中的位置的信息，需要辅助文件 `TempExample.aux`


<!--- ![shot](shot.png) --->



