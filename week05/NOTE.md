# 每周总结可以写在这里

## realms

每一个realm里都有一套完整的JS内置对象

### 为什么会有Realms

因为JS执行环境的多样性，在浏览器中，一个窗口(一个框架、一个打开了 window.open ()的窗口，或者只是一个普通的浏览器标签)是一个Realms。为了避免相互影响，所有会有realms的存在

不同的realms里执行构造函数等内置方法时，使用的是该realms下的方法，不同realms下互不影响。

[javascript - How to understand JS realms - Stack Overflow](https://stackoverflow.com/questions/49832187/how-to-understand-js-realms)
