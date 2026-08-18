# C++ Programming Journey

这是我的 C++ 学习仓库，用来持续记录从基础语法到数据结构、算法与项目实践的成长过程。

- 开始时间：2026 年 8 月
- 当前阶段：基础语法与控制流程
- 学习原则：只提交真正学过、运行过、理解过的代码

## Repository structure

```text
GitPractice
├── 01-basics
│   ├── hello-world.cpp
│   ├── input-output.cpp
│   └── git-greeting.cpp
├── 02-control-flow
│   └── for-loop.cpp
├── LEARNING_LOG.md
├── .gitignore
└── README.md
```

仓库只创建已经开始学习的章节，不提前堆放空目录。后续会随着学习进度逐步加入函数、数组、指针、类、标准模板库和算法练习。

## Progress

- [x] Hello, World
- [x] 标准输入与输出
- [x] `for` 循环
- [x] Git 基础工作流
- [ ] 函数
- [ ] 数组与字符串
- [ ] 指针与引用
- [ ] 类与对象
- [ ] STL（Standard Template Library）

## Compile and run

在 Windows PowerShell 中进入示例所在目录，然后使用：

```powershell
g++ hello-world.cpp -o hello-world -Wall -Wextra -std=c++17
.\hello-world.exe
```

编译得到的 `.exe` 文件不会提交到 GitHub。

## Commit style

每完成一个知识点或一组完整练习再提交，提交信息说明实际完成的内容，例如：

```text
Add basic input and output exercises
Practice for loops
Implement first array exercises
```

这个仓库保留真实的学习节奏，不为了提交数量制造无意义记录。
