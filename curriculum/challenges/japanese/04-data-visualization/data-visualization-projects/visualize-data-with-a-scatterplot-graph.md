---
id: bd7178d8c242eddfaeb5bd13
title: Visualize Data with a Scatterplot Graph
challengeType: 3
forumTopicId: 301467
dashedName: visualize-data-with-a-scatterplot-graph
---

# --description--

**目標:** <https://codepen.io/freeCodeCamp/full/bgpXyK> と同様の機能を持つ [CodePen.io](https://codepen.io) アプリを構築します。

以下の[ユーザーストーリー](https://en.wikipedia.org/wiki/User_story)を達成して、すべてのテストに合格してください。 あなたの独自のスタイルにしましょう。

HTML、JavaScript、CSS、および D3 の SVG ベースのビジュアライゼーションライブラリを使用できます。 テストでは、軸に沿って自動的にティックを生成する D3 軸プロパティを使用して軸を生成する必要があります。 これらのティックは、グラフ化された要素の配置を決定するために使用されるので、D3 テストに合格するために必要です。 軸の生成については <https://github.com/d3/d3/blob/master/API.md#axes-d3-axis> を参照してください。 必要な (非仮想) DOM 要素は、各テストの時にクエリされます。 フロントエンドフレームワーク (例えば Vue など) を使用した場合、動的なコンテンツではテスト結果が不正確になる可能性があります。 最終的には対応したいと考えていますが、現在の D3 プロジェクトではこれらのフレームワークはサポートされていません。

**ユーザーストーリー #1:** 対応する `id="title"` を持つタイトル要素が表示されています。

**ユーザーストーリー #2:** 対応する `id="x-axis"` を持つ x 軸が表示されています。

**ユーザーストーリー #3:** 対応する `id="y-axis"` を持つ y 軸が表示されています。

**ユーザーストーリー #4:** プロットされるデータを表すドット (それぞれが `dot` クラスを持つ) が表示されています。

**ユーザーストーリー #5:** 各ドットには、対応する `x` を格納している`data-xvalue` プロパティと、対応する `y` の値を格納している `data-yvalue` プロパティが必要です。

**ユーザー ストーリー #6:** 各ドットの `data-xvalue` と `data-yvalue` は、実データの範囲内にあり、正しい形式で指定される必要があります。 `data-xvalue` については、整数 (通年) または `Date` オブジェクトがテスト評価において許容されます。 `data-yvalue` (分) については、 `Date` オブジェクトを使用します。

**ユーザーストーリー #7:** `data-xvalue` とそれに対応するドットは、x 軸上の対応する点または値と一致している必要があります。

**ユーザーストーリー #8:** `data-yvalue` とそれに対応するドットは、y 軸上の対応する点または値と一致している必要があります。

**ユーザーストーリー #9:** y 軸上に、複数のテイックラベルが `%M:%S` 時間フォーマットで表示されています。

**ユーザーストーリー #10:** x 軸上に、年を示す複数のティックラベルが表示されています。

**ユーザーストーリー#11:** x 軸ラベルの範囲が実際の x 軸データの範囲内にあることが分かります。

**ユーザーストーリー#12:** y 軸ラベルの範囲が実際の y 軸データの範囲内にあることが分かります。

** ユーザーストーリー #13:** `id="legend"` を持つ説明テキストが含まれている凡例が表示されています。

**ユーザーストーリー #14:** ある領域にマウスカーソルを合わせると、その領域の詳細情報を表示するための、対応する `id="tooltip"` を持つツールチップが表示されます。

**ユーザーストーリー #15:** 私のツールチップには、アクティブな領域の `data-xvalue` に対応する `data-year` プロパティが必要です。

このプロジェクトを完了するために必要なデータセットはこちらにあります: `https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/cyclist-data.json`

プロジェクトを構築するには、<a href='https://codepen.io/pen?template=MJjpwO' target='_blank' rel='nofollow'>こちらの CodePen テンプレート</a>を使用し、`Save` をクリックして独自のペンを作成します。 または、下記の CDN リンクを使用して、使い慣れている環境でテストを実行することもできます: `https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js`

完了したら、すべてのテストに合格した作業プロジェクトの URL を送信してください。

# --solutions--

```js
// solution required
```
