# Kaggle-chaii---Hindi-and-Tamil-Question-Answering
## Log
### 20211009
- Kaggle日記をつけ始めた
- chaii---Hindi-and-Tamil-Question-Answeringのコンペに元々joinしていたけど、今日から本格的にスタート
- コンペにnotebookの項ががないけど、notebook=codeでおけ？
### 20211010
- notebookのレベル高いな
- ドメイン知識ないと不利そう。ヒンディー語まじわからん。
- https://www.kaggle.com/thedrcat/chaii-eda-baseline/notebook。
  とりあえずこのベースラインから理解する。
- 記述が長くて文字が省略されていたから、下記の記述で設定変更
文字数
pd.set_option("display.max_colwidth", 10000)
行数
pd.set_option("display.max_rows", 10000)
- trainの２行目のタミル語をそのままgoogle翻訳に突っ込んだらこんな感じになった。もう一つはフレミングさんの人生に関する記述で、人の人生に関する記述が多いのかな？
#### context
カーリダーサ（デーヴァナーガリー：कालिदास）は、サンスクリット文学に優れたインドの詩人および劇作家です。カリダサの完全な歴史は知られていない。[1]しかし、Sakunthalam、Meghadootham、Iraguvamsam、Kumarasambavam、Malavikakkinimitram、Vikramorvasiyam、Rudu Samharamなどの彼の作品は、インドの言語文学において重要な役割を果たしています。彼はグプタ朝の5世紀に住んでいたと考えられています。[2] [3]彼の叙事詩は自然の美しさを描いており、当時住んでいた人々の文化を反映しています。\ NKalidasan;多くの古代および中世のテキストは、ウジャインの王であるヴィクラマディティヤがインド神話の詩人であったと信じています。紀元前1世紀にインド中部のマルワップ地方にある旧市街ウジャインを統治したと言われています。有名なヴィクラマディティヤが歴史的な名前ではなかったことを知っている人もいます。帝国のある時点で（a）チャンドラグプタ2世[ウィクラマディティヤ]（375-413）、クマーラグプタ[マヘンドラディティヤ]（413-455）、スカンダの3つの王朝グプタ[ウィクラマディティヤ]（455-467）が住んでいた可能性があります。現代のオディシャのさまざまな部分と、カリンガナドゥなどのアンドラプラデシュの一部。ナイフもベースにしています。さらに、彼のウジャインへの愛情は、彼の叙事詩であるクラウドエンジェルとトワイライトに深く示されています。[7]カーリダーサの起源に関する著作に基づいて書かれています。彼はまた、カリダサカシミールで生まれたと言われていますが、地元の支配者の支援を求めて南下しました。[8] [9] [10]。\ nカシミールの一般的な地理的特徴の詳細：小さな湖、ジャングルなど。丘。\ nカラによると、カシミールの重要な場所のいくつかを特定することができます。このようなサイトはカシミール以外ではあまり人気がないため、カシミールと密接に関係していない人には知られていない可能性があります。伝説によると、カシミールは（シャクンタラの）湖から形成されました。ニラダプラーナで言及されている伝説は、アナンダという部族の指導者が湖をろ過して悪魔を殺したというものです。アナンダのかつての湖（現在の土地）は、父親のカシヤバにちなんで「カシミール」と名付けられました。カラはさらに、当時カシミールの外ではその枝は知られていなかったと主張している。[11] \ n民芸によれば、カリダサは最初は知的な男として描かれ、マヒシャプリの王女と結婚した。[12]彼の妻の挑戦により、彼は偉大な詩人に成長したと考えられており、別の伝説によれば、彼はセイロンとしても知られるセイロンのクマラダサになり、カリダサはいくつかの裏切りのために暗殺されました。シャクンタラーの。天のマンガイメナカイと信者に生まれたプタルヴィサクンタラ。メナカイが信者の瞑想を解散する任務を負っていることを知って、信者は彼の妻（メナカイ）、セヤ（サクンタラ）を去ります。メナカイは締め切りが切れ、さらに進むことを余儀なくされたため、シャクンタラーをジャングルに残しました。セージカンバは、鳥に囲まれて保護されているサクンタラを見つけて育てます。ガンダルヴァもシャクンタラを精錬してしばらく住み、首都の反乱のために森を去りました。以前は、彼女に指輪をサインとして渡して、すぐに戻ってきました。ドゥフシャンタの記憶に長く住んでいるサクンタラは、いつか彼女のアシュラムを訪れる賢者ドゥルヴァーサを歓迎しません。したがって、彼女の記憶に住んでいる人は、怒っているドゥルヴァーサス・サクンタラを呪って彼女を忘れさせます。そのような環境で、DushyantはShakuntalaを完全に忘れます。彼女はまた、彼を探して彼の国に行くシャクンタラーを記念して彼に与えた指輪を失います。彼らにはバーラサンという名前の息子がいます。最後のシーンは、さまざまな苦難の後のDushyantとの再会です。この叙事詩は、自然の美しさを表現する上でのカーリダーサの素晴らしい個性を表しています。nCloud\ n \ nCuberの王室の使用人は、いくつかの作業を完了した後、彼のリーダーに会うためにメッセンジャーのクラウドメッセージを送信します。これは、他のタミル文学の使命のタイプに似ています。カリダサは、森、山、川、湖、花などのすべての天然資源を巡る雲の旅について説明しています。[15]ハイライトはKumarasambavamです。プルラヴァンはケーシーという名前の悪魔からウルヴァシを救出し、彼女をデベンドラに引き渡す。デベンドラはまた、プルラヴァンにウルヴァシを与えます。彼らはしばらく一緒に住んでいて、分裂しています。タミル語のように、プルラヴァンはついに仕切りによって引き起こされたトラウマから回復します。 SathasivaIyerによって翻訳されました。[16]カーリダーサはこの叙事詩で自然の季節について美しく歌っています。\ N関連項目\ nカテゴリ：詩人\ nカテゴリ：インドの詩人\ nカテゴリ：インドの作家\ nカテゴリ：サンスクリット文学\ nカテ
#### question
カーリダーサはどこで生まれましたか？
#### answer
カシミールで
- Jaccard係数の意味
<img width="659" alt="スクリーンショット 2021-10-10 17 25 46" src="https://user-images.githubusercontent.com/53257509/136688455-e99233f4-a993-4c47-a690-a4579d688118.png">

