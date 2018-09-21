0. 入门介绍
=============

Sphinx，reSturcturedtext，GitHub，Readthedocs这几个名词一下子涌过来对初学者来说可能是有点蒙的。网上有许多优质的文档介绍如何用这三个工具搭建环境来创作文档。

简单地来说就是，我们必须：

    - 使用rst写出文档，这一步类似我们在word中写作，敲入文字后还是要手动设置样式，包括各级标题、设置缩进、粗体等，而在用rst（一种轻量级标记语言）写作时，我们也需要设置标题、表格、列表、图片等，例如我们可以通过在文字下面加“====”来表示这是一个标题。但别害怕，rst有自己的语法非常简单，可以 **边参考教程** 边写文档。我们可以安装visual studio code这个工具来辅助书写rst文档，其提供语法高亮、缩进的功能。

    - 使用sphinx发布文档，sphinx的功能在于能够把rst文档发布成我们需要的输出格式，例如html, epub, htmlhel等等格式。而且sphinx的安装、新建项目都能在网上教程的指引下一步一步完成。

    - 使用GitHub托管代码，我们将rst文档托管至GitHub上，每次对文档进行更新时更方便，也会提供代码版本控制

    - 使用Readthedocs托管文档，这个部分其实是和sphinx发布文档、GitHub代码托管紧密联系的，它的作用在于把代码实时发布成html，而不需要我们每次都使用sphinx发布文档。

以下是一些优质文档：

对整个流程的了解：

https://www.cnblogs.com/youxin/p/3594161.html

rst语法入门：

https://www.cnblogs.com/seayxu/p/5603876.html 
        
https://zh-sphinx-doc.readthedocs.io/en/latest/rest.html

sphinx使用入门：

http://www.sphinx-doc.org/en/master/usage/installation.html

http://www.sphinx-doc.org/en/master/usage/quickstart.html

https://www.jianshu.com/p/de731c4b94a0

GitHub使用：

https://www.cnblogs.com/r360/p/4931432.html 
        
https://blog.csdn.net/javaandroid730/article/details/53522872

Readthedocs使用：

https://www.xncoding.com/2017/01/22/fullstack/readthedoc.html

