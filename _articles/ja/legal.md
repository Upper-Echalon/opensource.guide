---
lang: ja
title: オープンソースの法的側面
description: オープンソースの法的側面についてあなたが疑問に思うだろうことや、思いもしないだろうことについて。
class: legal
order: 10
image: /assets/images/cards/legal.png
related:
  - contribute
  - leadership
---

## オープンソースの法的意味を理解しよう

あなたの創造的な仕事を世界に共有することは、とても興奮することであり報われる経験になり得ます。しかし、それは懸念する必要があることをそもそも知らなかったような、多くの法的な事柄が必要になるということでもあるのです。ありがたいことに、あなたはゼロから始める必要はありません。あなたが必要な法的知識をここにまとめました。（読み進める前に、[免責事項](/notices/)をお読みください。）

## なぜオープンソースの法的な側面を気にするんですか？

よくぞ聞いてくれました！何か作品（文書、グラフィックス、コードなど）を創作するときには、その作品はデフォルトで排他的な著作権によって守られます。つまり、あなたは作品の作者として、他の人があなたの作品についてやって良いことについて意見があるということを法律は想定しています。

この事は、一般的にはあなたの作品を使ったり、コピーしたり、配布したり、修正することは、取り下げや捜査、訴訟のリスクが発生することを意味します。

しかし、オープンソースでは他の人が使って、修正して、それを共有することを推奨しており、通常とは異なる状況です。しかし、法的にはデフォルトで排他的な著作権で守られており、他の人に許可する事項を明確にライセンスで宣言する必要があります。

もしオープンソースライセンスを適用しないと、プロジェクトにコントリビュートする全員が、彼らの作業についての排他的な著作権を持つことになります。つまり、彼らのコントリビュートに関しては他の誰もそれを使ったり、コピーしたり、配布したり、変更することができません。そして、あなたもそれに含まれます。

最後に、あなたのプロジェクトの依存関係の中には、あなたが気付いていないような要求をするライセンスのものがあるかもしれません。プロジェクトのコミュニティや雇用主の方針によって、あなたのプロジェクトで特定のオープンソースライセンスを使うよう要求されることもあるかもしれません。これらの状況については、後述します。

## パブリックな GitHub プロジェクトはオープンソースですか？

GitHub 上で[新しいプロジェクトを作る](https://help.github.com/articles/creating-a-new-repository/)際、リポジトリをパブリックにするかプライベートにするか、2 つの選択肢があります。

![リポジトリの作成](/assets/images/legal/repo-create-name.png)

**GitHub 上のプロジェクトをパブリックにするということと、プロジェクトにライセンスを設定することは同じではありません。** パブリックプロジェクトは [GitHub の Terms of Service](https://docs.github.com/en/site-policy/github-terms/github-terms-of-service#3-ownership-of-content-right-to-post-and-license-grants) によって保護されます。これによって、他の人があなたのプロジェクトを見たりフォークすることを許可します。しかし、それ以外の点については許可していません。

もし、他に人に対してプロジェクトの利用、配布、変更、コントリビュートをしてもらいたいと思うのであれば、オープンソースライセンスをプロジェクトに含める必要があります。たとえあなたのプロジェクトがパブリックだったとしても、もしあなたがプロジェクトのソースコードを他のプロジェクトで使って良いと明記しない限りは、他の人はそのプロジェクトのコードのどの部分も合法的に使うことができません。

## 私のプロジェクトを守るのに必要な概要だけを教えてください。

あなたはラッキーです。なぜなら、今日ではオープンソースライセンスは標準化されていて、簡単に使うことができます。既存のライセンスを直接プロジェクトにコピーペーストすることが可能です。

[MIT](https://choosealicense.com/licenses/mit/) や [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) 、 [GPLv3](https://choosealicense.com/licenses/gpl-3.0/) は最も有名なオープンソースライセンスです。しかし、他の選択肢もあります。 [choosealicense.com](https://choosealicense.com/) では、そういったライセンスの全文と使い方の手順を確認することができます。

GitHub で新しいプロジェクトを作るときには、[ライセンスを追加するよう聞かれます](https://help.github.com/articles/open-source-licensing/)。

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/benbalter?s=180" class="pquote-avatar" alt="avatar">
  標準化されたライセンスは、ソフトウェアに対して他の人は何ができて何ができないのかを正確に把握していない人にとっては、代理人として機能します。どうしても必要な場合を除いて、カスタムしたり、修正したり、標準的でない条項は使わないようにしましょう。そういったものは、政府機関のコードから使う際の障壁となります。
  <p markdown="1" class="pquote-credit">
— @benbalter, ["Everything a government attorney needs to know about open source software&nbsp;licensing"](https://ben.balter.com/2014/10/08/open-source-licensing-for-government-attorneys/)
  </p>
</aside>

## 私のプロジェクトに適切なオープンソースライセンスはどれでしょう？

もし白紙からプロジェクトを始めるのであれば、 [MIT ライセンス](https://choosealicense.com/licenses/mit/)を使えば失敗することはないでしょう。短くて、理解しやすく、あなたの著作権表示を含むライセンスのコピーを維持し続ける限りは誰が何をやっても良いというライセンスです。必要であれば、別のライセンスを使ってプロジェクトをリリースすることもできます。

それ以外のケースでは、どれが適切なオープンソースライセンスかは目的によって異なります。

あなたのプロジェクトには **依存関係** があるはずです（もしくは今後必要になるでしょう）。例えば、オープンソースで Node.js のプロジェクトに取り掛かっているのであれば、 Node Package Manager (npm) を使ってライブラリを使っていることでしょう。あなたのプロジェクトで使っているこれらのライブラリはそれぞれのオープンソースライセンスを持っています。これらのライセンスが「寛容」（ライブラリを利用するプロジェクトのライセンスに条件をつけることなく、誰でも利用、修正、共有が可能）であれば、どういったライセンスのものでも使うことができます。よく使われる寛容なライセンスには、 MIT 、 Apache 2.0 、 ISC 、 BSD といったものがあります。

その一方で、もし依存するライブラリの中に「強いコピーレフト」（寛容なライセンス同様、誰でも利用してよいが、その条件としてライブラリを利用するプロジェクトも同じライセンスである必要がある）の場合、あなたのプロジェクトでも同じライセンスを使う必要が出るでしょう。よく使われる強いコピーレフトのライセンスには、 GPLv2 、 GPLv3 、 AGPLv3 といったものがあります。

また、 **コミュニティ** にあなたのプロジェクトを使ってもらったり、コントリビュートしてもらいたいとも思うでしょう:

* **他のプロジェクトから依存関係として使われるのを望みますか？** おそらく、関連するコミュニティで最も多く使われているライセンスを使うのが一番でしょう。例えば、 [MIT](https://choosealicense.com/licenses/mit/) は [npm ライブラリ](https://libraries.io/search?platforms=NPM)で最もよく使われています。
* **大企業に使ってもらいたいと思っていますか？** 大企業は全てのコントリビューターから特許ライセンスを望む傾向があります。この場合、 [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) があなた（と大企業も）をカバーします。
* **クローズドなソフトウェアではコントリビュートを使ってほしくないと思っているコントリビューターにもアピールしたいですか？** [GPLv3](https://choosealicense.com/licenses/gpl-3.0/) か（もしクローズドなサービスにも使われたくないと思っているのであれば） [AGPLv3](https://choosealicense.com/licenses/agpl-3.0/) が適しています。

あなたの勤める **企業** が、オープンソースプロジェクトには特定のライセンスを使うよう要求するかもしれません。例えば、企業のクローズドな製品であなたのプロジェクトを使えるよう、寛容なライセンスを要求するかもしれません。もしくは、あなたの企業だけがあなたのプロジェクトをクローズドなソフトウェアで使えるように、強いコピーレフトを追加でコントリビューター同意（後述します）を要求するかもしれません。もしくは、あなたの企業は社内標準や社会的責任、透明性などに関連したニーズを持っているかもしれません。こういったものは独自のライセンス戦略が必要となってきます。[企業の法務部門](#雇用主である企業の法務部門には何を伝える必要があるでしょうか)に相談してみましょう。

GitHub 上で新しいプロジェクトを作ると、ライセンスの選択が表示されます。上記のライセンスのうちのどれかを指定することで、あなたの GitHub プロジェクトはオープンソースとなります。他の選択肢を確認したい場合は、あなたのプロジェクトに適切なライセンスを見つけるために [choosealicense.com](https://choosealicense.com) を確認してみましょう。このサイトはあなたのプロジェクトが[ソフトウェアではない場合](https://choosealicense.com/non-software/)も使うことができます。

## プロジェクトのライセンスを変更したいときはどうしたら良いでしょう？

ほとんどのプロジェクトはライセンスを変更する必要は発生しません。しかし、時々状況が変わることがあります。

例えば、プロジェクトが成長するに従って依存関係やユーザーが増えたり、あなたの企業が戦略を変更したり、こういった理由によって異なるライセンスが必要になることがあります。それに加えて、もしプロジェクトを開始する際にライセンスを指定していなかったら、ライセンスをあとから追加するということはライセンスを変更することと実質上同じになります。ライセンスを追加したり変更する際に考えるべき重要なポイントは 3 つあります：

**事態は複雑です。** ライセンスの互換性や遵守を検討したり、誰がコピーライトを保持しているのかを調査することは、すぐに複雑で混乱するものだとわかるでしょう。新しいリリースやコントリビュートについてのみ、新しいが互換性のあるライセンスに切り替えるのと、過去のコントリビュートの全てのライセンスを切り替えることとは事情が異なります。ライセンスを変更したいと思い始めた時に、法務部門を巻き込みましょう。たとえプロジェクトのコピーライトの保有者からライセンスの変更について許可を得ている（もしくは得ることが可能）としても、プロジェクトの他のユーザーやコントリビューターへの影響をきちんと考慮しましょう。ライセンスの変更は、あなたのプロジェクトにおける「運営上の大きな出来事」だと考えるようにしましょう。そうすることで、プロジェクトの利害関係者と明確なコミュニケーションと相談を行い、物事が円滑に進むようになります。プロジェクト発足時に適切なライセンスを選んで使うべきなのはこういった事情のためです！

**プロジェクトの既存のライセンス。** もし既存のライセンスとこれから変更しようとしているライセンスで互換性があるのであれば、単に新しいライセンスを使い始めれば大丈夫です。なぜなら、もしライセンス A がライセンス B と互換性がある場合、ライセンス B の規約に従っているのであればライセンス A の規約も遵守していることになるからです（ただし、必ずしも逆は成り立ちません）。もし現在使っているのが寛容なライセンス（例えば MIT ）であれば、 MIT ライセンスと関連するコピーライト表示を保ちつづける（つまり、 MIT ライセンスの最低限の条件は守り続ける）かぎりは、より条件の多いライセンスに変更することができます。しかし、現在使っているライセンスが寛容でなく（例えばコピーレフトやライセンスがない場合）、あなたが単一のコピーライト保持者ではない場合、単純にライセンスを MIT に変更することはできません。基本的に寛容なライセンスでは、プロジェクトのコピーライト保有者は前もってライセンスの変更を許可しているということになります。

**プロジェクトの既存のコピーライト保有者。** もしあなたがプロジェクトの単独のコントリビューターなのであれば、あなたかあなたの会社がプロジェクトの単独のコピーライト保有者です。あなたやあなたの企業が望むどんなライセンスの追加や変更をすることができます。そうでない場合は、ライセンスの変更にあたって同意を取る必要のある他のコピーライト保有者がいるかもしれません。それは誰でしょうか？あなたのプロジェクトにコミットをしたことがある人は第一の候補になります。しかし、場合によってはコピーライトを保有しているのは彼らの雇用主かもしれません。他にも、ほんの少しのコントリビュートをした人々について考慮が必要かもしれません。一定量以下の変更しかないコントリビュートに対してはコピーライトを保有できないという明確なルールがない場合もあるからです。比較的小さくて歴史の浅いプロジェクトであれば、イシューやプルリクエストで全ての既存のコントリビューターからライセンスの変更についての同意を取ることは実現可能かもしれません。巨大で歴史の長いプロジェクトであれば多くのコントリビューター、場合によってはその相続人を探し出す必要があります。 Mozilla は Firefox や Thunderbird と関連するソフトウェアのライセンスを変更するのに多くの時間（2001 年ー 2006 年）を費やしました。

こういったことを行う代わりに、既存のオープンソースライセンスの範疇を超えて、前もってコントリビューターとある特定の条件でライセンス変更を許容するような同意（後述の追加のコントリビューターアグリーメント）を結ぶこともできます。こうすることで、ライセンス変更の複雑さは少しは緩和されます。事前に弁護士からより多くの助けを得ることができるでしょうし、実際にライセンス変更をする際にはプロジェクトの利害関係者を明確なコミュニケーションができるでしょう。

## 私のプロジェクトでは追加のコントリビューターアグリーメントが必要でしょうか？

おそらく必要ありません。大部分のオープンソースプロジェクトでは、オープンソースライセンスはインバウンド（コントリビューターから）もアウトバウンド（他のコントリビューターやユーザー向け）の両方のライセンスとして使うことができます。もしプロジェクトを GitHub 上においているのであれば、 GitHub の利用規約によってインバウンドとアウトバウンドが同じであるということがデフォルトとして[明記されています](https://help.github.com/en/github/site-policy/github-terms-of-service#6-contributions-under-repository-license)。

追加のコントリビューターアグリーメントはしばしば Contributor License Agreement (CLA) と呼ばれます。これを作ることで、プロジェクトのメンテナーは運用上の手間が必要になってきます。どのくらいの手間がかかるかはプロジェクトとやり方によります。簡単な同意であれば、コントリビューターに対してプロジェクトのオープンソースライセンスに従ってコントリビュートする権利があるとクリックひとつで同意できる様になるでしょう。より複雑な同意になると、法務のレビューとコントリビューターの雇用主の署名が必要になるかもしれません。

加えて、「書類作業」が必要になることによって、中にはその作業が不必要、理解しがたい、公正ではない（プロジェクトのオープンソースライセンスによって、同意を受ける人や一般の人がコントリビューターより多くの権利を得る場合）と感じる人が出てくるかもしれません。このような状況では、追加のコントリビューターアグリーメントはプロジェクトのコミュニティからは友好的でないと受け取られるかもしれません。

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/bcantrill?s=180" class="pquote-avatar" alt="avatar">
  Node.js では CLA を廃止しました。こうすることによって、 Node.js のコントリビューターになる敷居が下がり、コントリビューターの層を広げる事ができます。
  <p markdown="1" class="pquote-credit">
— @bcantrill, ["Broadening Node.js Contributions"](https://www.tritondatacenter.com/blog/broadening-node-js-contributions)
  </p>
</aside>

追加のコントリビューターアグリーメントがプロジェクトに必要になってくるケースにはこういったものがあります：

* あなたの弁護士が全てのコントリビューターが明示的にコントリビュート規約に同意する（オンラインかオフラインでの _サイン_）必要があると判断した場合。これはおそらく、オープンソースライセンスだけでは十分でない（たとえ実際には十分だったとしても！）と感じているからでしょう。もしこれが唯一の懸念なのであれば、あるオープンソースライセンスを支持する旨のコントリビューターアグリーメントで十分なはずです。 [jQuery Individual Contributor License Agreement](https://web.archive.org/web/20161013062112/http://contribute.jquery.org/CLA/) が、軽量な追加のコントリビューターアグリーメントの良い例です。
* あなたや弁護士が、開発者が行う全てのコミットは承認されていると表明してほしいと考える場合。[Developer Certificate of Origin](https://developercertificate.org/) の要件はこれを達成するプロジェクトの数です。例えば、Node.js コミュニティは彼らが以前使っていた CLA の[代わりに](https://nodejs.org/en/blog/uncategorized/notes-from-the-road/#easier-contribution)、DCO を[使っています](https://github.com/nodejs/node/blob/HEAD/CONTRIBUTING.md)。あなたのリポジトリでDCOの執行を自動化するためのシンプルなオプションは [DCO Probot](https://github.com/probot/dco) を使うことです。
* プロジェクトで使っているオープンソースライセンスに特許許諾が明記されておらず（ MIT ライセンスのように）、全てのコントリビューターから特許許諾を取る必要がある場合。これは、コントリビューターの中にあなたのプロジェクトやプロジェクトのコントリビューター、ユーザーを巨大な特許ポートフォリオの対象にする企業があるかもしれないためです。 [Apache Individual Contributor License Agreement](https://www.apache.org/licenses/icla.pdf) は、 Apache License 2.0 に記載されている特許許諾をコピーした追加のコントリビューターアグリーメントで、一般的に使われています。
* プロジェクトがコピーレフトライセンスを使っているが、プロプライエタリバージョンも提供する必要がある場合。この場合、全てのコントリビューターから、コピーライトをあなたに割り当てるか、寛容なライセンスを（パブリックに対してではなく）あなたに対して許諾する必要があるでしょう。 [MongoDB Contributor Agreement](https://www.mongodb.com/legal/contributor-agreement) はこの種の同意の例です。
* プロジェクトが成熟するに連れてライセンスを変更する必要があると考えており、コントリビューターに前もってライセンス変更の同意を得ておきたい場合。

追加のコントリビューターアグリーメントがあなたのプロジェクトで必要なのであれば、コントリビューターの手間を最小限に留めるために [CLA assistant](https://github.com/cla-assistant/cla-assistant) のような連携ツールを使うことを検討しましょう。

## 雇用主である企業の法務部門には何を伝える必要があるでしょうか？

もしあなたがオープンソースプロジェクトを企業の従業員としてリリースしようとしているのであれば、まずはじめに法務部門にプロジェクトをオープンソース化しようとしている旨を伝えましょう。

メリット・デメリット両方ありますが、たとえプロジェクトが個人的なものだとしても彼らに伝えることを検討しましょう。おそらくあなたは「従業員知的財産同意」を会社と結んでいるでしょう。これは企業があなたのプロジェクトに対してある程度の管理をすることを認めるもので、特に企業のビジネスに関係したプロジェクトであったり、プロジェクトの開発をするのに何らかの企業のリソースを使う際に関係してきます。あなたの企業はあなたに許可を出す _べき_ です。もしかしたら、従業員に優しい知的財産同意や企業のポリシーで既に許可されているかもしれません。もし許可されていないのであれば、交渉する（例えば、プロジェクトを行うことがあなたの職業訓練になったり開発目標になることを説明する、など）事もできますし、別の良い企業を見つけるまでプロジェクトを進めるのを一旦止める事もできます。

**もし企業内のプロジェクトをオープンソース化しようとしているのであれば、**必ず法務部門に知らせるようにしましょう。おそらく法務部門の方で、企業のビジネス要件やあなたのプロジェクトの依存関係のライセンスにきちんと遵守していることを確実にするための専門知識に基づいて、どのオープンソースライセンス（と追加のコントリビューターアグリーメントもあるかもしれません）を使うべきかの方針を決めているかもしれません。もしそういった方針がないのであれば、ラッキーです！法務部門はあなたと一緒にどういった方針が良いのかについて熱心に取り組むべきです。その際、幾つかの考慮事項があります：

* **サードパーティのソースコード:** あなたのプロジェクトでは他の人が作った依存関係を使っていたり、他の人が書いたソースコードを含んでいたり使っていたりしますか？もしそれらがオープンソースなのであれば、そのプロジェクトのオープンソースライセンスを遵守する必要があります。そのためにまずはサードパーティのオープンソースライセンス（上記参照）と整合するライセンスを選ぶ所からはじめましょう。もしあなたのプロジェクトでサードパーティのソースコードを修正したり配布する場合は、法務部門からコピーライト表記を保持しているかどうかといった、サードパーティのオープンソースライセンスの条件を満たしているかどうかを聞かれるでしょう。もし使っているサードパーティのプロジェクトがオープンソースライセンスを持っていないのであれば、おそらくそのサードパーティのメンテナーに[オープンソースライセンスを追加する](https://choosealicense.com/no-license/#for-users)ようお願いする必要があるでしょう。そして、もし追加してもらえなかった場合は、彼らのコードをあなたのプロジェクトで使うのは止めましょう。

* **ビジネス上の秘密：** プロジェクトの中に企業が世間一般に見られたくないと思うような何かが含まれていないかどうかを調べましょう。もし含まれているのであれば、秘密にしておきたいコードを取り除いた後に残りの部分をオープンソース化することができます。

* **特許：** あなたの企業はプロジェクトをオープンソース化することで[一般開示](https://en.wikipedia.org/wiki/Public_disclosure)に繋がるような特許を申請中ですか？残念ながら、オープンソース化を待つよう依頼されるかもしれません（もしくは企業は賢明にも特許の申請を再検討するかもしれません）。もし、大きな特許ポートフォリオを持つ企業の従業員からもプロジェクトにコントリビュートしてもらう事を望むのであれば、法務部門はコントリビューターからの特許許諾を明記したライセンス（ Apache 2.0 や GPLv3 のような）を使うよう要求するか、追加のコントリビューターアグリーメント（上述参照）を望むでしょう。

* **商標：** あなたのプロジェクトの名前が[既存の商標と衝突していないか](../starting-a-project/#名前の衝突を避ける)入念に確認しましょう。もしあなたの企業の商標をプロジェクトで使っている場合は、それによって利害の対立が発生しないかを確認しましょう。 [FOSSmarks](http://fossmarks.org/) はフリーやオープンソースプロジェクトの文脈における商標について理解するための実践的なガイドです。

* **プライバシー：** あなたのプロジェクトではユーザーのデータを収集していますか？企業のサーバーに秘密の通信を行っていませんか？法務部門が企業の方針や外部の規制を遵守するために手助けしてくれます。

もし企業内で初めてのオープンソースプロジェクトを公開しようとしているのであれば、オープンソース化の道のりには上記以外にもあるかもしれません（でも心配しないでください、ほとんどのプロジェクトでは大きな問題はありません）。

長期的には、法務部門は企業がオープンソースに関わることでより多くのことを安全に獲得する助けとなります：

* **従業員のコントリビュートポリシー：** 従業員がどのようにオープンソースにコントリビュートするかを定めた社内規約を作ることを検討しましょう。明確な規約を作ることで従業員同士の混乱も減りますし、従業員に対して企業が最も関心のあるオープンソースプロジェクトに業務の一環であれ空き時間でコントリビュートする手助けにもなります。 Rackspace の [Model IP and Open Source Contribution Policy](https://processmechanics.com/2015/07/23/a-model-ip-and-open-source-contribution-policy/) が良い例です。

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/vanl?s=180" class="pquote-avatar" alt="avatar">
  パッチに関連した知的財産を手放すことで従業員の知識ベースと名声を築く事ができます。そうすることで、その企業は従業員の能力を高め、自律的に働くことに投資していることを示すことができます。こういったメリットは、士気の向上や従業員の維持にも繋がります。
  <p markdown="1" class="pquote-credit">
— @vanl, ["A Model IP and Open Source Contribution Policy"](https://processmechanics.com/2015/07/23/a-model-ip-and-open-source-contribution-policy/)
  </p>
</aside>

* **何をリリースすべきですか？：** [(ほぼ)すべて？](http://tom.preston-werner.com/2011/11/22/open-source-everything.html) もし法務部門が企業のオープンソース戦略を理解し、それに投資している場合は、あなたの努力を妨害するよりもむしろ助けとなってくれるでしょう。
* **コンプライアンス：** たとえあなたの企業が 1 つもオープンソースプロジェクトをリリースしていないとしても、他の人のオープンソースソフトウェアを使っているはずです。 [Awareness and process](https://www.linuxfoundation.org/blog/blog/why-companies-that-use-open-source-need-a-compliance-program/) can prevent headaches, product delays, and lawsuits.

<aside markdown="1" class="pquote">
組織は、\[「寛容」と「コピーレフト」\]の両方のカテゴリにフィットするライセンス戦略、コンプライアンス戦略を確立しなければなりません。まずは使っているオープンソースソフトウェアとそのサブコンポーネント、依存関係に適用されているライセンス条項の記録を保持する所から始めましょう。
  <p markdown="1" class="pquote-credit">
— Heather Meeker, ["Open Source Software: Compliance Basics And Best Practices"](https://techcrunch.com/2012/12/14/open-source-software-compliance-basics-and-best-practices/)
  </p>
</aside>

* **特許：** あなたの企業は [Open Invention Network](https://www.openinventionnetwork.com/) に参加したいと望むかもしれません。これはメンバーが有名なオープンソースプロジェクトを使うための共有の防御的パテントプールです。もしくは[代替となる特許ライセンス](https://www.eff.org/document/hacking-patent-system-2016)を調査してみましょう。
* **組織運営：** [社外の法人](../leadership-and-governance/#プロジェクトを運営するのに法人は必要ですか)にプロジェクトを移すことが理にかなっているときは特に必要です。
