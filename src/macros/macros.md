Rust 提供了一个强大的宏系统，可进行元编程（metaprogramming）。正如你已经看过了前面章节，宏看起来和函数很像，除了名称末尾连着一个感叹号 `!` ，但宏并不产生一个函数调用，而是展开成源码并结合程序的其余代码一起进行编译。

宏是通过 `macro_rules!` 宏来创建的。

{simple.play}