---
description: "Learn more about: Fatal Error C1002"
title: "Fatal Error C1002"
ms.date: "11/04/2016"
f1_keywords: ["C1002"]
helpviewer_keywords: ["C1002"]
ms.assetid: bd6d274a-c7b4-43af-8bf2-23c5e442aa22
---
# Fatal Error C1002

compiler is out of heap space in pass 2

The compiler ran out of dynamic memory space during its second pass, probably due to a program with too many symbols or complex expressions.

### To fix by using the following possible solutions

1. Divide the source file into several smaller files.

1. Break expressions into smaller subexpressions.

1. Remove other programs or drivers that consume memory.

1. If you are compiling on a 64-bit platform, use the 64-bit compiler toolset. For information, see [How to: Enable a 64-Bit Visual C++ Toolset on the Command Line](../../build/how-to-enable-a-64-bit-visual-cpp-toolset-on-the-command-line.md).
