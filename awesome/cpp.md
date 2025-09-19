# Awesome C++ list

This document lists various softwares and resources related to the
C++ programming language I have found useful.

## Table of Contents

- [Softwares](#softwares)
    - [Tools](#tools)
    - [Libraries](#libraries)
- [Resources](#resources)
    - [Community](#community)
    - [Articles](#articles)
    - [Books](#books)
    - [Guidelines](#guidelines)
    - [Podcasts](#podcasts)
    - [Talks](#talks)
- [Other Lists](#other-lists)

## Softwares

Software and tools related to the use of the C++ programming language.

### Tools

- [GNU C++ Compiler](https://gcc.gnu.org/): the Libre GNU compiler front-end for C++.
- [LLVM Clang](https://clang.llvm.org/): a C++ front-end for the LLVM compiler infrastructure.
- [Green Hills Optimizing Compilers](https://ghs.com/products/compiler.html): fast and reliable C++ compiler trusted in safety-critical industries.
- [Visual C++](https://visualstudio.microsoft.com/vs/features/cplusplus/): Microsoft's C++ compiler.
- [Intel® oneAPI DPC++/C++ Compiler](https://www.intel.com/content/www/us/en/developer/tools/oneapi/dpc-compiler.html): Intel's C++ compiler.
- [NVIDIA HPC Compilers](https://www.intel.com/content/www/us/en/developer/tools/oneapi/dpc-compiler.html): NVIDIA's C++ compiler.
- [Arm C++ Compiler](https://www.arm.com/products/development-tools/embedded-and-software/c-cpp-compilers): Arm's C++ compiler and optimized libraries for Arm-powered systems.
- [Compiler Explorer](https://godbolt.org/): on-line exploration of various compilers' outputs and behaviours.
- [clang-tidy](https://clang.llvm.org/extra/clang-tidy/): Clang-based source code linter.
- [clang-format](https://clang.llvm.org/docs/ClangFormat.html): Clang-based automatic code formatter.
- [clangd](https://clangd.llvm.org/): Clang-based code completion system with LSP.
- [American Fuzzy Lop](https://lcamtuf.coredump.cx/afl/): industry-standard fuzzer.
- [Bazel](https://bazel.build/): performant and distributed polyglot build system.
- [vcpkg](https://vcpkg.io/en/): C++ package manager supported by Microsoft.
- [Clang Static Analyzer](https://clang.llvm.org/docs/ClangStaticAnalyzer.html): Clang-based Static Analyzer using symbolic execution.
- [ASan, TSan, MSan](https://github.com/google/sanitizers): Memory and multi-threading compiler instrumentation modules.
- [Astrée](https://www.absint.com/astree/index.htm): Static analyzer for safety-critical computer systems.
- [RuleChecker](https://www.absint.com/rulechecker/index.htm): automated compliance checker for MISRA or CERT.

### Libraries

- [libstd++](https://gcc.gnu.org/onlinedocs/libstdc++/manual/): GNU's implementation of the ISO C++ Standard Library.
- [libc++](https://libcxx.llvm.org/): an implementation of the C++ standard library as part of LLVM.
- [libc++abi](https://libcxxabi.llvm.org/): a low-level layer for C++ standard library implementations.
- [libcu++](https://docs.nvidia.com/cuda/cuda-c-std/index.html): NVIDIA's implementation of the C++ Standard Library for use with CUDA-powered graphic cards.
- [Guidelines Support Library](https://github.com/Microsoft/GSL): Microsoft's implementation of the support library for the C++ Core Guidelines.
- [GoogleTest](https://github.com/google/googletest): Google's testing and mocking framework.
- [Folly](https://github.com/facebook/folly): Meta's core C++ library.
- [Abseil](https://abseil.io/): Google's open-source collection of C++ libraries.
- [Boost](https://www.boost.org/): open-source, peer-reviewed, portable and free C++ libraries.
- [EASTL](https://github.com/electronicarts/EASTL): Electronic Arts' collection of data structures and algorithms in C++.
- [POCO C++](https://pocoproject.org/): networking and Internet-working library for mission-critical IoT devices.
- [Thrust](https://nvidia.github.io/cccl/thrust/index.html): NVIDIA's introduction of parallel algorithms within the C++ standard library.
- [Cap'n Proto](https://capnproto.org/): fast and efficient interchange format and RPC system.
- [AOCL](https://www.amd.com/en/developer/aocl.html): numerical libraries for optimized operations on AMD processors.
- [NamedType](https://github.com/joboccara/NamedType): implementation of strong types in C++.
- [integers](https://github.com/google/integers): safer integers in C++.
- [Highway](https://github.com/google/highway): performance-portable, length-agnostic SIMD with runtime dispatch.
- [type_safe](https://github.com/foonathan/type_safe): zero overhead utilities for preventing bugs at compile time.

## Resources

Non-software technical resources about the C++ programming language.

### Community

- [Standard C++](https://isocpp.org/): Latest news about the ISO C++ standard.
- [cppstat](https://cppstat.dev/): status report for the support of C++ features within compilers.
- [cppreference.com](https://cppreference.com/): community-maintained documentation for the C++ standard library and compilers support.
- [CppCon](https://cppcon.org/): *The* C++ Conference.
- [code::dive](https://codedive.pl/): a high-ranked programming conference with a focus on C++.
- [C++ on Sea](https://cpponsea.uk/): an international C++ conference from the UK.
- [ACCU](https://accuconference.org/): the longest developer conference still in activity, with a particular interest for C and C++.
- [NDC {TechTown}](https://ndctechtown.com/): a software conference for embedded systems programming.
- [C++ Russia](https://cppconf.ru/): the Russian-speaking world's C++ conference.
- [CppNorth](https://cppnorth.ca/): the Canadian C++ conference.
- [Meeting Cpp](https://www.youtube.com/user/MeetingCPP/): independent platform for C++ voices.
- [quick-bench](https://quick-bench.com/): quick on-line C++ benchmarking.

### Articles

- [C++ Standard Committee Papers](https://www.open-std.org/jtc1/sc22/wg21/docs/papers/), multiple authors.
- [Strongly typed constructors](https://www.fluentcpp.com/2016/12/05/named-constructors/), Jonathan Boccara.
- [Strong types for strong interfaces](https://www.fluentcpp.com/2016/12/08/strong-types-for-strong-interfaces/), Jonathan Boccara.
- [Passing strong types by reference](https://www.fluentcpp.com/2017/03/06/passing-strong-types-reference-revisited/), Jonathan Boccara.
- [Strong lambdas: strong typing over generic types](https://www.fluentcpp.com/2017/02/20/strong-lambdas-strong-generic-types/), Jonathan Boccara.
- [Good news: strong types are (mostly) free in C++](https://www.fluentcpp.com/2017/05/05/news-strong-types-are-free/), Jonathan Boccara.
- [Strong types: inheriting the underlying type’s functionalities](https://www.fluentcpp.com/2017/05/23/strong-types-inheriting-functionalities-from-underlying/), Jonathan Boccara.
- [Making Strong Types Hashable](https://www.fluentcpp.com/2017/05/30/implementing-a-hash-function-for-strong-types/), Jonathan Boccara.
- [Strong Units Conversions](https://www.fluentcpp.com/2017/05/26/strong-types-conversions/), Jonathan Boccara.
- [Metaclasses, the Ultimate Answer to Strong Typing in C++?](https://www.fluentcpp.com/2017/08/08/metaclasses-ultimate-answer-strong-typing-c/), Jonathan Boccara.
- [Calling Functions and Methods on Strong Types](https://www.fluentcpp.com/2017/11/07/calling-functions-methods-strong-types/), Jonathan Boccara.
- [Using Strong Types to Return Multiple Values](https://www.fluentcpp.com/2017/11/10/strong-types-multiple-return-values/), Jonathan Boccara.
- [Making Strong Types Implicitly Convertible](https://www.fluentcpp.com/2018/01/05/making-strong-types-implicitly-convertible/), Jonathan Boccara.
- [Strong Templates](https://www.fluentcpp.com/2018/01/09/strong-templates/), Jonathan Boccara.
- [Strong Optionals](https://www.fluentcpp.com/2018/01/16/strong-optionals/), Jonathan Boccara.

### Books

- [A Tour of C++ (Second edition)](https://www.stroustrup.com/tour2.html), Bjarne Stroustrup.
- [The C++ Programming Language (4th Edition)](https://www.stroustrup.com/4th.html), Bjarne Stroustrup.
- [Effective Modern C++](https://www.oreilly.com/library/view/effective-modern-c/9781491908419/), Scott Meyers.
- [Effective STL](https://www.oreilly.com/library/view/effective-stl/9780321545183/), Scott Meyers.
- [C++ Concurrency in Action: Practical Multithreading](https://www.cplusplusconcurrencyinaction.com/), Anthony Williams.
- [Working Draft Programming Language - C++](https://eel.is/c++draft/), ISO C++ WG.
- [Optimizing software in C++: An optimization guide for Windows, Linux and Mac platforms](https://www.agner.org/optimize/optimizing_cpp.pdf), Agner Fog.
- [Optimizing subroutines in assembly language: An optimization guide for x86 platforms](https://www.agner.org/optimize/optimizing_assembly.pdf), Agner Fog.
- [The microarchitecture of Intel, AMD and VIA CPUs: An optimization guide for assembly programmers and compiler makers](https://www.agner.org/optimize/microarchitecture.pdf), Agner Fog.
- [Instruction tables: Lists of instruction latencies, throughputs and micro-operation breakdowns for Intel, AMD and VIA CPUs](https://www.agner.org/optimize/instruction_tables.pdf), Agner Fog.
- [Calling conventions for different C++ compilers and operating systems](https://www.agner.org/optimize/calling_conventions.pdf), Agner Fog.

### Guidelines

- [C++ Core Guidelines](https://isocpp.github.io/CppCoreGuidelines/): collaborative guidelines from the C++ community.
- [JSF++](https://www.stroustrup.com/JSF-AV-rules.pdf): Lockheed Martin's direction and guidance for writing error-free air vehicle systems.
- [SEI CERT C++ Coding Standard](https://wiki.sei.cmu.edu/confluence/display/cplusplus): rules for secure coding in the C++ programming language.
- [MISRA C++](https://misra.org.uk/misra-c-plus-plus/): guidelines for the use of C++ in the automobile industry.
- [C++ Do's and Don'ts](https://chromium.googlesource.com/chromium/src/+/HEAD/styleguide/c++/c++-dos-and-donts.md): advices for writing C++ in the large Chromium codebase. 
- [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html): Google's guidelines for writing C++.
- [LLVM C++ Style Guide](https://llvm.org/docs/CodingStandards.html): style guide for contributing C++ code to LLVM.
- [BDE C++ Coding Standards](https://bloomberg.github.io/bde/knowledge_base/coding_standards.html): strict but well-thoughts rules for writing C++ at Bloomberg.

### Talks

- [Correct by Construction: APIs That Are Easy to Use and Hard to Misuse](https://www.youtube.com/watch?v=nLSm3Haxz0I), Matt Godbolt, C++ on Sea: a demonstration of C++ capabilities to write safer C++ code.
- [Data-Oriented Design and C++](https://www.youtube.com/watch?v=rX0ItVEVjHc), Mike Acton, CppCon: the classic talk about writing software with performance in mind.
- [The Essence of C++](https://www.youtube.com/watch?v=86xWVb4XIyE), Bjarne Stroustrup: a glimpse into the future of Modern C++.
- [C++ Exceptions for Smaller Firmware](https://www.youtube.com/watch?v=bY2FlayomlE), Khalil Estell, CppCon: using C++ exceptions to reduce an executable's size.
- [Contemporary C++ in Action](https://www.youtube.com/watch?v=yUIFdL3D0Vk), Daniela Engert, CppCon: practical illustration of modern C++ features.
- [Secure development with C++ - Lessons and techniques](https://www.youtube.com/watch?v=U2CIi-CyGY4) Helge Penne, NDC TechTown: lessons and tips for writing secure C++ from experts at Thalès.
- [Garbage In, Garbage Out: Arguing about Undefined Behavior with Nasal Demons](https://www.youtube.com/watch?v=yG1OZ69H_-o), Chandler Carruth, CppCon: the sad reality of UB in ISO C++ and how to deal with them from the perspective of a compiler writer.
- [CPU Caches and Why You Care](https://www.youtube.com/watch?v=WDIkqP4JbkE), Scott Meyers, code::dive: a well-explained talk about why cache coherency matters.
- [Writing Fast Code I](https://www.youtube.com/watch?v=vrfYLlR8X8k), Andrei Alexandrescu, code::dive: various tips for making your code faster, for real.
- [Writing Fast Code II](https://www.youtube.com/watch?v=9tvbz8CSI8M), Andrei Alexandrescu, code::dive: the follow-up.
- [Lock-Free Programming (or, Juggling Razor Blades), Part I](https://www.youtube.com/watch?v=c1gO9aB9nbs), Herb Sutter, CppCon 2014: the ideas behind lock-free programming.
- [Lock-Free Programming (or, Juggling Razor Blades), Part II](https://www.youtube.com/watch?v=CmxkPChOcvw), Herb Sutter, CppCon 2014: the follow-up.

## Other Lists

Similar documents listing useful resources related to the C++ programming language.

- [Faraz Fallahi's Awesome C++](https://github.com/fffaraz/awesome-cpp): a curated list of awesome C++ (or C) frameworks, libraries, resources, and shiny things.
- [Erik Rigtorp's Awesome Modern C++](https://awesomecpp.com/): a collection of resources on modern C++.
- [Markus Gans' awesome-cpp](https://github.com/uhub/awesome-cpp): a curated list of awesome C++ frameworks, libraries and software.
- [Danil Sidoruk's C++ conferences](https://github.com/eoan-ermine/cpp-conferences): a catalog of C++ conferences worldwide
