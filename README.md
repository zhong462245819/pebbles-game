# pebbles-game

Pebbles Game 是一个用 Rust 编写的有趣且互动性强的游戏。该项目包含核心游戏逻辑、IO 处理和基本测试。

## 项目特点
	• 核心游戏逻辑：包括所有游戏规则和逻辑实现，确保游戏的流畅运行。
	• IO 处理：负责处理输入输出操作，使游戏能够与用户进行互动。
	• 基本测试：包含一组基本测试，确保代码的可靠性和稳定性。
	• 高性能：利用 Rust 语言的高性能和内存安全特性，确保游戏在各种平台上的稳定性和性能。
	• 可扩展性：代码结构清晰，易于扩展和维护。

## 项目结构

```plaintext
pebbles-game
├── io
│   ├── src
│   │   └── lib.rs
│   └── Cargo.toml
├── src
│   └── lib.rs
├── tests
│   └── basic.rs
├── Cargo.lock
├── Cargo.toml
└── build.rs
```

## 先决条件

要构建和运行此项目，你需要安装以下软件：

	• Rust: 用于此项目的编程语言。
	• Cargo: Rust 的包管理器。
	• wasm-pack: 用于构建 Rust 生成的 WebAssembly 的工具。

## 构建项目

使用以下命令构建项目：

```
cargo build
```



## 运行测试

使用以下命令运行测试：

```
cargo test
```
