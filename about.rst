关于中文版
============

关于源文件格式
--------------

原英文文档使用的是reStructureText标准格式, 中文文档使用Sphinx工具, 虽然仍然是rst格式的文档, 但是其中某些标记和原文有所不同.

翻译说明
----------

尽量做到按原文翻译, 有些地方感觉原文实在太啰嗦了, 在不影响理解的情况下有所省略.

关于术语的翻译
^^^^^^^^^^^^^^

术语的翻译尽量使用通用的译法, 一般确定不会影响歧义的都直接翻译, 有的会在第一次出现时备注原英文, 有的不方便直译的保留原文或者其它更熟悉的缩写替代.
例如: free keyword arguments 怎么翻译都别扭, 除了少数地方直译为"任意命名参数", 后面一般都使用大家都熟悉的 `**kwargs` 写法指代.


关于表格和代码示例
^^^^^^^^^^^^^^^^^^

文档中出现的大量代码示例和表格, 绝大多数情况都没有做任何翻译, 因为这些内容都很简单, 而且其中的代码是不可能翻译的, 如果只翻译部分, 混杂一起反而看着很别扭. 
表格部分的情况和代码类似, 而且翻成中文还会出现无法对齐的问题, reST中编辑表格是一件比较痛苦的事情.
