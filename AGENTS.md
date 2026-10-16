# Agent Instructions

The repository is fork from [renesas/cpk_examples: CPK板样例代码 Sample Codes China Promotion Kits](https://github.com/renesas/cpk_examples). Note: absolutely not push to upstream, only push to my repository.

## Rule: Workspace Cleaning

1. All intermediate files generated from PDF, image, and document parsing must be placed in the system temporary directory %TEMP%\codex-artifacts\<task-name>\, unless I explicitly specify a different location.

## Rule: Edit File

1. For the markdown format: there is no need to follow the rule of approximately 80 characters per line.
2. For C/C++ files and makefile files: Macro Name: It should be arranged in the order of the ASCII code table.Unless certain macros should be grouped together in terms of their meaning, for example, some macros are the detailed configurations for the same module's specific functional aspects.

## Build

Almost all project are build with e2 studio, and this IDE doesn't support call in CLI. So when you want to build, just tell the developer to build in IDE, rather than build in CLI by yourself.