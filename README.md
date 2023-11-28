<img width="1201" alt="スクリーンショット 2023-11-27 18 48 33" src="https://github.com/aaaa383/Optiver---Trading-at-the-Close/assets/58076642/5d37e6cd-b964-421e-ae92-c5983a74bce4">

# Optiver-Trading-at-the-Close
KaggleのOptiver - Trading at the Closeコンペの参加記録をまとめる

## コンペの目的
ナスダック上場銘柄の終値を予測する。

## 評価指標
MAE（Mean Absolute Error/平均絶対値誤差）は、真の値と予測値の差の絶対値の平均。  
つまりどれだけズレているのかというのを評価します。外れ値の影響を低減した形での評価に適している。

### Overview(deepl)
このコンペティションでは、注文帳簿と終値オークションのデータを使用して、ナスダック上場銘柄の終値の動きを予測できるモデルを開発することに挑戦します。
オークションからの情報は、価格の調整、需給ダイナミクスの評価、取引機会の特定に使用できます。

### Description(deepl)
証券取引所は、一刻を争うハイペースな環境である。一日の取引が終わりに近づくにつれ、その激しさはエスカレートし、最後の10分間がピークとなる。ボラティリティの高まりと急激な価格変動が特徴的なこの瞬間は、その日の世界経済のシナリオを形成する上で極めて重要な役割を果たす。

ナスダック証券取引所の各取引日は、ナスダックのクロージングクロスオークションで終了します。このプロセスによって、取引所に上場している証券の公式な終値が決定されます。これらの終値は、投資家、アナリスト、その他の市場参加者にとって、個々の証券や市場全体のパフォーマンスを評価する上で重要な指標となります。

この複雑な金融情勢の中で、世界をリードする電子マーケット・メーカーであるオプティバーは活動しています。技術革新を原動力として、オプティバーは、デリバティブ、現物株式、ETF、債券、外国通貨などの膨大な金融商品を取引し、世界の主要取引所において、数千もの商品に対して競争力のある両建て価格を提供しています。

ナスダック取引所の取引セッションの最後の10分間に、オプティバーのようなマーケットメーカーは従来のオーダーブックデータとオークションブックデータを統合します。両ソースからの情報を統合するこの能力は、すべての市場参加者に最良の価格を提供するために不可欠です。

このコンペティションでは、オーダーブックとオークションの終値データを使用して、ナスダック上場銘柄の終値の動きを予測できるモデルを開発することが求められます。オークションからの情報は、価格の調整、需給ダイナミクスの評価、取引機会の特定に利用できます。

あなたのモデルは、オークションとオーダーブックからのシグナルの統合に貢献し、特に取引の最後の10分間の激しい動きにおいて、市場の効率とアクセスの改善につながります。また、オプティバーのトレーダー、クオンツ・リサーチャー、エンジニアが直面するような、現実世界のデータサイエンスの問題を扱う実体験も得られます。


### Data(deepl)
このデータセットには、NASDAQ 証券取引所の毎日 10 分間の終値オークションのヒストリカルデータが含まれている。  
あなたの課題は、ナスダック上場銘柄で構成される合成指数の将来の値動きに対する、銘柄の将来の値動きを予測することです。

これは時系列APIを使った予測競技です。  
非公開のリーダーボードは、提出期間終了後に収集された実際の市場データを使用して決定されます。

### Files
[train/test].csv The auction data. The test data will be delivered by the API.



