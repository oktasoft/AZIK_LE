AZIK 外来語拡張
====
azik_le.tsv を Google 日本語入力にインポートしてお使いください。

要旨
----
[拡張ローマ字入力 AZIK](http://hp.vector.co.jp/authors/VA002116/azik/azikinfo.htm)
は、日本語に多い読みのパターンを楽に打てる入力方式です。
「拡張ローマ字入力」なので、多くの場合ローマ字入力と同じ打ち方も可能ですが、AZIK特有の入力方法を覚えれば以下のようにストロークを減らすことができます。
~~~~
例：

しんかんせん  
ローマ字入力：sinnkannsenn  
AZIK：skknsd  

かいちゅうでんとう  
ローマ字入力：kaityuudenntou  
AZIK：kqchddtp  
~~~~
カタカナ（外来語）も同様にストロークが減ります。
~~~~
例：

ウィンドウ  
ローマ字入力：winndou  
AZIK：wkdp  

フォーチュン  
ローマ字入力：fo-tyunn  
AZIK：fpcj  
~~~~
しかし、以下のような例外もあります。
~~~~
例：

デュアル  
ローマ字入力：dhuaru  
AZIK：delyuaru  

ツァイス  
ローマ字入力：tsaisu  
AZIK：tulaisu  
~~~~
AZIKでは、日本語にない読みに対してむやみに拡張せず、Lキーで小文字を入力することで対応します。
そのため、通常のローマ字入力のほうが打ちやすい場面も出てきます。

そこで、AZIKの基本方針はそのままに、一部の特殊な読みにもキーを割り当てることで、外来語を打ちやすくしました。
~~~~
例：

デュアル  
AZIK：delyuaru  
外来語拡張：dcyaru  

ツァイス  
AZIK：tulaisu  
外来語拡張：tsqsu  
~~~~

外来語拡張
----
### 「てゅ」 と 「でゅ」
AZIKには以下の拗音拡張があります。
~~~~
tgi てぃ
tgu とぅ

dci でぃ
dcu どぅ
~~~~
これに倣い、以下の定義を加えます。
~~~~
tgy てゅ
tgh てゅー
tgj てぃー
tgk てぃん
tgp とぅー
tgl とぅん

dcy でゅ
dch でゅー
dcj でぃー
dck でぃん
dcp どぅー
dcl どぅん
~~~~
### 「つぁ行」
ts\*（つぁ行）を加えます。
~~~~
tsa つぁ
tsd つぇん
tse つぇ
tsh つう
tsi つぃ
tsj つん
tsk つぃん
tsl つぉん
tsn つぁん
tso つぉ
tsp つぉー
tsq つぁい
tsw つぇい
tsz つぁん
~~~~
### 「すぃ」
以下の定義を加えます。
~~~~
syi すぃ
syk すぃん
~~~~
特殊拡張
----
AZIKのサブセットである特殊拡張のうち、以下の定義を加えます。
~~~~
ds です
ms ます
~~~~