 Backbone 式的注释
======================

Backbone 的代码，采用了说明式注释，在每个需要说明的方法或代码段前，会写上一两句话，描述下面的代码是干嘛的。典型代码：

https://github.com/documentcloud/backbone/blob/master/backbone.js

这种风格，也能很方便的生成文档：

http://documentcloud.github.com/backbone/docs/backbone.html

虽然针对各个方法的注释，也会有一些啰嗦重复（比如前面一个方法是 setXxx, 后面一个方法是 setYxx, 两者的注释大同小异），但由于摆脱了 JSDoc 的禁锢，不用再去描述参数名，这样已经大幅度降低了注释的重复率，同时也让注释的腐坏变慢，至少比 JSDoc 式注释慢很多。同时又能生成一份可读性不错的文档，因此我觉得这种风格是值得推荐的。
