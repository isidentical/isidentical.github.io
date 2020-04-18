# Batuhan Taskaya's Resume

### About

Highschool student. Python developer, for 6 years. Member of Python Triage Team. Contributing to the upstream CPython, parser and compiler itself. Especially the AST. Author of InspectorTiger and many AST-based static analyze tools. Researching on parsing methodologies and implementations. Experienced in C, C-extensions for Python and C development in different architectures. PyCon Turkey speaker committee member. Enthusiastic and curious about the operating systems that aren't counted as "major" thanks to being a GCC compile farm user.

I'm close to graduating from high school \(2021, june\) and I am looking for international scholarships and grants for universities that are in the USA / Canada / Europe.

I have also limited \(very limited\) free time for freelance offers. If you are willing to sponsor some work to a F/OSS project that is with in my area area of interest \(AST, parsing, static analyzing\), there is no technical time limit except the school period \(I like to spend my time in that area, it is why I am restricting myself from closed source freelance work\).

### F/OSS Life

I'm trying to work on open source full time \(except the school period\), especially on the CPython project. But I have a various of contributions to other projects such as Astor, Django, Setuptools, Pyflakes, Pegen, RustPython, Unimport, Werkzeug and many more small contribution.

### My Own F/OSS Projects

[Inspector Tiger](https://github.com/thg-consulting/it) is a code review framework and an embedded linter. It comes with a series of built-in handlers \(like finding yield statements that can be replaced with yield from\). But the real aim is using its framework side, developing codebase-specific plugins.

[Arkh](https://github.com/isidentical/arkhe) is an universal, register based virtual machine / bytecode interpreter. Simple but powerful instructions. Builtin debugger and a text formatted language.

[Swinging Head Languag](https://github.com/isidentical/swinginghead) is an esoteric language that is based a top of LLVM and can be directly binded into python.

[Bicycle Repair Man](https://github.com/isidentical/BRM) is a python source rewriting library with the freedom people are looking for. It gives people a chance to intervene lexing before any tree-like structre constructed. Users are free to do anything; change already constructed tokens with matching them according to created patterns, put new tokens and modify the lexer rules, refactor tons of python files without losing any information \(full roundtripability\).

[PEPGrave](https://github.com/isidentical/pepgrave) is a fun project that tried to implemented rejected language changes \(PEPs\) with doing runtime source transformations, object patchings etc just for fun.[PySandbox](https://github.com/isidentical/pysandbox)

[PySandbox ](https://github.com/isidentical/PySandbox)offers a way to safely execute / evaluate arbitrary python code on containers with a programmatic approach. 



There are many more projects in [my github](https://github.com/isidentical) and [my personal archive](https://github.com/isidentical-archive). 



### Talks

### [Memory Management in CPython](https://speakerdeck.com/isidentical/memory-management-in-python) \(FOSDEM'19\)

What is an object, how cpython stores objects in memory, allocation of memory, deallocation and garbage collection, edge cases like small int caching or string interning, how to handle memory leaks with tracemaloc[ ](https://speakerdeck.com/isidentical/hack-the-cpython)

### [Hack the CPython Interpreter](https://speakerdeck.com/isidentical/hack-the-cpython) \(EuroPython'20\)

How a python code get executed, which steps you can manipulate, add a new syntax add runtime, modify the behaviour of python, optimize bytecode

### [LLVM & Python](https://fosdem.org/2020/schedule/event/llvm_python/) \(FOSDEM'20\)

History of LLVM and Python, how CPython tried to use LLVM and failed, how some external companies tried to integrate python with llvm and some other jit engines, what are the current state of these technologies, how can you write your own JIT compiler for python with llvm



