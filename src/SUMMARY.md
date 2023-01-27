# 搞定 Rust 编程语言

[Rust 编程语言](title-page.md)
[前序](foreword.md)
[简介](ch00-00-introduction.md)

## 开始

- [开始](ch01-00-getting-started.md)

  - [安装](ch01-01-installation.md)
  - [入门](ch01-02-hello-world.md)
  - [Cargo 包管理器](ch01-03-hello-cargo.md)

- [猜谜游戏](ch02-00-guessing-game-tutorial.md)

- [概念](ch03-00-common-programming-concepts.md)

  - [可变变量和不可变变量](ch03-01-variables-and-mutability.md)
  - [数据类型](ch03-02-data-types.md)
  - [函数](ch03-03-how-functions-work.md)
  - [注释](ch03-04-comments.md)
  - [流程控制](ch03-05-control-flow.md)

- [了解所有权](ch04-00-understanding-ownership.md)

  - [什么是所有权](ch04-01-what-is-ownership.md)
  - [引用和借用](ch04-02-references-and-borrowing.md)
  - [切片类型](ch04-03-slices.md)

- [使用 Structs 构建数据](ch05-00-structs.md)

  - [定义和实例 struct](ch05-01-defining-structs.md)
  - [struct 例子](ch05-02-example-structs.md)
  - [方法](ch05-03-method-syntax.md)

- [枚举和模式匹配](ch06-00-enums.md)
  - [定义一个枚举](ch06-01-defining-an-enum.md)
  - [match 流程控制](ch06-02-match.md)
  - [if let 流程控制](ch06-03-if-let.md)

## 基本能力

- [使用 Packages, Crates, and Modules 管理项目](ch07-00-managing-growing-projects-with-packages-crates-and-modules.md)

  - [Packages and Crates](ch07-01-packages-and-crates.md)
  - [使用 Modules 控制 Scope 和 Privacy](ch07-02-defining-modules-to-control-scope-and-privacy.md)
  - [Paths for Referring to an Item in the Module Tree](ch07-03-paths-for-referring-to-an-item-in-the-module-tree.md)
  - [Bringing Paths Into Scope with the `use` Keyword](ch07-04-bringing-paths-into-scope-with-the-use-keyword.md)
  - [Separating Modules into Different Files](ch07-05-separating-modules-into-different-files.md)

- [集合](ch08-00-common-collections.md)

  - [Storing Lists of Values with Vectors](ch08-01-vectors.md)
  - [Storing UTF-8 Encoded Text with Strings](ch08-02-strings.md)
  - [Storing Keys with Associated Values in Hash Maps](ch08-03-hash-maps.md)

- [错误处理](ch09-00-error-handling.md)

  - [Unrecoverable Errors with `panic!`](ch09-01-unrecoverable-errors-with-panic.md)
  - [Recoverable Errors with `Result`](ch09-02-recoverable-errors-with-result.md)
  - [To `panic!` or Not to `panic!`](ch09-03-to-panic-or-not-to-panic.md)

- [泛型, 特化, 生命周期](ch10-00-generics.md)

  - [Generic Data Types](ch10-01-syntax.md)
  - [Traits: Defining Shared Behavior](ch10-02-traits.md)
  - [Validating References with Lifetimes](ch10-03-lifetime-syntax.md)

- [自动化测试](ch11-00-testing.md)

  - [如何写测试用例](ch11-01-writing-tests.md)
  - [执行测试和运行](ch11-02-running-tests.md)
  - [Test Organization](ch11-03-test-organization.md)

- [构建一个命令行程序](ch12-00-an-io-project.md)
  - [获取命令行参数](ch12-01-accepting-command-line-arguments.md)
  - [读取一个文件](ch12-02-reading-a-file.md)
  - [Refactoring to Improve Modularity and Error Handling](ch12-03-improving-error-handling-and-modularity.md)
  - [Developing the Library’s Functionality with Test Driven Development](ch12-04-testing-the-librarys-functionality.md)
  - [Working with Environment Variables](ch12-05-working-with-environment-variables.md)
  - [Writing Error Messages to Standard Error Instead of Standard Output](ch12-06-writing-to-stderr-instead-of-stdout.md)

## 使用 rust 思考

- [函数式语言特性: 迭代和闭包](ch13-00-functional-features.md)

  - [Closures: Anonymous Functions that Capture Their Environment](ch13-01-closures.md)
  - [Processing a Series of Items with Iterators](ch13-02-iterators.md)
  - [Improving Our I/O Project](ch13-03-improving-our-io-project.md)
  - [Comparing Performance: Loops vs. Iterators](ch13-04-performance.md)

- [更多的 Cargo 和 Crates.io](ch14-00-more-about-cargo.md)

  - [Customizing Builds with Release Profiles](ch14-01-release-profiles.md)
  - [Publishing a Crate to Crates.io](ch14-02-publishing-to-crates-io.md)
  - [Cargo Workspaces](ch14-03-cargo-workspaces.md)
  - [Installing Binaries from Crates.io with `cargo install`](ch14-04-installing-binaries.md)
  - [Extending Cargo with Custom Commands](ch14-05-extending-cargo.md)

- [智能指针](ch15-00-smart-pointers.md)

  - [Using `Box<T>` to Point to Data on the Heap](ch15-01-box.md)
  - [Treating Smart Pointers Like Regular References with the `Deref` Trait](ch15-02-deref.md)
  - [Running Code on Cleanup with the `Drop` Trait](ch15-03-drop.md)
  - [`Rc<T>`, the Reference Counted Smart Pointer](ch15-04-rc.md)
  - [`RefCell<T>` and the Interior Mutability Pattern](ch15-05-interior-mutability.md)
  - [Reference Cycles Can Leak Memory](ch15-06-reference-cycles.md)

- [并发](ch16-00-concurrency.md)

  - [使用线程同时运行代码](ch16-01-threads.md)
  - [线程之间传输数据](ch16-02-message-passing.md)
  - [共享并发状态](ch16-03-shared-state.md)
  - [使用 `Sync` 和 `Send` 扩展并发](ch16-04-extensible-concurrency-sync-and-send.md)

- [面向对象](ch17-00-oop.md)
  - [Characteristics of Object-Oriented Languages](ch17-01-what-is-oo.md)
  - [Using Trait Objects That Allow for Values of Different Types](ch17-02-trait-objects.md)
  - [Implementing an Object-Oriented Design Pattern](ch17-03-oo-design-patterns.md)

## 高级

- [模式匹配](ch18-00-patterns.md)

  - [使用模式匹配](ch18-01-all-the-places-for-patterns.md)
  - [处理无法匹配的情况](ch18-02-refutability.md)
  - [模式符号](ch18-03-pattern-syntax.md)

- [高级特性](ch19-00-advanced-features.md)

  - [高级 rust](ch19-01-unsafe-rust.md)
  - [高级特化](ch19-03-advanced-traits.md)
  - [高级类型](ch19-04-advanced-types.md)
  - [高级函数编程和闭包](ch19-05-advanced-functions-and-closures.md)
  - [宏](ch19-06-macros.md)

- [构建多线程 web 服务器](ch20-00-final-project-a-web-server.md)

  - [构建一个单线程 web 服务器](ch20-01-single-threaded.md)
  - [改造成多线程服务器](ch20-02-multithreaded.md)
  - [优雅退出](ch20-03-graceful-shutdown-and-cleanup.md)

- [附录](appendix-00.md)
  - [A - 关键字](appendix-01-keywords.md)
  - [B - 操作符和符号](appendix-02-operators.md)
  - [C - 特化衍生](appendix-03-derivable-traits.md)
  - [D - 有用的开发工具](appendix-04-useful-development-tools.md)
  - [E - 版次](appendix-05-editions.md)
  - [F - 翻译](appendix-06-translation.md)
  - [G - 每日构建版本](appendix-07-nightly-rust.md)
