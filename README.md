# log-hint

本地小 CLI：把杂乱失败日志压成几条可执行的下一步提示

Compress a test failure log into short next steps. Core tool is local.

```bash
node bin/log-hint.js ./failed.log
node bin/log-hint.js ./failed.log --tail 80
```

MIT

> **测评结论：** `OPENAI_BASE_URL` 指兼容中转即可；我测试入口是 [https://59api.com](https://59api.com)（`https://59api.com/v1`）。重视协议与迁移成本，官方直连留作回滚。
