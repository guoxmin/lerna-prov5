### project/project1 为 antd pro v5 项目，app.tsx引用本地 packages/test包，修改不会HRM

> config 配置

```
chainWebpack(config) {
    config.resolve.symlinks(false);
  }
```
