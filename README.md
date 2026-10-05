# CYAPI

> 当前版本：**v5.4.7**

CARYANG 服务器生态统一命令入口。(停更)

## 下载

从 [Releases](https://github.com/YANGCECYAPI/CYAPI/releases) 下载最新版 jar。

## 安装

1. 把 `CYAPI-x.x.x.jar` 放进服务器 `plugins/` 文件夹
2. 重启服务器
3. 首次启动后自动生成：
   - `plugins/CYAPI/config.yml`（可编辑配置）
   - `plugins/CYAPI/接入指南.txt`（第三方接入文档）

## 命令

| 命令 | 权限 | 说明 |
|------|------|------|
| `/cy <命令名> <参数>` | 所有人 | 执行第三方命令 |
| `/cy help` | 所有人 | 查看帮助 |
| `/cy cyapip list` | 所有人 | 列出你有权限的命令 |
| `/cy cyapi list` | 管理员 | 列出全部已注册命令 |
| `/cy cyapi clear` | 管理员 | 清空注册表 |
| `/cy cyapi reload` | 管理员 | 同上，别名 |

## 配置

`config.yml` 可调：

- `max-registrations` — 最多允许多少个命令注册
- `reserved-names` — 保留字列表
- `list-limit` — `/cy cyapi list` 显示条数
- `tab-limit` — Tab 补全最多返回条数
- `default-permission` — 第三方命令的默认权限

## 兼容性

- 服务器：1.17.1 到最新
- 核心：Bukkit / Spigot / Paper / Purpur
- Java：17 及以上

## 反馈

有 bug 或建议请到 [Issues](https://github.com/YANGCECYAPI/CYAPI/issues) 提交。

## 许可

本项目使用 MIT 许可，详见 [LICENSE](LICENSE)。
