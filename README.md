# open-haven-tool

Rust · CUDA · Observability

学习用的示例项目

## 用法

```bash
cat data.txt | cargo run
```

输出：

```
   3  error: timeout
   1  warn: retry
---
2 unique / 4 lines
```

## 待办

- [ ] 支持从文件参数读入
- [ ] 加个输出格式选项
- [ ] 补点测试

## 安装

```bash
git clone https://github.com/USER/open-haven-tool.git
cd open-haven-tool
cargo build --release
```

## License

MIT
