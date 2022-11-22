# Project Sprint

## ![](images/pjs_og.png)

<span style="font-size: 200%">[Project Sprint (v3.3)](JA/v3.3/README.md)</span>

## Project Sprint とは

Project Sprint は、定例会議を活用したプロジェクト推進のためのフレームワークです。本ドキュメントは、Project Sprint を体系立てた文章にまとめ、オープンソースのメソッドとして公開しているものです。

Project Sprint 及び本ドキュメントは、2020年のリリース以降大小さまざまなアップデートを繰り返し、今現在も進化し続けています。

**▼現在の最新ドキュメント**  
[Project Sprint (v4.0-alpha)](JA/v4.0-alpha/README.md)

-----

## はじめての方へ

本ドキュメントは、個々のプロジェクトチームの自律性や創造性の発揮を支援するための本質的な内容に重点を置きたいとの思いで記述されています。そのため、プロジェクトの推進を手取り足取り支援できるような細かい導入マニュアルや利用ガイドは今のところ置いておらず、基本的な概念や価値観と実践方法、そしてそれらの理解を助けるための記述をまとめたものになっています。

はじめての方にとっては、少しとっつきにくいと感じられることもあるかと思いますので、スムーズに理解いただくために、下記の順番でお読みいただくことをおすすめします。

1. Project Sprint の構成や、理解する上で重要な前提・用語を把握する
　[&#9758; はじめに](JA/v4.0-alpha/introduction.md)
2. Project Sprint の核となる概念や価値観に触れる
　[&#9758; フレームワーク](JA/v4.0-alpha/framework.md)
3. 具体的な行動の指針や実践イメージを把握する
　[&#9758; チュートリアル](JA/v4.0-alpha/tutorial/README.md)
4. チュートリアルの理解を踏まえ、改めてフレームワークの内容を理解する
　[&#9758; フレームワーク](JA/v4.0-alpha/framework.md)

## Project Sprint の想定読者と活用方法

このドキュメントの活用方法は、読者の方が置かれている状況によって異なります。

<table border="2">
　<tr>
   <th>読者</th><th>目的</th><th>お願いしたいフィードバック観点</th>
 </tr>
 <tr>
    <td valign="top">プロジェクトマネジメントの経験<font color="#F082A0">あり</font>
    <br>
    Project Sprintの実践経験<font color="#F082A0">あり</font>
    </td>
    <td rowspan="2" valign="top">自身の実践経験とProject Sprintの<b>記述に乖離がないか確認</b>する
    <br>
    <br>
    自身の<b>実践知をフィードバック</b>しProject Sprintを発展させる
    <br>
    <br>
    バージョンアップの際の差分を確認し、<b>最新の内容をインプット</b>する
    </td>
    <td valign="top">実践知（Project Sprintを実践してみて良かった点や、うまくいかなかった点）
    <br>
    <br>
    新たな理論（Project Sprintが取り込むべき考え方やまだ記述されていない論点）
    <br>
    <br>
    Project Sprintの導入や活用に関する疑問・質問
    </td>
</tr>
<tr>
    <td valign="top"> プロジェクトマネジメントの経験<font color="#007bbb">なし</font>
    <br>
    Project Sprintの実践経験<font color="#F082A0">あり</font>
    <br>
    </td>
    <td valign="top">実践知（Project Sprintを実践してみて良かった点や、うまくいかなかった点）
    <br>
    <br>
    Project Sprintの導入や活用に関する疑問や、質問
    </td>
</tr>
<tr>
    <td valign="top"> プロジェクトマネジメントの経験<font color="#F082A0">あり</font>
    <br>
    Project Sprintの実践経験<font color="#007bbb">なし</font>
    <br>
    <br>
    ※&nbsp;新しい方法論としてProject Sprintをインプットしたいと考える方
    <br>
    <td valign="top">概念としてのProject Sprintを理解し、核となっている<b>行動規範や価値観を把握</b>する
    <br>
    <br>
    Project Sprintの<b>特徴や利点を理解</b>する
    </td>
    <td valign="top"> Project Sprintに対する共感・違和感
    <br>
    <br>
    Project Sprintの導入や活用に関する疑問や、質問
    </td>
</tr>
<tr>
    <td valign="top"> プロジェクトマネジメントの経験<font color="#007bbb">なし</font>
    <br>
    Project Sprintの実践経験<font color="#007bbb">なし</font>
    <br>
    <br>
    ※&nbsp;プロジェクトマネジメントの経験はないが、Project Sprintに興味がある方
    <br>
    </td>
    <td valign="top"> Project Sprintの<b>概要を理解</b>する</td>
    <td valign="top">---</td>
</table>

## フィードバックを歓迎します！

Project Sprint は、プロジェクトの現場で得られた実践知のフィードバックを受けることにより、アップデートを繰り返してきました。

- 不確実で変化の多いプロジェクトが増える中、プロジェクトに関わる人の苦悩を少しでも減らしたい
‐ プロジェクトに関わるすべての人が、プロジェクトで自分の能力を最大限活かせるようしたい

事務局のメンバーはそんな思いで、今現在もProject Sprint を進化させるべく、試行錯誤を繰り返しています。どのようなかたちや内容であれ、このメソッドに関心やご意見、共感をお寄せいただけることを嬉しく思います。また、Project Sprintの発展に貢献したいと考えてくださる方も歓迎します。

**＜フィードバックの方法＞**

GitHubの[Discussions](https://github.com/copilot-jp/project-sprint/discussions)へお寄せください。
- Discussionsとは、GitHubのオープンなコメントシステムです。
‐ 入力に当たっては、運用ルール（[Operation Rules](https://github.com/copilot-jp/project-sprint/wiki/Method-operation-rules)）をご参照ください。
