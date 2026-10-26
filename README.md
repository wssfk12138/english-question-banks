<div align="center">

  <img src="docs/images/cover.webp" alt="英语刷题机题库封面" width="100%">

  # 英语刷题机题库

  **四六级与考研英语 · ESQ 题库分发 · 校验后导入**

  配合 [英语刷题机 Android](https://github.com/wssfk12138/android-english-multiple-choice-practice-machine) 与 [Windows 版](https://github.com/wssfk12138/english-multiple-choice-practice-machine) 使用

  <p>
    <a href="https://linux.do/" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/LINUX-DO-FFB003.svg?logo=data:image/svg%2bxml;base64,DQo8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgd2lkdGg9IjEwMCIgaGVpZ2h0PSIxMDAiPjxwYXRoIGQ9Ik00Ni44Mi0uMDU1aDYuMjVxMjMuOTY5IDIuMDYyIDM4IDIxLjQyNmM1LjI1OCA3LjY3NiA4LjIxNSAxNi4xNTYgOC44NzUgMjUuNDV2Ni4yNXEtMi4wNjQgMjMuOTY4LTIxLjQzIDM4LTExLjUxMiA3Ljg4NS0yNS40NDUgOC44NzRoLTYuMjVxLTIzLjk3LTIuMDY0LTM4LjAwNC0yMS40M1EuOTcxIDY3LjA1Ni0uMDU0IDUzLjE4di02LjQ3M0MxLjM2MiAzMC43ODEgOC41MDMgMTguMTQ4IDIxLjM3IDguODE3IDI5LjA0NyAzLjU2MiAzNy41MjcuNjA0IDQ2LjgyMS0uMDU2IiBzdHlsZT0ic3Ryb2tlOm5vbmU7ZmlsbC1ydWxlOmV2ZW5vZGQ7ZmlsbDojZWNlY2VjO2ZpbGwtb3BhY2l0eToxIi8+PHBhdGggZD0iTTQ3LjI2NiAyLjk1N3EyMi41My0uNjUgMzcuNzc3IDE1LjczOGE0OS43IDQ5LjcgMCAwIDEgNi44NjcgMTAuMTU3cS00MS45NjQuMjIyLTgzLjkzIDAgOS43NS0xOC42MTYgMzAuMDI0LTI0LjM4N2E2MSA2MSAwIDAgMSA5LjI2Mi0xLjUwOCIgc3R5bGU9InN0cm9rZTpub25lO2ZpbGwtcnVsZTpldmVub2RkO2ZpbGw6IzE5MTkxOTtmaWxsLW9wYWNpdHk6MSIvPjxwYXRoIGQ9Ik03Ljk4IDcwLjkyNmMyNy45NzctLjAzNSA1NS45NTQgMCA4My45My4xMTNRODMuNDI2IDg3LjQ3MyA2Ni4xMyA5NC4wODZxLTE4LjgxIDYuNTQ0LTM2LjgzMi0xLjg5OC0xNC4yMDMtNy4wOS0yMS4zMTctMjEuMjYyIiBzdHlsZT0ic3Ryb2tlOm5vbmU7ZmlsbC1ydWxlOmV2ZW5vZGQ7ZmlsbDojZjlhZjAwO2ZpbGwtb3BhY2l0eToxIi8+PC9zdmc+" alt="LINUX DO 社区"></a>
    <img src="https://img.shields.io/badge/ESQ-1.0%20%2F%201.1-2563EB?style=flat-square" alt="ESQ 1.0 / 1.1">
    <img src="https://img.shields.io/badge/banks-4-16A34A?style=flat-square" alt="4 个题库">
    <img src="https://img.shields.io/badge/release-2026--09--27-F59E0B?style=flat-square" alt="2026-09-27">
    <img src="https://img.shields.io/badge/license-NOASSERTION-7C3AED?style=flat-square" alt="内容许可 NOASSERTION">
  </p>

  <p>
    <a href="#catalog"><img src="https://img.shields.io/badge/%E5%AF%BC%E5%85%A5%E7%9B%AE%E5%BD%95-%E7%82%B9%E5%87%BB%E6%9F%A5%E7%9C%8B-4F7CFF?style=flat-square" alt="导入目录"></a>
    <a href="#verify"><img src="https://img.shields.io/badge/SHA--256-%E6%A0%A1%E9%AA%8C-0EA5E9?style=flat-square" alt="SHA-256 校验"></a>
  </p>
</div>

本仓库独立分发英语刷题机 ESQ 题库。题库文件存放在 Releases；Git 仅保存目录清单、校验值和发布说明。题库可导入 Android 与 Windows 两端的英语刷题机，导入不会覆盖个人做题记录。

## 导入目录

<a id="catalog"></a>

固定目录地址：

```text
https://raw.githubusercontent.com/wssfk12138/english-question-banks/main/question-bank-catalog.json
```

在英语刷题机的远程题库目录中填写该地址，刷新后选择题库下载并按提示导入。目录更新不会自动覆盖应用中的题库或做题记录；新题库默认建立独立配置，也可以选择导入已有配置。

## 当前发布：2026-09-27

| 题库 | 内容版本 | 内容范围 |
| --- | --- | --- |
| 大学英语四级（CET-4） | 1.2.1 | 35 套，1825 题；包含人工复核修正 |
| 大学英语六级（CET-6） | 1.2.1 | 43 套，2365 题；包含人工复核修正 |
| 考研英语（一） | 1.1.3 | 2002、2010–2026；18 套，805 题；2026-09-r5 修订 |
| 考研英语（二） | 1.1.3 | 2010–2025；16 套，720 题；含已锁定智能标注 |

考研英语（一）的 1.1.3 已修复 132 个选项、53 道题的选项末尾截断与重复编号问题，答案、题号和稳定标识未变。大小和 SHA-256 以 `question-bank-catalog.json` 及 `SHA256SUMS` 为准。

## 下载与校验

<a id="verify"></a>

题库包只在 [Releases](https://github.com/wssfk12138/english-question-banks/releases) 中提供。目录中的每个条目都包含文件名、字节数和 SHA-256；应用下载后会先核对大小与哈希，再进入冲突预览。

```text
postgraduate-english-one-2002-2010-2026-v1.1.3.esq
sha256  099f212c17ef631b77da35e4154c844faee15611ce29968964f1619bf1db9aec

postgraduate-english-two-2010-2025-v1.1.3.esq
sha256  63b15409bbfeea674e5917592d6eece399d978feab38a5439119c07a9afc21be

cet4-complete-v1.2.1.esq
sha256  bba6bf1af0ff988e98bae4e6d27dbdd0ee0ce29d3da72903758853ceea2dc048

cet6-complete-v1.2.1.esq
sha256  0adc274514723bfdace623d72646fd8dd96a58dfc9a1efe7464d2c09077244b2
```

完整校验值见 [SHA256SUMS](SHA256SUMS)，版本变化见 [CHANGELOG.md](CHANGELOG.md)。发现问题时请附上题库名称、内容版本、年份、题号和页面截图；不要上传包含个人做题记录或题库整理原稿的数据库。

## 兼容旧入口

原应用仓库的 `question-banks-v1.2.0` Release 中保留 `question-bank-catalog.json`，并将下载地址指向此仓库。已配置该目录的客户端可继续刷新；旧版客户端针对旧仓库设置的备用下载线路不会自动适用于新仓库。

## 内容许可

沿用各包原有 `NOASSERTION` 声明，不为原始试题新增授权；具体声明见 ESQ 内 `manifest.json`。本仓库不包含原始 PDF/Word、应用数据库、学习记录或私有校对材料。使用或再分发题库前，请确认你拥有相应权利。
