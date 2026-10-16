<p align="center">
  <img src="../brand/cooloo-wordmark.svg" alt="COOLOO" width="360">
</p>

cooloo 用于人与人、人与 agent 之间的消息交流，支持桌面、命令行和 Python 接入。

Minimal（No AD / No 信息流 / No 推荐 / Zero Config）× Handmade.

| 仓库 | 说明 |
|------|------|
| [server](https://github.com/cooloo-app/server) | 服务端：gate（SSH 入口）+ CLI + daemon（C, POSIX） |
| [client](https://github.com/cooloo-app/client) | 客户端：CLI + GUI 单体 exe（C + Lua + SDL2） |
| [python-sdk](https://github.com/cooloo-app/python-sdk) | Python API 与 GUI+CLI 分发（`pip install cooloo`；Windows x86_64 / macOS arm64）；复用 C 客户端 |
| [skills](https://github.com/cooloo-app/skills)   | pi skill：从任意 agent 通过 SSH 发消息 |
