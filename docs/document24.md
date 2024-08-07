---
id: "24"
title: "出生日による入学年度の違い"
description: "日本において、学校教育法（4月2日前後に生まれた子どもの入学年度が異なる）が出産のタイミングに与える影響"
date: "2024-06-27"
category: "education"
categoryLabel: "教育"
tables: [
  {
    "title": "1日当たりの出生数",
    "effectiveness": "効果あり",
    "strength": 3
  }
]

points:
- 年間1800人以上の出生が、入学年度の切替日（日本の場合4月2日）前から切替日後の週にシフトすると考えられる。
    - これは、同じ学年の中で早く生まれていることによって、周りより発達が早く学力面で有利になる可能性があることが原因の一つと考えられる。
    - 出産のタイミングを決める際に、子どもの学力という長期的な面を考慮に入れている親がいることを示唆している。
- 第2子以上の出産、男子の出産、または高いSES（社会経済的背景）の親による出産の方が、出生日のシフトが起きている可能性が高い。
- 居住地域の保育所の利用しやすさと出生のシフト数の間には正の相関がある。
- 「経済的に恵まれた人ほど入学を遅らせやすいアメリカのような制度では、格差拡大につながるかもしれないので、日本のように厳格に入学年度を決めた方がよい」とは必ずしも言えない。
    - 上述したように、高いSES（社会経済的背景）の親の方が出生日をシフトさせている可能性があり、厳格に入学年度が決まっていても、格差拡大と無縁ではないからである。
- 未刊行論文


contacts:
- 大島侑真（東京大学）

---

## 背景
- 親はさまざまな税制などのインセンティブを考慮して、出産のタイミングを決定しているという研究結果が出ている。
- 多くの親が入学を遅らせるアメリカなどと比較すると、日本では、ほぼ全ての子どもが満6歳時点で小学校に入学するため、出生日が入学年度の決定要因となる。
- 入学年度が切り変わる4月2日付近に出産を控えている親はトレードオフに直面する。
4月2日以降に出産すると、その子どもは周りの子どもより最大で約1年早く生まれているため、学力面で有利になるかもしれない。
他方、入学年度が1年遅くなるため、親はその分のコストを負担しなければならない。
- 長期的な学力を考慮した出産のタイミングの意思決定がなされているかを分析した。

## 介入
- 学校教育法：小学校への入学年度が、出生日（4月2日より前か以降か）によって異なる。

## 評価指標
- 1日当たりの出生数

## 分析方法
- 出生のシフトに関する分析：「日次の出生数」を「出生日が4月2日以降ダミー」に回帰したモデル（曜日・祝日・年効果含む）を推定
親や子どもの特徴に関する異質性を分析する際は、サブグループごとの推定値を比較
- 出生のシフトと保育所との関係についての分析：都道府県別のシフト数の推定値を保育所の利用可能性に回帰したモデル（都道府県・年効果含む）を推定


## 証拠の強さ
- SMS:3
- 根拠
     - 年効果や曜日効果、祝日効果を含んでいる。
     - 4月以外の2日前後のアウトカムにほぼ差がないことを確認することで、入学年度の切替日による効果を識別できている。


## サンプル
- 「出生日に関するデータ」
    - 厚生労働省によるデータ
    - 1974年〜2010年の全出生（5000万以上）の正確な日付が記録されている。
    - 0.01%未満しか欠損がなく、欠損は分析対象から取り除かれている。
    - 出生証明書で集計されたデータで、体重や性別などの新生児の情報を補完している。
- 「死亡データ」
    - 1974年〜2010年の全死亡が記録されている。
    - 亡くなった人の出生日や性別、死因などが含まれる。
- 「保険請求データ」
    - 2011年～2012年の約500の病院から集めたデータ
    - 出産方法、特に帝王切開かどうかの情報を利用する。
- 「保育所データ」
    - 1974年～2007年の保育所の受入れ枠データ（都道府県別）
- 「PISA」
    - OECDによるデータ
    - 分析には、2003年の調査を使用


## 結果
- 年間1800人以上の出生が、入学年度の切替日（日本の場合4月2日）前から切替日後の週にシフトする。
     - 4月2日だけでなくそれ以降も出生が増加していることや、4月2日以降の出産の方が妊娠期間が長く新生児の体重も重いことなどから、出生日の改ざんが主な原因では無いと考えられる。
- 異質性に着目すると、第2子以降、母親が30歳以降、子どもの性別が男、または親が高いSES（社会経済的背景）である場合、出産を4月2日以降に遅らせている割合が高い。
- 居住地域の保育所の利用しやすさと出生のシフト数の間には正の相関がある。
     - 因果関係を分析することはできていないが、保育所が利用しやすく育児のコストが低いと出産タイミングを遅らせやすいという仮説と整合的である。
- 実際に、早生まれの子どもほどPISAの点数が低い。


## 研究の弱点
- 日本の「出生日に関するデータ」からは親の教育水準や所得、就業形態などの情報がわからないため、親の特性と出産のタイミングとの関係を詳細に分析することはできない。
- 上記の「出生日に関するデータ」の限界を補うため、PISAデータも使用しているが、PISAデータでは出生月までしか記録されていない。


## 書誌情報
- Shigeoka, H. (2015). School Entry Cutoff Date and the Timing of Births (Working Paper No. 21402). National Bureau of Economic Research. https://doi.org/10.3386/w21402