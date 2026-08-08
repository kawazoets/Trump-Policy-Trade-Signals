# Case 03 — Intel

Case 03は **Intel — 2025年8月18日の株式購入と、数日後の米政府によるIntel出資発表** を扱います。
このCaseは、Case 01・02よりもさらに法的な論点が見えやすい一方で、**反証材料もかなり強い**案件です。

### Case 03で見ること
時系列を単純化すると、こうです。

> **2025年8月18日**  
> Trump関連投資口座でIntel株を購入  
> ↓  
> **2025年8月22日**  
> Trump政権とIntelが、米政府による約9.9%の株式取得を発表

表面だけ見ると、
**Trade Before Policy = 4 days**
です。

Case 01は1日前、Case 02は同日、Case 03は4日前です。
一見するとかなり注目すべき時間差です。
### ただし、Intelは非常に重要な反証があります
ここがCase 03の核心です。
正式発表は8月22日ですが、その前の**8月14日には、Trump政権がIntelへの出資を検討しているという報道がすでに出ていました。**

つまり、
> 8/18にIntelを買った  
> ↓  
> 8/22に政府出資が発表された

だけを切り取ると強く見えますが、実際には、

> **8/14　政府出資協議が報道される**  
> ↓  
> **8/18　Intel株購入**  
> ↓  
> **8/22　正式発表**

という可能性があります。
この場合、8月18日の買いは**公開情報に基づく通常の投資判断**でも説明できます。
したがってCase 03は、単純な「政策発表前取引」の例ではありません。

### Case 03の本当の論点

**正式発表前だったか**

ではなく、
**投資判断時点で、どこまで情報がすでに公開されていたか**
です。

Case 03では少なくとも次の3つの日付を分けて扱う必要があります。

- **Public Rumor / Reporting Date**
- **Trade Date**
- **Official Policy Announcement Date**

これは今後の全Caseにも使える非常に重要な設計です。

たとえば、

| DateEvent | |
| --------- | -------------------------------------------------- |
| Aug 14 | Government stake discussions reported publicly |
| Aug 18 | Intel stock purchase |
| Aug 22 | U.S. government–Intel agreement formally announced |

こうなると、Temporal Gapを単に**Event Date − Trade Date**だけで見るのは足りません。

追加で、**Public Information Gap = Trade Date − First Public Report Date**も見た方がいいです。

Intelの場合、買いは公開報道の**4日後**です。

これはかなり重要です。

### さらに調べるべきこと
Case 03では、次を確認します。
- 8月18日のIntel購入額レンジ
- 同日にIntelを何回買ったか
- 8月18日前後にもIntelを買っていたか
- 8月14日の報道内容がどこまで具体的だったか
- 8月22日の正式契約内容が8月14日時点の報道を超えるサプライズを含んでいたか
- 8月14日、18日、22日前後のIntel株価
- 同じ日にNvidia、Apple、Microsoftなども大量購入していたか
- portfolio rebalancingで説明できるか

特に重要なのは、**8月18日がIntel単独の集中買いだったのか、それとも大型テック全体を大量購入した日だったのか**です。
もし後者なら、Intelだけを取り出すとチェリーピッキングになります。

### Case 03の暫定評価
現時点では、
**Temporal Significance: Moderate**
**Prior Public Information: Strong**
**Evidence of Illegal Trading: Not Established**
という位置づけになると思います。

むしろCase 03は、このプロジェクトにとって非常に良い「反証ケース」です。
「政策発表の4日前に買っていた」という数字だけなら強く見える。しかし、調べるとその4日前よりさらに前に市場へ情報が出ていた。
このケースをきちんと残すことで、このGitHubが単なる疑惑集ではなく、**疑わしく見えるものを実際に検証して弱めることもある研究**だと示せます。

次は、OGE原本で、**2025年8月18日のIntel取引と同日の全取引を確認する**ところから進めます。
結論からいうと、**「4日前にIntelを買った」という事実だけでは弱く、むしろ“公開情報がいつ出ていたか”を入れる**です。

### Case 03 — Intel

確認できた時系列はこうです。
| DateEvent意味 | | |
| ---------------- | -------------------------------------- | ------------------ |
| **Aug 11, 2025** | Intel CEO Lip-Bu TanがTrump氏と面会 | 政府とIntelの接触は公開済み |
| **Aug 14, 2025** | Bloomberg報道をReutersが報道：米政府がIntel株取得を検討 | **政府出資の可能性が市場に公開** |
| **Aug 18, 2025** | Trump関連投資口座がIntel株を少なくとも$250,000購入 | 調査対象の取引 |
| **Aug 18, 2025** | SoftBankがIntelへ$2B出資契約を発表 | 同日に別の大きな好材料 |
| **Aug 22, 2025** | 米政府とIntelが正式契約を発表 | 政府が9.9%取得 |

まず8月11日、Intel自身がCEOのLip-Bu Tan氏とTrump氏が面会し、米国の技術・製造業強化について協議したことを公表しています。
そして8月14日、ReutersはBloomberg報道を引用して、Trump政権がIntelへの政府出資を協議していると報じています。
この時点でIntel株は通常取引で7%以上上昇し、その後の時間外取引でも上昇しました。つまり、**市場は政府出資の可能性を明確に認識していました。**
その4日後、8月18日にTrump氏の投資口座で**少なくとも$250,000のIntel株購入**があったとWSJの開示分析が報じています。
同日はTrump氏の口座にとって2025年最大級の取引日で、総取引額は7,500万ドル超。Nvidia、Apple、Microsoftではそれぞれ$5M–$25Mの購入レンジだったと報じられています。

ここが重要です。
**Intelだけを狙って大量購入した日ではありません。**
むしろ、
> Large Tech Portfolio Purchase Day  
> ＋  
> Intelも購入
という性格が強い。

さらに同じ8月18日には、SoftBankがIntel株を**20億ドル、1株23ドルで取得する契約**をIntelと締結しています。IntelのSEC提出資料でも8月18日が契約日として確認できます。
したがってIntel株には、
**政府出資観測**  
＋  
**SoftBank $2B investment**
という複数の公開材料が存在していました。

そして8月22日に正式発表です。
米政府はIntelへ**89億ドルを投資し、433.3百万株を1株20.47ドルで取得、9.9%を保有**する契約を発表しました。資金には未払いのCHIPS Act資金57億ドルとSecure Enclave関連32億ドルが使われました。
### したがってCase 03の判定は変わります
単純に計算すると、
**Trade → Official Announcement = 4 days**です。
しかし、
**First Public Report → Trade = 4 days**でもあります。

つまり、
```text
Aug 14
Government stake publicly reported
        ↓ 4 days
Aug 18
Intel shares purchased
        ↓ 4 days
Aug 22
Government stake formally announced
```
となります。

このため、Case 03について、

> 「政府出資発表の4日前に買った」

だけを書くのは不十分です。

より正確には、

> **Trump's accounts purchased Intel four days before the formal government investment announcement — but also four days after the possibility of that government investment had already been publicly reported.**

です。

これは非常に重要な違いです。
