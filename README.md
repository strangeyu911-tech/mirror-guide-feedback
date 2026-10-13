# mirror-guide-feedback

《以日为鉴：衰退时代普通人生存指南（增补版）》的**读者批注私有收件箱**。

站点：<https://mirror.strangeyu.xyz/> ｜ 代码仓库：[strangeyu911-tech/mirror-guide](https://github.com/strangeyu911-tech/mirror-guide)

## 这个仓库是干什么的

读者在站点上划选正文、写下批注后，站点后端（Cloudflare Worker）会**代为**把这条批注追加到本仓库的聚合 issue 里。

两条设计要点：

- **读者不需要 GitHub 账号。** 批注由 Worker 用维护者的 token 代发，comment 的作者显示为维护者本人，读者在 GitHub 上完全不出场。这也意味着本仓库里所有 comment 的署名都相同，区分读者的依据是每条 comment 正文里的**读者标识行**。
- **本仓库为私有。** 读者批注不会出现在任何公开页面或公开仓库里。站点页面本身也只在读者自己的浏览器中回显他划过的内容。

## 仓库内容

唯一的内容物是 **issue 区**（聚合 issue + comment 追加）。代码与站点正文都在 mirror-guide 那个公开仓库里。

本仓库**不参与 GitHub Pages 构建**，与线上站点的部署链路无关。

## 处理约定

| 标签 | 含义 |
|---|---|
| `new` | 新收到，未看 |
| `accepted` | 采纳，将改进正文 |
| `rejected` | 不采纳（可附理由） |
| `fixed` | 已改完并上线 |

## 许可

本仓库仅作反馈收集用途，不包含《以日为鉴》正文，亦不对外分发。
