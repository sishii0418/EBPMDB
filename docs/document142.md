---
id: "142"
title: "低所得世帯に対するベーシックインカム"
description: "カナダにおいて3年間にわたるベーシックインカムの支給が出生率に与えた影響"
date: "2024-06-02"
category: "fertility"
categoryLabel: "少子化対策"
tables: [
  {
    "title": "出生率",
    "effectiveness": "効果あり",
    "strength": 5
  },
]

points:
    - ベーシックインカムの支給によって、出生率が7パーセントポイント増加した。
    - ベーシックインカムによる世帯収入の保証が低所得世帯の出生率に寄与することが確認された。

contacts:
  - 石井俊輔 (The University of Edinburgh)

---

## 背景
- 理論的には世帯収入が増えると出生数が増えるはずだが、実際には世帯収入と出生数との関係は単調ではなく、子供の数よりも子育ての「質」を求める中所得者層では負の関係があるとみられている。
- 1960~70年代、アメリカやカナダで貧困率が上昇しており、その対策としてベーシックインカムや負の所得税の可能性が議論されていた。
- カナダ・マニトバ州では、1974年からランダムに選ばれた低所得世帯に対し3年間一定レベルの収入を保証するベーシックインカム政策の社会実験が行われた。この政策実験はミンカム (Mincome = minimum income の造語) と呼ばれている。

## 介入
- 3年間に渡るベーシックインカムの支給による世帯収入保証。
- 収入の保証額は4人世帯において3,800ドル、4,800ドル、5,480ドルの3つのレベルにランダムに振り分けられた (1972年当時の4人世帯の収入の中央値は11,234ドル)。

## 評価指標
- 出生率: 各家庭が子供を出産する確率

## 分析方法
- 世帯収入が一定水準以下であることを条件に、ランダムにミンカムの対象世帯を選びランダム化比較試験を行った。
- ロジスティック回帰を用いて、ミンカムの対象に選ばれた世帯とそうでない世帯において出生率に差があったか分析した。

## 証拠の強さ
- SMS: 5
  - 所得が一定水準以下の世帯について、ミンカムの支給可否はランダムに決定されている。
  - 介入群と対照群の世帯との間で、収入がある人員の数や収入額、子供の数などに違いがみられた。しかし、このような違いをコントロール変数として回帰式に組み込むことで、条件付き独立の仮定の下、推定結果が因果関係を示唆することを説明している。
  - イベントヒストリー分析を用いることで、ミンカムの対象世帯とそうでない世帯との間にデータで捉えられていない差がないことを確認している。

## サンプル- カナダ・マニトバ州の州都ウィニペグに居住する、収入が一定水準以下の世帯。
- 世帯は家族構成と収入の2つの変数をもとに層化抽出された。
  - 家族構成は二人親共働き世帯、二人親で片方が働いている世帯、一人親世帯、独身世帯の4種類に分類された。
- 最終的な分析の対象世帯数は435あり、そのうちミンカムが支給された介入群は335世帯、支給されなかった対照群は100世帯あった。
- データはこの社会実験用に収集された一次データを利用。

## 結果
- ミンカムの支給を受けた世帯において、出生率が7パーセントポイント増加した。
- 夫婦で暮らす世帯に限ると、出生率の増加は13パーセントポイントで、さらに子供がいない世帯では29パーセントポイント増加した。
- 出生率の増加幅は支給額によっては左右されず、それよりもミンカムによる収入の保証自体が世帯出生率に影響をもたらしていた。

## 研究の弱点
- ミンカムが支給されていた期間は3年間に過ぎず、期限無しの支給ではより変化幅が大きくなっていた可能性がある。
- ミンカムの支給には事前調査や支給期間中の四半期ごとの調査への参加が求められており、その負担の大きさから、より恩恵を受けそうな世帯がプログラムに残り、あまり恩恵を感じなかった世帯は途中でプログラムから離脱した可能性がある。この場合、効果が過大推定されている恐れがある。

## 書誌情報
- Dökmeci, T., Rainer, C., & Schneebaum, A. (2023). Economic Security and Fertility: Evidence from the Mincome Experiment. *Canadian Public Policy. Analyse de Politiques*, 49(2), 136–161. https://doi.org/10.3138/cpp.2022-063
