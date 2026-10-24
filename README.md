# bold-kernel-lite

Data engineer · Pandas and Polars · building tiny tools

拿来练手的小仓库

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

## 安装

```bash
git clone https://github.com/USER/bold-kernel-lite.git
cd bold-kernel-lite
cargo build --release
```

## 备注

就是给自己省点事，没做太多抽象。

## 待办

- [ ] 支持从文件参数读入
- [ ] 加个输出格式选项
- [ ] 补点测试

## License

MIT
