[English](./README.md) | 中文

# Swow

[![license][license-badge]][license-link]
[![ci][ci-badge]][ci-link]
[![codecov][codecov-badge]][codecov-link]
[![release][release-badge]][release-link]

> ⚠️ 预览版本, 非生产可用

**Swow是一个使用PHP和C编写的高性能网络通信引擎**

它是长期以来从Swoole项目中获得的宝贵经验的结晶，是次世代的Swoole扩展。

## ⚡️ 特点

+ 主要功能使用PHP实现, 核心部分使用纯C实现
+ 最小核心原则, 为PHP赋能
+ 跨平台, 支持所有主流操作系统
+ 可选的Composer安装
+ 支持主协程, 无需创建协程即可使用
+ 支持协程中断, kill协程等特性
+ 可编程的抢占式协程调度功能
+ 线程安全
+ 支持在所有SAPI下运行
+ 使用异常机制而不是错误码

## 🛠 开发 & 讨论

+ __中文文档__: <https://wiki.s-wow.com> [尚未完成]

[license-badge]: https://img.shields.io/badge/license-apache2-blue.svg
[license-link]: LICENSE
[ci-badge]: https://github.com/swow/swow/workflows/swow/badge.svg
[ci-link]: https://github.com/swow/swow/actions?query=workflow:swow
[codecov-badge]: https://codecov.io/gh/swow/swow/branch/develop/graph/badge.svg?token=
[codecov-link]: https://codecov.io/gh/swow/swow
[release-badge]: https://img.shields.io/github/release/swow/swow.svg?style=flat-square
[release-link]: https://github.com/swow/swow/releases
