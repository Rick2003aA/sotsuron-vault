Chaos Report
無改造のパッケージ導入は成功率57%、既存システムのモダナイゼーションは53%とされる一方、現代的手法によるスクラッチ開発は失敗率23%、伝統的な言語・手法によるスクラッチ開発は「challenged」が61%と報告されています。
https://cdn1-public.infotech.com/agile/CHAOSReport2015-Final.pdf

Endless Modernization: How Infinite Flow Keeps Software Fresh
https://www.rocketsoftware.com/sites/default/files/resource_files/endless-modernization-how-infinite-flow-keeps-software-fresh-report.pdf
これは次の主張を組み立てる際に使えそうです。

> 問題は古い技術を使用していることだけではなく、企業が継続的にシステムを変更・更新する能力を持っていないことにある。

---

## 検証メモ（2026-11-21 Muse）

### Standish Groupとは・何のデータを出しているか
- 米国の民間コンサルティング会社 The Standish Group International。1994年から CHAOS Report を刊行し、ソフトウェア開発プロジェクトの成否を Successful（期限・予算内＋満足な結果）／Challenged（遅延・予算超過・範囲縮小）／Failed（中止・未使用）に分類して集計している。公的統計ではない。
- 最新の本編は CHAOS 2020: Beyond Infinity（有料）。成功要因を Good Sponsor／Good Team／Good Place の3つに集約し、意思決定の遅さ（decision latency）を失敗の根本要因とする。

### 原典で確認できた数字（CHAOS Report 2015、FY2011-2015、Modern Resolution）
- 全プロジェクト（2015年）：Successful 29%／Challenged 52%／Failed 19%
- 規模別が卒論で最も使いやすい：Grand（最大規模）成功 6%・失敗 43% に対し、Small 成功 61%・失敗 7%。大規模プロジェクトほど成功率が桁違いに低い
- CHAOS 2020（二次資料経由）：Successful 約31%／Challenged 約50%／Failed 約19% で、2015から大きく変わっていない

### このメモ冒頭の数字について
- パッケージ57%・モダナイゼーション53%・スクラッチ失敗23%・伝統的スクラッチ challenged 61% は、CHAOSデータベースのプロジェクト類型・手法別の内訳とみられるが、今回の確認では該当ページの原典照合までできていない。引用する前に CHAOS Report 2015 原典PDFの該当表で確認すること（未確認のまま本文に入れない）。

### 重大な注意：方法論への学術的批判がある
- Eveleens & Verhoef (2010) "The Rise and Fall of the Chaos Report Figures", IEEE Software 27(1): 成功／失敗の定義が「当初見積もりの正確さ」に過ぎず一方向的で、数値は「意味をなさない（no credence）」と強く批判。Standishは標本の詳細・生データを公開していない。
- したがって CHAOS の数値を、IPA・経産省の一次統計と同格の証拠として使うのは危険。使うなら「業界で広く引用される一方、方法論への批判もある民間調査」と留保を付ける。

### 卒論での使いどころ（日本固有の証拠にはならない）
- データは主に米国／グローバルのプロジェクトで、日本の分業構造そのものの証拠にはならない。
- 使えるのは一般メカニズムの側：①大規模な全面刷新プロジェクトは規模自体で失敗しやすい（→第2章2.4／第5章「全面刷新より追加改修・延命が選ばれる理由」の一般論の裏付け）②Endless Modernization の「継続的に変更・更新する能力の欠如が問題」という視点（→第5章・第6章）。
- Endless Modernization は Rocket Software（モダナイゼーション製品のベンダー）向けのホワイトペーパーで、Standish自身の商業的立場も含め中立な学術資料ではない点に注意。
