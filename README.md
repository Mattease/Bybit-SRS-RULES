# My Shadowrocket Rules (Bybit 专项)

这是一个专门为 Shadowrocket（小火箭）优化的自定义规则集，主要用于 Bybit 的规则分流。

## 🚀 如何使用

1. **复制链接**：
   复制本仓库中 `bybit.list` 文件的 **Raw** 链接。
   
   `https://raw.githubusercontent.com/Mattease/Bybit-SRS-RULES/main/bybit.list`

3. **添加至 Shadowrocket**：
   - 打开小火箭 -> **配置** -> 点击当前配置右侧的 **(i)**。
   - 选择 **规则** -> **右上角 + 号**。
   - **类型**：选择 `RULE-SET`。
   - **策略**：选择 `PROXY` (或你的代理节点组)。
   - **URL**：粘贴上方复制的 Raw 链接。
   - 点击 **保存**。

## 📋 包含内容
- Bybit 主站及子域名
- Bybit API 接口域名
- 必要的 Amazon 网络服务域名（辅助加速）
- 相关的 IP 地址段 (CIDR)

## 🛠 更新日志
- **2026-04-14**: 首次创建，整合 Bybit 常用域名及 IP 段。

## ⚖️ 声明与致谢

本项目的规则集在整理过程中参考并引用了以下优秀开源项目：

* **[blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script)**: 提供了极其详尽的 Bybit 基础分流域名列表。
* 特别感谢 [Issue #1476](https://github.com/blackmatrix7/ios_rule_script/issues/1476) 中贡献者提供的最新域名补充。

本项目仅在原规则基础上针对 Shadowrocket 进行了格式优化和个人化定制。

仅供学习交流使用，请在合法范围内使用。
