[![Build Status](https://travis-ci.org/sger/RustBooks.svg?branch=master)](https://travis-ci.org/sger/RustBooks)

Rust Books
====
* [Books](#books)
 * [Starter Books](#starter-books)
 * [Advanced Books](#advanced-books)
* [Resources](#resources)

**Books**
====

**Starter Books**
----

### [The Rust Programming Language](https://doc.rust-lang.org/book/) *Free*

Welcome! This book will teach you about the Rust Programming Language. Rust is a systems programming language focused on three goals: safety, speed, and concurrency. It maintains these goals without having a garbage collector, making it a useful language for a number of use cases other languages aren’t good at: embedding in other languages, programs with specific space and time requirements, and writing low-level code, like device drivers and operating systems. It improves on current languages targeting this space by having a number of compile-time safety checks that produce no runtime overhead, while eliminating all data races. Rust also aims to achieve ‘zero-cost abstractions’ even though some of these abstractions feel like those of a high-level language. Even then, Rust still allows precise control like a low-level language would.

### [Welcome to Rust-101](https://www.ralfj.de/projects/rust-101/main.html) *Free*

This is Rust-101, a small tutorial for the Rust language. It is intended to be an interactive, hands-on course: I believe the only way to really learn a language is to write code in it, so you should be coding during the course.
If you have any questions that are not answered here, check out the "Additional Resources" below. In particular, the IRC channel is filled with awesome people willing to help you! I spent lots of time there ;-)
I will assume some familiarity with programming, and hence not explain the basic concepts common to most languages. Instead, I will focus on what makes Rust special.

### [Rust by Example](http://rustbyexample.com/) *Free*

Rust by Example (RBE) is a collection of runnable examples that illustrate various Rust concepts and standard libraries. To get even more out of these examples, don't forget to [install Rust locally](http://www.rust-lang.org/install.html) and check out the [official docs](http://doc.rust-lang.org/std/). Additionally for the curious, you can also [check out the source code for this site](https://github.com/rust-lang/rust-by-example).

### [Why Rust?](http://www.oreilly.com/programming/free/why-rust.csp)

<img src="http://covers.oreillystatic.com/images/0636920040446/cat.gif" width="120px"/>

While systems programming languages have greatly evolved since the introduction of C more than 40 years ago, our capacity for dumb mistakes with enormous consequences has remained unchanged, with vivid examples regularly in the news. This O'Reilly report examines Rust, a new systems programming language that combines safety and security with performance on a par with C and C++.

### [Learning Rust](https://www.packtpub.com/application-development/learning-rust)

<img src="https://dz13w8afd47il.cloudfront.net/sites/default/files/imagecache/ppv4_main_book_cover/B05114.png" width="120px"/>

Rust is a highly concurrent and high performance language that focuses on safety and speed, memory management, and writing clean code. It also guarantees thread safety, and its aim is to improve the performance of existing applications. It has been backed by Mozilla to solve the critical problem of concurrency.

### [Beginning Rust - From Novice to Professional](https://www.apress.com/us/book/9781484234679) 

<img src="https://images.springer.com/sgw/books/medium/9781484234679.jpg" width="120px"/>

Learn to program with Rust in an easy, step-by-step manner on Unix, Linux shell, macOS and the Windows command line.  As you read this book, you’ll build on the knowledge you gained in previous chapters and see what Rust has to offer.  

Beginning Rust starts with the basics of Rust, including how to name objects, control execution flow, and handle primitive types. You’ll see how to do arithmetic, allocate memory, use iterators, and handle input/output. Once you have mastered these core skills, you’ll work on handling errors and using the object-oriented features of Rust to build robust Rust applications in no time.

Only a basic knowledge of programming is required, preferably in C or C++. To understand this book, it's enough to know what integers and floating-point numbers are, and to distinguish identifiers from string literals.

### [Rust Cookbook](https://www.packtpub.com/application-development/rust-cookbook) 

<img src="https://d1ldz4te4covpm.cloudfront.net/sites/default/files/imagecache/ppv4_main_book_cover/9781785880254.png" width="120px"/>

This book will help you understand the core concepts of the Rust language, enabling you to develop efficient and high-performance applications by incorporating features such as zero cost abstraction and better memory management.Delve into advanced-level concepts such as error handling, macros, crates, and parallelism in Rust. Toward the end of the book, learn how to create HTTP servers and web services, building a strong foundational knowledge in server-side programming and enabling to deliver solutions to build high-performance and safer production-level web applications and services using Rust.

### [Rust Standard Library Cookbook](https://www.packtpub.com/application-development/rust-standard-library-cookbook)

<img src="https://www.packtpub.com/sites/default/files/B09027.png" width="120px"/>

Mozilla’s Rust is gaining much attention with amazing features and a powerful library. This book will take you through varied recipes to teach you how to leverage the Standard library to implement efficient solutions.

The book begins with a brief look at the basic modules of the Standard library and collections. From here, the recipes will cover packages that support file/directory handling and interaction through parsing. You will learn about packages related to advanced data structures, error handling, and networking. You will also learn to work with futures and experimental nightly features. The book also covers the most relevant external crates in Rust.

### [Network Programming with Rust](https://www.packtpub.com/application-development/network-programming-rust)

<img src="https://www.packtpub.com/sites/default/files/B09152_Cover.png" width="120px">

Rust is low-level enough to provide fine-grained control over memory while providing safety through compile-time validation. This makes it uniquely suitable for writing low-level networking applications.

This book is divided into three main parts that will take you on an exciting journey of building a fully functional web server. The book starts with a solid introduction to Rust and essential networking concepts. This will lay a foundation for, and set the tone of, the entire book. In the second part, we will take an in-depth look at using Rust for networking software. From client-server networking using sockets to IPv4/v6, DNS, TCP, UDP, you will also learn about serializing and deserializing data using serde. The book shows how to communicate with REST servers over HTTP. The final part of the book discusses asynchronous network programming using the Tokio stack. Given the importance of security for modern systems, you will see how Rust supports common primitives such as TLS and public-key cryptography.

### [Rust Programming by Example](https://www.packtpub.com/application-development/rust-programming-example)

<img src="https://www.packtpub.com/sites/default/files/B08821_cover.png" width="120px"/>

Beginning with an introduction to Rust, you’ll learn the basic aspects such as its syntax, data types, functions, generics, control flows, and more. After this, you’ll jump straight into building your first project, a Tetris game. Next you’ll build a graphical music player and work with fast, reliable networking software using Tokio, the scalable and productive asynchronous IO Rust library.

Over the course of this book, you’ll explore various features of Rust Programming including its SDL features, event loop, File I/O, and the famous GTK+ widget toolkit. Through these projects, you’ll see how well Rust performs in terms of concurrency—including parallelism, reliability, improved performance, generics, macros, and thread safety. We’ll also cover some asynchronous and reactive programming aspects of Rust.

**Advanced Books**
---

### [The Rustonomicon](https://doc.rust-lang.org/nightly/nomicon/)

This book digs into all the awful details that are necessary to understand in order to write correct Unsafe Rust programs. Due to the nature of this problem, it may lead to unleashing untold horrors that shatter your psyche into a billion infinitesimal fragments of despair.

Should you wish a long and happy career of writing Rust programs, you should turn back now and forget you ever saw this book. It is not necessary. However if you intend to write unsafe code -- or just want to dig into the guts of the language -- this book contains invaluable information.

### [Programming Rust](http://shop.oreilly.com/product/0636920040385.do)

<img src="http://akamaicovers.oreilly.com/images/0636920040385/rc_cat.gif" width="120px"/>

This practical book introduces systems programmers to Rust, the new and cutting-edge language. You’ll learn how Rust offers the rare and valuable combination of statically verified memory safety and low-level control—imagine C++, but without dangling pointers, null pointer dereferences, leaks, or buffer overruns.

### [Mastering Rust](https://www.packtpub.com/application-development/mastering-rust)

<img src="https://dz13w8afd47il.cloudfront.net/sites/default/files/imagecache/ppv4_main_book_cover/B05023.png" width="120px"/>

If concurrent programs are giving you sleepless nights, Rust is your go-to language. Filled with real-world examples and explanations, this book will show you how you can build scalable and reliable programs for your organization.

We’ll teach you big level concepts that make Rust a great language. Improving performance, using generics, building macros, and working with threads are just some of the topics we’ll cover. We’ll talk about the official toolsets and ways to discover more. The book contains a mix of theory interspersed with hands-on tasks so you acquire the skills as well as the knowledge. Since programming cannot be learned by just reading, we provide exercises (and solutions) to hammer the concepts in.

### [The Rust Programming Language](https://www.nostarch.com/Rust)

<img src="https://www.nostarch.com/sites/default/files/styles/uc_product/public/RustProgrammingLanguage_cover_0.png" width="120px"/>

The Rust Programming Language is the official book on Rust; a community-developed, systems programming language that runs blazingly fast, prevents segfaults, and guarantees thread safety. Rust’s memory safety guarantees, enforced at compile time, safeguard your programs against the many problems that pervade other systems languages. Rust offers the control and performance of a low-level language with the helpful abstractions of a high level one, and does this all without having a garbage collector. These characteristics make Rust useful for embedding in other languages, programs with specific space and time requirements, and writing low-level code, like device drivers and operating systems.

### [Rust Essentials - Second Edition](https://www.packtpub.com/application-development/rust-essentials-second-edition) 

<img src="https://d1ldz4te4covpm.cloudfront.net/sites/default/files/imagecache/ppv4_main_book_cover/B08304%20_cover.png" width="120px"/>

This book starts off with an argumentation of Rust's unique place in today's landscape of programming languages. Install Rust and learn how to work with its package manager Cargo. The various concepts are introduced step by step: variables, types, functions, and control structures to lay the groundwork. Then explore more structured data such as strings, arrays, and enums, and see how pattern matching works.

Throughout all this, this book lays emphasis on the unique ways of reasoning that the Rust compiler uses to produce safe code. Next look at Rust's specific way of error handling, and the overall importance of traits in Rust code. The pillar of memory safety is treated in depth as we explore the various pointer kinds. Next, see how macros can simplify code generation, and how to compose bigger projects with modules and crates. Finally, discover how we can write safe concurrent code in Rust and interface with C programs, get a view of the Rust ecosystem, and explore the use of the standard library.

### [Hands-On Concurrency with Rust](https://www.packtpub.com/application-development/hands-concurrency-rust)

<img src="https://www.packtpub.com/sites/default/files/B08865_cover.png" width="120px"/>

This book will teach you to how to manage program performance on modern machines and build fast, memory-safe, and concurrent software in Rust. It starts with the fundamentals of Rust and discusses machine architecture concepts. You will be taken through ways to measure and improve the performance of Rust code systematically and how to write collections with confidence. You will learn about the Sync and Send traits applied to threads, and coordinate thread execution with locks, atomic primitives, data-parallelism, and more.

The book will show you how to efficiently embed Rust in C++ code and explore the functionalities of various crates for multithreaded applications. It explores implementations in depth. You will know how a mutex works and build several yourself. You will master radically different approaches that exist in the ecosystem for structuring and managing high-scale systems.

### [Hands-On Functional Programming in Rust](https://www.packtpub.com/application-development/hands-functional-programming-rust)

<img src="https://www.packtpub.com/sites/default/files/B09736.png" width="120PX"/>

Functional Programming allows developers to divide programs into smaller, reusable components that ease the creation, testing, and maintenance of software as a whole. Combined with the power of Rust, you can develop robust and scalable applications that fulfill modern day software requirements. This book will help you discover all the Rust features that can be used to build software in a functional way.

We begin with a brief comparison of the functional and object-oriented approach to different problems and patterns. We then quickly look at the patterns of control flow, data the abstractions of these unique to Functional Programming. The next part covers how to create functional apps in Rust; mutability and ownership, which are exclusive to Rust, are also discussed. Pure functions are examined next and you'll master closures, their various types, and currying. We also look at implementing concurrency through functional design principles and metaprogramming using macros. Finally, we look at best practices for debugging and optimization.

By the end of the book, you will be familiar with the functional approach of programming and will be able to use these techniques on a daily basis.

### [Rust High Performance](https://www.packtpub.com/application-development/rust-high-performance)

<img src="https://www.packtpub.com/sites/default/files/B08822_cover.png" width="120px"/>

At times, it is difficult to get the best performance out of Rust. This book teaches you to optimize the speed of your Rust code to the level of languages such as C/C++. You'll understand and fix common pitfalls, learn how to improve your productivity by using metaprogramming, and speed up your code by concurrently executing parts of it safely and easily. You will master the features of the language which will make you stand out and use them to really improve the efficiency of your algorithms

The book begins with a gentle introduction to help you identify bottlenecks when programming in Rust. We highlight common performance pitfalls, along with strategies to detect and resolve these issues early. We move on to mastering Rust's type system, which will enable us to create impressive optimizations in both performance and safety at compile time. You will then learn how to effectively manage memory in Rust, mastering the borrow checker. We move on to measuring performance and you will see how this affects the way you write code. Moving ahead, you will perform metaprogramming in Rust to boost the performance of your code and your productivity. You will finally learn parallel programming in Rust, which enables efficient and faster execution by using multithreading and asynchronous programming.

**Resources**
====

### [Learn Rust with examples](https://github.com/rust-lang/rust-by-example)

### [The Rust Programming Language](https://www.youtube.com/watch?v=d1uraoHM8Gg)

### [Are We Learning Yet?](http://www.arewelearningyet.com/): List of resources for machine learning in Rust

### [Are We Web Yet?](http://www.arewewebyet.org/): List of resources for web development in Rust

Contributing
====
Your contributions are always welcome, just follow [the rules](https://github.com/sger/RustBooks/blob/master/CONTRIBUTING.md)!

License
====
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://licensebuttons.net/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
