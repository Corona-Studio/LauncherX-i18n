# LauncherX-i18n

这里是 LauncherX 的多语言文档仓库，这里保存了 LauncherX 所使用的语言文档，欢迎各大贡献者的贡献！

## 开始之前

感谢热心市民的贡献！使用Git贡献翻译需要的前置知识：[如何使用Git和Github / 目标语言翻译知识 / 本篇下文会提到的工具使用方法]

## 如何贡献

您可以通过点击页面右上角的 `Fork` 按钮来获得一个仓库的副本，在翻译完成之后可以提交一个 PR 至本仓库以完成审核和合并。

**请不要动除了您贡献的目标语言文件之外的任何内容。**

### 如果要开启一个新语言

首先根据[这篇文档](https://www.zhanid.com/tool/language-codes.html) 确认语言代码，文件命名需要使用它的全小写格式。如果将要创建一个整活向（梗）语言，请整活地为其命名，但是形式上要相似。比如：火星文的语言代码是`zh_hxw`

在Fork完成后，将您的仓库副本（在您名下，fork自此处）拉取到您的电脑上（如果是Git新手，推荐使用 [Github Desktop](https://github.com/apps/desktop)）

在拉取到的文件夹里复制一份简体中文文档（`zh_cn`），将其重命名为之前确认的语言代码(`<语言代码>.axaml`)，然后就可以开始编辑了。

### 如果要贡献到现有语言

请在开始之前使用语言文档快速工具（[LangFileCleaner](https://github.com/Corona-Studio/LangFileCleaner)）

使用此工具将其他语言文档中缺失的字段（条目）从简体中文文档同步到目标语言文档，然后进行翻译。

您可以在仓库的 `Releases` 页面下载到工具的最新构建。

在下载之后，请使用该工具对您将要翻译的语言文档进行一次同步操作以获得最新的变更：

```bash
.\LangFileCleaner.exe sync -s "[zh_cn.axaml 的路径]" -t "[您要翻译的语言文档的路径]" -o "out.axaml"
```

执行完成后您将在工具的目录下发现一个 `out.axaml` 这里面的所有条目均已完成与 `zh_cn.axaml` 的同步，现在开始翻译吧！

## 贡献列表

![Alt](https://repobeats.axiom.co/api/embed/70122cda29c3978ce1dfb34c45f389f3ba44b315.svg "Repobeats analytics image")
