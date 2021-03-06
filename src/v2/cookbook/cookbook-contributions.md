---
title: 参与 cookbook 贡献
type: cookbook
order: 1
---

## 我们的目标

Cookbook 为开发者提供了一些示例，涵盖常见的或有趣的用例，并逐步解释更复杂的细节。我们的目标是超越一个简单的示例介绍，展现更广泛适用的概念及其注意事项。

如果你有兴趣参与贡献，请将您的想法填入 issue 并加上 **cookbook idea** 的标签作为起步，这样我们就可以帮助并引导您完成一个 pull request。在你的想法被认同之后，请尽可能遵循以下模板。有些小节是必须的，有些是可选的。我们强烈建议您遵循其顺序，但这也不是必须的。

## 简单的示例

_必须的_

1. 用一两句话来说明问题。
2. 用一两句话解释最简单的可能的解决方案。
3. 显示一小段代码示例。
4. 用一句话解释它完成了什么。

## 关于其价值的细节

_必须的_

1. 解决人们在看例子时可能遇到的常见问题。(最好以块引用格式呈现)
2. 显示常见错误的例子，以及如何避免它们。
3. 用非常简单的代码示例展示好模式和坏模式。
4. 讨论这个模式令人信服的理由。参考链接不是必需的，但鼓励提供。

## 真实的例子

_必须的_

通过以下方式演示能够为常见或有趣的用例提供支持的代码：

1. 通过几个简单的设置例子，或者
2. 嵌入一个 CodePen / JSFiddle 的例子

如果你选择稍后再提供，那么你仍应该表述它是什么和做什么。

## 额外的上下文

_可选的_

为这个模式写点东西，描述在这个模式下，它会应用到什么地方，为什么它能正常工作；以及在此基础上运行一些代码、提供一些延伸阅读材料，都是非常有帮助的。

## 何时避免使用这个模式

_可选的_

本节不是必需的，但强烈建议。你没有必要写一些特别简单易懂的事项，比如根据状态的改变开关 class，但是对于 mixin 这样的更高阶的模式来说是非常重要的。大多数高阶的问题的答案都是[“要看情况！”](https://codepen.io/rachsmith/pen/YweZbG)，该部分就包含了这一点。在此，我们要诚实地看待模式何时有用，何时应该避免，什么时候更有意义。

## 替代模式

_可选的，除非这部分内容在之前已经提供过了_

如果你已经在上一节提供了避免使用的条件，那么这一节是必须的。探索其它方法非常重要，这样人们在遇到某些反模式的情形时不至于无所适从。这样做是因为考虑到 web 是一个不同人有着不同代码结构解决不同问题的大舞台。这个应用是大是小？它们要把 Vue 集成到一个现成的项目中还是从零起步构建新项目？它们的用户只是想达成一个目标还是多个？有很多异步数据吗？所有的这些担忧都会影响实现替代品。一篇好的 cookbook 会为开发者提供这些相关信息。

## 致谢

文档贡献是需要很多时间的，如果您花时间提交这部分的文档，我们将感激不尽。
