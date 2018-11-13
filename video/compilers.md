# Compiler optimization
## What else has my compiler done for me lately?

*Matt Godbolt* @ C++Now (2018)

> We've given Matt four day's notice to tell us what his compiler has done for him since his [CppCon 2017 Keynote](https://cppcon2017.sched.com/event/BguG/unbolting-the-compilers-lid-what-has-my-compiler-done-for-me-lately).

[Watch at YouTube](https://www.youtube.com/watch?v=nAbCKa0FzjQ)

[See more details](https://cppnow2018.sched.com/event/EilZ/what-else-has-my-compiler-done-for-me-lately)

## What has my compiler done for me lately? Unbolting the compiler's lid

*Matt Godbolt* @ CppCon (2017)

> In 2012, Matt and a colleague were arguing whether it was efficient to use the then-new-fangled range for. During the discussion a bash script was written to quickly compile C++ source and dump the assembly. Five years later and that script has grown into a website relied on by many to quickly see the code their compiler emits, to compare different compilers' code generation and behaviour, to quickly prototype and share code, and investigate the effect of optimization flags. In this talk Matt will not only show you how easy (and fun!) it is to understand the assembly code generated by your compiler, but also how important it can be. He'll explain how he uses Compiler Explorer in his day job programming low-latency trading systems, and show some real-world examples. He'll demystify assembly code and give you the tools to understand and appreciate how hard your compiler works for you. He'll also talk a little about how Compiler Explorer works behind the scenes, how it is maintained and deployed, and  share some stories about how it has changed over the years. By the end of this session you'll be itching to take your favourite code snippets and start exploring what your compiler does with them.

[Watch at YouTube](https://www.youtube.com/watch?v=bSkpMdDe4g4)

[See more details](https://cppcon2017.sched.com/event/BguG/unbolting-the-compilers-lid-what-has-my-compiler-done-for-me-lately)

## C++ costless abstractions: the compiler view

*Serge Guelton* @ CppCon (2016)

> One of the motto of C++ is "costless abstractions", a.k.a. you only pay for what you use. To achieve this goal, modern C++ puts a heavy burden on the compiler. But what does the compiler really does when it meets an exception? When it finds a nested lambda? When it encounters a structure that wraps a single scalar? During this talk, we'll go trough a set of innocent C++ sample that involves several data types and algorithms from the standard library, and verify that the costless abstraction principle holds, especially when looking at the difference between several optimization level, eventually digging into specific compiler optimization to understand what happens under the hood. This talk uses Clang++ as the reference compiler, and relies on its LLVM bitcode output to explain how the abstractions are lowered (or completely pruned) at the Intermediate Representation level.

[Watch at YouTube](https://www.youtube.com/watch?v=q0N9Tvf7Bz0)

[See more details](https://cppcon2016.sched.com/event/7nLK/c-costless-abstractions-the-compiler-view)

## Understanding compiler optimization

*Chandler Carruth* @ code::dive (2016)

> C++ is used in applications where resources are constrained and performance is critical. However, its power in this domain comes from the ability to build large, complex systems in C++. These systems leverage numerous C++ features in order to build and utilize abstractions that make reasoning about these complex systems possible. Abstractions are the very essence of how we scale software to solve ever larger and more complex problems.

[Watch at YouTube](https://www.youtube.com/watch?v=haQ2cijhvhE)

[See more details](http://codedive.pl/index/speaker/name/chandler-carruth/year/2016/)
