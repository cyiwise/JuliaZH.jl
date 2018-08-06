# 翻译格式指引

统一的翻译稿件格式有助于日后维护。请在参与翻译之前阅读这个指引，以保证大家的文档格式基本一致。

## 原文段落组织

英文原文如下方式在Markdown里注释：

```
\`\`\`@raw html
<!-- English -->
\`\`\`
```

中文翻译写在下面。

## 格式细则

1. 段落英文中的英文两边空格，例如：

> 不要将它的类型声明为 `Int`

2. 专业词汇请用括号注明英文原文，例如

> 而要使用抽象类型（abstract type）

3. 文件链接全部保持原文链接（包括wiki，`@ref`的文档内部交叉引用）

4. master分支的文档跟进官方repo的master分支。

5. 对于表格， 如果翻译则请按照段落处理


## 提交规则

- 提交译文时， 请用 pull request (PR) 提交。 对于翻译中不确定的部分， 请在 PR 里指明。

- 对于含有多个 commit 的 PR， 合并时， 请选择  ``squash and merge`` 。

## 书写规范
### 标点符号
中文内容请使用半角中文标点符号， 尤其是逗号以及括号， 冒号， 破折号。 对于引号， 如果被引用的内容**包含**英文， 则使用英文引号。

### 空格
译文一律使用空格， 禁止使用 ``Tab``， 仅对注释原文时可以用 ``Tab`` 缩进， 缩进为两个空格。 中文和英文以及数字间应加一个空格。

### 粗斜体
中文部分不应使用斜体， 对于原文斜体部分， 译文里可以酌情修改为粗体。

## 内容规范
力求表达清楚明确， 语句尽量通顺， 请不要逐字翻译， 避免错别字等。

### 代码
只翻译注释， 如果代码简单易懂， 可不翻译。

### 专有名词
如果没有对应或者不确定的专有词汇， 可以先不译， 保留在译文里。 等确定后可批量修改。

### 人称代词
像 "we" 和 "you" 这些词汇一般来说可以不译出来， 或者换个说法。 如果译出来更通顺， 就翻译出来。  