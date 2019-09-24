#第一章 JavaScript基础

### 1.1 JavaScriptgai概述

1.1.1 JavaScriptgai历史
1993年网景公司开发了第一款浏览器Mosaic,继续一种脚本语言让用户与浏览器进行交互，从而提升“用户体验”。

1.1.2 JavaScript的创始人
布兰登 艾奇，仅用了10天时间开发了livescript,后因为java火热的缘故，将其改名为JavaScript.

1.1.3 ECMAScript
1997年以网景公司的JavaScript.1作为草案，提交给欧洲计算机制造商协会（ECMA），指定一个脚本语言的规范。

1.1.4 JavaScript的实现
一个完整的JavaScript结构应该包括三个部分：原生ECMAScript、DOM(文档对象模型)、BOM（浏览器对象模型）。

1.1.5 JavaScript的版本
现在为8

### 1.2 JavaScript脚本
1.2.1 script标签
将JS的脚本语言写在 script 标签里，有两种方法，一种是内部脚本，一种是外部脚本

    <script>
     alert('hellow');
    </script>

1.2.2 内部脚本
js的内部脚本是写在script标签里，并且将其直接放入html文档里的<!DOCTYPE html>下，位置有不同。

1.2.3 外部脚本

利用script标签的src属性引入一个外部的js文件。该脚本放在head标签或者body标签中。

      <script src="外部脚本.js"></script>
