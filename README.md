# Card Stack

## 功能说明

- 定期生成卡片页面

## 使用方法

1. 首先你必须使用 GitHub issues 作为卡片记录工具，那么你就必然需要创建一个 `GitHub` 账号并创建一个 `Repository`；

2. 创建一个 `issue`, 给它一个 `Read&Write` 的 `label` （必须，以便过滤掉其他 `issues` ），编辑并保存；

3. 打开本页面 `http://www.awareof.xyz/CardStack/index.html`

4. 在 `index.html` 后面追加你的账号和库信息，例如 `?user=hexcola&repo=note`, 即可查看今天所处的时间域（ `1-7` | `8-14` | `15-21` | `22 ~ 28/29/30/31` ）所写的所有卡片

5. 如果想查以往的卡片，则可以在链接中继续追加，例如 `&date=2018-3-5` 就会列出 `2018-03-01` 到 `2018-03-07` 这段时间内的所有卡片

## 使用库

- [Markdown.js](https://github.com/evilstreak/markdown-js)

## References

- [REST API v3 - Development Guides](https://developer.github.com/v3/guides/)