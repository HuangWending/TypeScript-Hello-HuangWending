# TypeScript-Hello-HuangWending
TypeScript打印Hello,HuangWending程序
function sayHello(name: string) { ... }：定义了一个名为sayHello的函数，它接受一个名为name、类型为string的参数。
console.log(Hello, ${name});：使用console.log()函数打印字符串到控制台。在这里，我们使用了模板字符串，使用${}语法将变量name的值嵌入到字符串中。
sayHello("HuangWending");：调用sayHello函数并传入字符串参数"HuangWending"。
程序中，我们定义了一个名为sayHello的函数，它将传入的名字作为参数，并将"Hello, 名字"打印到控制台。然后，我们调用sayHello函数并传入字符串参数"HuangWending"，这将输出"Hello, HuangWending"到控制台。请注意，TypeScript需要被编译为JavaScript后才能在浏览器或Node.js中执行。
