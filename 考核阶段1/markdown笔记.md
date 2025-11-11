1. ==标题语法==

#  一级标题

## 二级标题

### 三级标题

注:用一个空格在 `#` 和标题之间进行分隔。

2. ==段落语法==

I really like using Markdown.

I think I'll use it to format all of my documents from now on.

注:不要用空格（spaces）或制表符（ tabs）缩进段落。

3. 换行语法

在一行的末尾添加两个或多个空格，然后按回车键,即可创建一个换行  

4. ==强调语法==   

   **加粗**  单词或短语的前后各添加两个星号。

   *斜体*  单词或短语的前后添加一个星号。

   ***加粗和斜体***  单词或短语的前后各添加三个星号或下划线。

   ~~删除线~~    若要删除单词，请在单词前后使用两个波浪号`~~`。

5. ==引用语法==  

   > 这是一个引用  

   要创建块引用，在段落前添加一个 `>` 符号。 

   > part1
   >
   > > part2   

   块引用可以嵌套。在要嵌套的段落前添加一个 `>>` 符号。

   > #### The quarterly results look great!
   >
   > - Revenue was off the chart.
   > - Profits were higher than ever.
   >
   >  *Everything* is going according to **plan**.

​        块引用可以包含其他 Markdown 格式的元素。

6. ==列表语法== 

   要创建有序列表，请在每个列表项前添加数字并紧跟一个英文句点。

   要创建无序列表，请在每个列表项前面添加破折号 (-)、星号 (*) 或加号 (+) 。缩进一个或多个列表项可创建嵌套列表。

   

7. ==代码语法== 

    At the command prompt, type `nano`.   

   要将单词或短语表示为代码，请将其包裹在反引号 (`) 中。

   

   [代码块](https://markdown.com.cn/basic-syntax/lists.html#code-blocks)通常采用四个空格或一个制表符缩进。当它们被放在列表中时，请将它们缩进八个空格或两个制表符。

   补充：Markdown基本语法允许您通过将行缩进四个空格或一个制表符来创建[代码块](https://markdown.com.cn/basic-syntax/code-blocks.html)。如果发现不方便，请尝试使用受保护的代码块。根据Markdown处理器或编辑器的不同，您将在代码块之前和之后的行上使用三个反引号（(`````）或三个波浪号（~~~）。

   

8. ==分隔线语法==  

   要创建分隔线，请在单独一行上使用三个或多个星号 (`***`)、破折号 (`---`) 或下划线 (`___`) ，并且不能包含其他内容。最好在分隔线的前后均添加空白行。

   

9. ==链接语法==  

   链接文本放在中括号内，链接地址放在后面的括号中，链接title可选。

   超链接Markdown语法代码：`[超链接显示名](超链接地址 "超链接title")`

   如：这是一个链接 [Markdown语法 (opens new window)](https://markdown.com.cn/)

   

   链接title是当鼠标悬停在链接上时会出现的文字，这个title是可选的，它放在圆括号中链接地址后面，跟链接地址之间以空格分隔。

   ```text
   这是一个链接 [Markdown语法](https://markdown.com.cn "最好的markdown教程")
   ```

   

   使用尖括号可以很方便地把URL或者email地址变成可点击的链接。

   

   [强调](https://markdown.com.cn/basic-syntax/links.html#emphasis) 链接, 在链接语法前后增加星号。 要将链接表示为代码，请在方括号中添加反引号。

   如：

   ```text
   I love supporting the **[EFF](https://eff.org)**.
   This is the *[Markdown Guide](https://www.markdownguide.org)*.
   See the section on [`code`](#code).
   ```

   效果为：I  love supporting the **[EFF (opens new window)](https://eff.org/)**.
                  This is the *[Markdown Guide (opens new window)](https://www.markdownguide.org/)*.
                  See the section on [`code`](https://markdown.com.cn/basic-syntax/links.html#code).

   

   引用样式链接是一种特殊的链接，它使URL在Markdown中更易于显示和阅读。参考样式链接分为两部分：与文本保持内联的部分以及存储在文件中其他位置的部分，以使文本易于阅读。

   - 引用类型的链接的第一部分使用两组括号进行格式设置。第一组方括号包围应显示为链接的文本。第二组括号显示了一个标签，该标签用于指向您存储在文档其他位置的链接。

    尽管不是必需的，可以在第一组和第二组括号之间包含一个空格。第二组括号中的          标签不区分大小写，可以包含字母，数字，空格或标点符号。

   - 引用类型链接的第二部分使用以下属性设置格式：

   1. 放在括号中的标签，其后紧跟一个冒号和至少一个空格（例如`[label]:`）。

   2. 链接的URL，可以选择将其括在尖括号中。

   3. 链接的可选标题，可以将其括在双引号，单引号或括号中。

      

      注：不同的 Markdown 应用程序处理URL中间的空格方式不一样。为了兼容性，请尽量使用**%20**代替空格。

10. ==图片语法==

    ![举例](考核阶段1/assests/屏幕截图 2025-11-10 190959.png)

     ![test]()

    ```text
    [![沙漠中的岩石图片](/assets/img/shiprock.jpg "Shiprock")](https://markdown.com.cn)
    ```

11. ==转义字符语法==

    要显示原本用于格式化 Markdown 文档的字符，请在字符前面添加反斜杠字符 \ 。

    如：\* Without the backslash, this would be a bullet in an unordered list.

    [![转义符](C:\Users\35748\Pictures\Screenshots\屏幕截图 2025-11-10 195514.png)]

    注：在 Markdown 的块级元素和内联元素中， `<` 和 `&` 两个符号都会被自动转换成 HTML 实体，这项特性让你可以很容易地用 Markdown 写 HTML。（在 HTML 语法中，你要手动把所有的 `<` 和 `&` 都转换为 HTML 实体。） 

    如果你要打「AT&T」 ，你必须要写成「`AT&T`」。

    

12. ==Markdown 内嵌 HTML 标签==

    区块元素──比如 `<div>`、`<table>`、`<pre>`、`<p>` 等标签，必须在前后加上空行，以便于内容区分。而且这些元素的开始与结尾标签，不可以用 tab 或是空白来缩进。Markdown 会自动识别这区块元素，避免在区块标签前后加上没有必要的 `<p>` 标签。

    

13. ==markdown扩展语法==

    （1）markdown表格  

    要添加表，请使用三个或多个连字符（`---`）创建每列的标题，并使用管道（`|`）分隔每列。您可以选择在表的任一端添加管道。

    **Tip:** 使用连字符和管道创建表可能很麻烦。为了加快该过程，请尝试使用[Markdown Tables Generator](https://www.tablesgenerator.com/markdown_tables)。使用图形界面构建表，然后将生成的Markdown格式的文本复制到文件中。

    您可以通过在标题行中的连字符的左侧，右侧或两侧添加冒号（`:`），将列中的文本对齐到左侧，右侧或中心。

    您可以使用表格的HTML字符代码（`|`）在表中显示竖线（`|`）字符。

    （2）Markdown 脚注

    要创建脚注参考，请在方括号（`[^1]`）内添加插入符号和标识符。标识符可以是数字或单词，但不能包含空格或制表符。标识符仅将脚注参考与脚注本身相关联-在输出中，脚注按顺序编号。

    在括号内使用另一个插入符号和数字添加脚注，并用冒号和文本（`[^1]: My footnote.`）。您不必在文档末尾添加脚注。您可以将它们放在除列表，块引号和表之类的其他元素之外的任何位置。

    （3）Markdown 标题编号

    添加自定义ID允许直接链接到标题并使用CSS对其进行修改。要添加自定义标题ID，请在与标题相同的行上用大括号括起该自定义ID。

    如：### My Great Heading {#custom-id}  

    HTML:<h3 id="custom-id">My Great Heading</h3>

    （4）Markdown 定义列表

    一些Markdown处理器允许您创建术语及其对应定义的*定义列表*。

    如：

    ```text
    First Term
    : This is the definition of the first term.
    
    Second Term
    : This is one definition of the second term.
    : This is another definition of the second term.
    ```

输出为：

​               First Term

​                     This is the definition of the first term.

​               Second Term

​                     This is one definition of the second term.

​                     This is another definition of the second term.

​       （5）Markdown 任务列表语法

​        任务列表使您可以创建带有复选框的项目列表。

如：

```text
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
```

输出为：[![任务列表](C:\Users\35748\Pictures\Screenshots\屏幕截图 2025-11-10 214204.png)]

​      （6）Markdown 使用 Emoji 表情

有两种方法可以将表情符号添加到Markdown文件中：将表情符号复制并粘贴到      Markdown格式的文本中，或者键入*emoji shortcodes*（[📙 Emojipedia — 😃 Home of Emoji Meanings 💁👌🎍😍](https://emojipedia.org/)），还有一个[markdown 表情符号标记的完整列表]（[github markdown 表情符号标记的完整列表](https://gist.github.com/rxaviers/7360908)） 最简便的方式：Win键+句号键就可以去使用emoji，直接翻找选择合适的emoji。

如：

```text
去露营了！ :tent: 很快回来。

真好笑！ :joy:
```

输出结果为：去露营了！⛺很快回来。

​                        真好笑！😂



14. ==问题：==

- 轻量标记语言 

  轻量标记语言

  有几种轻量级标记语言是Markdown的超集。它们包含Gruber的基本语法，并通过添加其他元素（例如表，代码块，语法突出显示，URL自动链接和脚注）在此基础上构建。许多最受欢迎的Markdown应用程序使用以下轻量级标记语言之一：

  - [CommonMark(opens new window)](https://commonmark.org/)

  - [GitHub Flavored Markdown (GFM)(opens new window)](https://github.github.com/gfm/)

  - [Markdown Extra(opens new window)](https://michelf.ca/projects/php-markdown/extra/)

  - [MultiMarkdown(opens new window)](https://fletcherpenney.net/multimarkdown/)

  - [R Markdown](https://rmarkdown.rstudio.com/)

    

- markdown处理器

  有许多[Markdown处理器 (opens new window)](https://github.com/markdown/markdown.github.com/wiki/Implementations)可用。它们中的许多允许您添加启用扩展语法元素的扩展。查看您所使用处理器的文档以获取更多信息。

  

  

15. 参考：[Markdown 扩展语法入门 | Markdown 教程](https://markdown.com.cn/extended-syntax/)






