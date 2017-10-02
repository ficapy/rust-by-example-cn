忽视[省略][elision]（elision）情况，带上生命周期的函数签名（function signature）有一些限制：

* 任何引用**都必须**拥有标注好的生命周期。
* 任何被返回的引用**都必须**有一个和输入量相同的生命周期或是静态类型（`static`）。

另外要注意，若会导致返回的引用指向无效数据，则返回不带输入量的引用是被禁止的。下面例子展示了一些带有生命周期的函数的有效形式：

{fn.play}

### 参见：

[函数][fn]

[elision]: elision.html
[fn]: ../../fn.html