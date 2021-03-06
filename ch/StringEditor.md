---
title: 字符串编辑器
---

# 字符串编辑器

[字符串](Strings) 可以通过 **BibTeX → 编辑字符串** 或按工具栏中的按钮进行编辑。

*字符串* 在 *BibTeX* 中相当于编程语言中的常量。每一个字符串都使用唯一的 *名字* 和 *内容*来定义。 在数据库的其他位置，名称可用于表示内容。

例如，如果在许多条目中出现了难以记住的学术期刊的缩写，例如 'J. Theor. Biol.' (Journal of Theoretical Biology), 可以定义一个名为JTB的字符串来表示该期刊的名称。不需要在每一条目中重复具体的期刊名称，而是将 '\#JTB\#' (不带引号) 放入每个条目的 *journal* 字段中，确保每次学术期刊的名称都能正确录入。

字符串引用可以出现在字段中的任何位置，始终将字符串的名称括在一对 '\#' 字符中。此语法仅在JabRef中独有，与保存数据库时生成的*BibTeX* 表示法略有不同。 默认情况下，字符串可用于所有标准BibTeX字段，在 ** 首选项 → 通用 → 文件** ，您也可以选择为非标准字段启用字符串。在后一种情况下，您可以指定一组字段不被字符串解析，我们建议您加入'url'等可能需要包含'\#'字符的字段，因为这样的字段可能被BibTeX/LaTeX处理。

只要被引用的字符串在引用字符串的字符串之前定义，字符串就可以以相同的方式在另一字符串的内容中引用。

虽然在某些情况下BibTeX文件中的字符串顺序很重要，但在使用JabRef时不必担心这一点。字符串将在字符串编辑器中按字母顺序显示，并以相同的顺序存储，除非BibTeX中声明需要不同的顺序。

有关字符串语法的完整说明，请参阅[专用帮助](Strings).
