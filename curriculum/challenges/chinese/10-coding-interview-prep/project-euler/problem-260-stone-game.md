---
id: 5900f4701000cf542c50ff83
title: 问题260：石头游戏
challengeType: 5
videoUrl: ''
dashedName: problem-260-stone-game
---

# --description--

一场比赛由三堆石头和两名球员组成。在轮到时，玩家从堆中移除一个或多个宝石。但是，如果她从多个桩中取石头，她必须从每个选定的桩中移除相同数量的石头。

换句话说，玩家选择一些N> 0并从任何一个桩中移除：N个石头;或任意两桩（总共2N）中的每一块N石;或者从三个桩中的每一个（总共3N）中的N个石头。拿最后一块石头的玩家赢了比赛。

获胜配置是第一个玩家可以强制获胜的配置。例如，（0,0,13），（0,11,11）和（5,5,5）是获胜配置，因为第一个玩家可以立即移除所有宝石。

失败的配置是第二个玩家可以强制获胜的配置，无论第一个玩家做什么。例如，（0,1,2）和（1,3,3）正在失去配置：任何合法移动都会为第二个玩家留下获胜配置。

考虑所有丢失的配置（xi，yi，zi），其中xi≤yi≤zi≤100。我们可以验证Σ（xi + yi + zi）= 173895。

求Σ（xi + yi + zi）其中（xi，yi，zi）在失去的配置范围内，xi≤yi≤zi≤1000。

# --hints--

`euler260()`应该返回167542057。

```js
assert.strictEqual(euler260(), 167542057);
```

# --seed--

## --seed-contents--

```js
function euler260() {

  return true;
}

euler260();
```

# --solutions--

```js
// solution required
```
