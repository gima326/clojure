
<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN">
<html><head>
<meta name="GENERATOR" content="MSHTML 6.00.2800.1264"><meta http-equiv="Content-Type" content="text/html; charset=EUC-JP"><meta http-equiv="Content-Style-Type" content="text/css"><title>はじめてのClojure</title></head>





<body>

<table width="386" cellspacing="0" border="0" align="center">
<tbody><tr>
<td width="32%" valign="middle" nowrap="nowrap" height="50%" align="center"><font lang="JA"><img src="http://www.kohgakusha.co.jp/bookimages/4263m.jpg" width="121" height="173"></font></td><td width="68%" valign="middle" nowrap="nowrap" height="50%" align="center"><br><font size="5" lang="JA" color="#000000"><b>はじめてのClojure</b></font><br><font size="4" lang="JA"><b>サポート情報</b></font><br><font size="3" lang="JA"><del>最終更新2014年07月22日</del><br>最終更新2021年12月01日</font></td>

</tr>
</tbody></table>

<p>
  <font size="+1">
    <b><a name="Label001"></a>■本書のサポート情報</b></font>　[ <a href="http://www.kohgakusha.co.jp/support/clojure/index.html">http://www.kohgakusha.co.jp/support/clojure/index.html</a> ]　(更新2014年06月11日）</p>


<p>　　■サンプルプログラムのダウンロード（更新2014年6月11日）<br>
　　本書のサンプルプログラムは、以下からダウンロードできます。<br></p>
<hr width="98%" size="1">
　　・<a href="http://www.kohgakusha.co.jp/support/clojure/BeginningClojure.zip">BeginningClojure.zip</a><br>
<hr width="98%" size="1">
　　また、最新のファイルについては、以下のサイトからダウンロードしてください。<br>
<hr width="98%" size="1">
　　・<a href="https://github.com/nyampass/BeginningClojure" target="_blank">https://github.com/nyampass/BeginningClojure</a><br>
<hr width="98%" size="1">


<p><font size="2">
<br>
※サンプルファイルの使用にあたって生じたトラブルは、著者および工学社は一切の責任を負いません。また、サンプルなどは著作権法により保護されていま
す。個人で利用する目的以外には利用できません。ネットワークへのアップロードなどは、著者の許可無く行なうことはできません。
</font></p>

<p>　　■お詫びと訂正（更新2014年7月22日）<br>
　　本文中における下記の部分が間違っておりました。お詫びして訂正いたします。<br></p>


<table width="80%" cellspacing="5" cellpadding="3" border="0">
	<tbody><tr>
		<td width="20%" bgcolor="#AAAAAA" align="center">
		ページ
		</td>
		<td width="40%" bgcolor="#AAAAAA" align="center">
		誤<br>
		</td>
		<td width="40%" bgcolor="#AAAAAA" align="center">
		正<br>
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.17　最後のコード内
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		(def hoge []
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		(def<font color="#ff0000">n</font> hoge []
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.26　最後のコード内
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		(require <font color="#ff0000">use</font> '[clojure.string :as cstring])
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		(require '[clojure.string :as cstring])
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.30
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		「name」というキーワードのキーの値が
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		「<font color="#ff0000">:</font>name」というキーワードのキーの値が
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.35　最初のコード内
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		(print "x &gt; 0"))<font color="#ff0000">"</font>
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		(print "x &gt; 0"))
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.37　最後のコード内
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		:else (print<font color="#ff0000">ln</font> "other"))
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		:else (print "other"))
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.38　最後のコード内
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		(println "username "
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		(println "username<font color="#ff0000">:</font> "
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.42　3番目のコード内
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		{name age}}
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		<font color="#ff0000">[</font>name age]}
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.44　2番目のコード内
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		(defn <font color="#ff0000">in-</font>fizz-buzz []
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		(defn fizz-buzz []
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.46　2番目のコード内
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		(.getSystemClipboard (Toolkit/getDefaultToolkit))<font color="#ff0000">)</font>
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		(.getSystemClipboard (Toolkit/getDefaultToolkit))
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.47　2番目のコード内
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		(.setContents clipboard (StringSelection. text) nil))
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		(.setContents clipboard (StringSelection. text) nil))<font color="#ff0000">)</font>
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.55　最後のコード内
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		(require 'first-project.hoge :as hoge))<br>
(inc100 23)
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		(require '<font color="#ff0000">[</font>first-project :as hoge<font color="#ff0000">]</font>)<br>
(<font color="#ff0000">hoge/</font>inc100 23)
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.66　最後のコード内
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		@b → "a"<font color="#ff0000">)</font>
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		@b → "a"
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.68　最後のコード内
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		(count keycharacters))))))))
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		(count key<font color="#ff0000">-</font>characters))))))))
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.71　最後のコード内
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		<font color="#ff0000">core.clj</font><br>
(ns simple-web.core<br>
      (:use org.httpkit.server))
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		(ns simple-web.core<br>
      (:use org.httpkit.server))
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.68　最後のコード内※
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		(defn char-range [[first-char end-char]]<br>
  (map char (range (int first-char) (int end-char))))"
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		(defn char-range [[first-char end-char]]<br>
  (map char (range (int first-char) <font color="#ff0000">(inc</font> (int end-char)))))
		</td>
	</tr>
</tbody></table>
<br>
<p><font size="2">※元のコードでは、end-charが含まれない範囲の文字の集合を作っていたので、end-charの文字が含まれるよう修正しました。</font></p>

<br><br>

<p>　　■ごっそり、粗探しをした成果です（追加2021月12月01日）<br></p>


<table width="80%" cellspacing="5" cellpadding="3" border="0">
	<tbody><tr>
		<td width="20%" bgcolor="#AAAAAA" align="center">
		ページ
		</td>
		<td width="40%" bgcolor="#AAAAAA" align="center">
		誤<br>
		</td>
		<td width="40%" bgcolor="#AAAAAA" align="center">
		正<br>
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.8　最初のコード内<br>
		【バッククォートを用いていない】
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　'(if (not ~pred)
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　<font color="#ff0000">`</font>(if (not ~pred)
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.30　2番目のコード内<br>
		【キー重複】
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　{"y" 10.3 "y" 12.3}
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　{"<font color="#ff0000">x</font>" 10.3 "y" 12.3}
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.44
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　「fizz-buzz」関数は遅延シーケンスで実現されているので、
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　「<font color="#ff0000">in-</font>fizz-buzz」関数は遅延シーケンスで実現されているので、
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.62
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　「shorter.models<font color="#ff0000">.</font>」の中に「links」という「実体」を置く
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　「shorter.models」の中に「links」という「実体」を置く
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.82
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　「short<font color="#ff0000">l</font>er.handler」ネーム・スペースを作り、
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　「shorter.handler」ネーム・スペースを作り、
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.82
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　「src/shorter<font color="#ff0000">/</font>」フォルダの中に
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　「src/shorter」フォルダの中に
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.85
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　「ring.uti<font color="#ff0000">s</font>.response」ネーム・スペースにある
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　「ring.util.response」ネーム・スペースにある
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.86
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　「compo<font color="#ff0000">l</font>ure.handler/site」を使って、
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　「compojure.handler/site」を使って、
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.92
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　だたし、このように書く<font color="#ff0000">う</font>と、
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　だたし、このように書くと、
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.97
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　「mong<font color="#ff0000">o</font>er.result/updated-existing?」
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　「monger.result/updated-existing?」
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.94　最初のコード内
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　(ns mongo.users<br>
		　　(<font color="#ff0000"></font>require [monger.core :refer ～
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　(ns mongo.users<br>
		　　(<font color="#ff0000">:</font>require [monger.core :refer ～
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.97　最後のコード内
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　(ns mongo.users<br>
		　　(<font color="#ff0000"></font>require [monger.core :refer ～
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　(ns mongo.users<br>
		　　(<font color="#ff0000">:</font>require [monger.core :refer ～
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.98　最初のコード内<br>
		【引数を区切るスペース文字がない】
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　"users<font color="#ff0000">"{</font>:_id email})]
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　"users" {:_id email})]
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.98　最初のコード内
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　;; (change-password! "t.noborio@gmail.com" "pass<font color="#ff0000">2</font>" "pass2")
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　;; (change-password! "t.noborio@gmail.com" "pass" "pass2")
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.99　最後のコード内
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　(ns shorter.models.links-db<br>
		　　(<font color="#ff0000"></font>require [monger.core :as mg]
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　(ns shorter.models.links-db<br>
		　　(<font color="#ff0000">:</font>require [monger.core :as mg]
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.99　最初のコード内<br>
		【未定義の関数「new-id」呼び出し】
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　(let [<font color="#ff0000">new-id (new-id)</font><br>
		　　document (mc/insert-and-return "links" {:url url})
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　(let[<br>
		　　document (mc/insert-and-return "links" {:url url})
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.102
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　※テスト<font color="#ff0000">仕様</font>としているコード、
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　※テストしようとしているコード、
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.103　2番目のコード内
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　hoge.<font color="#ff0000">test.fuga</font>
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　hoge.fuga_test
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.103　最後のコード内
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　test/hoge/<font color="#ff0000">test/fuga</font>.clj
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　test/hoge/fuga_test.clj
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.104　最初のコード内
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　test/postcode/co<font color="#ff0000">t</font>e_test.clj<br>
                  　(ns postcode.core-test<br>
                  　　(:require [clojure.test :refer :all]<br>
		</td>
		<td width="40%" bgcolor="#cfcfcf">
                  　(ns postcode.core-test<br>
                  　　(:require [clojure.test :refer :all]<br>
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.109
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　自動で作成されるテスト<font color="#ff0000">。</font>ファイルです。
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　自動で作成されるテストファイルです。
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.110
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　多くの Clojure を利用したサービスが<font color="#ff0000">生まる</font>参考になればと思い、
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　多くの Clojure を利用したサービスが生まれる参考になればと思い、
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.119
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　compojureで「/repl<font color="#ff0000">/</font>」というパスが定義されていたので、
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　compojureで「/repl」というパスが定義されていたので、
		</td>
	</tr>
	<tr>
		<td width="20%" bgcolor="#cfcfcf" align="center">
		p.120　最初のコード<br>
		【実行の前提条件が不足している】
		</td>
		<td width="40%" bgcolor="#cfcfcf" align="center">
		ー
		</td>
		<td width="40%" bgcolor="#cfcfcf">
		　・利用しているライブラリの import、require の記述が必要。<br>
		　・USER、PASS の事前登録が必要。<br>
		　（ターミナル上で、「heroku config:set USER=xxxx PASS=xxxx」）<br>
		　・このコードが、どこで、どのように実行出来るのか明示すべき。
		</td>
	</tr>
</tbody></table>


<br>
<p align="right">（株）工学社　I/O編集部</p>
<hr>
<p>本書の内容に関するご質問／お問い合わせは、次の方法で工学社編集部宛にお願いします。</p>
<ol>
  <li><font size="4">返信用の切手を同封した手紙</font></li>
  <li><font size="4">往復はがき</font></li>

  <li><font size="4">FAX 03-5269-6031</font></li>
  <li><font size="4">E-mail <a href="http://www.kohgakusha.co.jp/mailform/info">問い合わせフォーム</a></font></li>

</ol>
<p>なお、電話によるお問い合わせはご遠慮ください。</p>
<p>※ご質問／お問い合わせの際、お客様の使用・動作環境などに添えて、具体的な症状をできるだけ詳しくお知らせください。<br>
※FAXでのご質問／お問い合わせの場合は、必ずお客様のFAX番号を明記してください。</p>
<hr>
<a href="http://www.kohgakusha.co.jp/support.html">戻る</a><br>



</body></html>
