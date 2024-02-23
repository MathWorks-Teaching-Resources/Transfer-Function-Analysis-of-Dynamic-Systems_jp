# 動的システムの伝達関数解析 (Transfer Function Analysis of Dynamic Systems) 

[![View Transfer-Function-Analysis-of-Dynamic-Systems_jp on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://jp.mathworks.com/matlabcentral/fileexchange/110610-transfer-function-analysis-of-dynamic-systems_jp)

[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Transfer-Function-Analysis-of-Dynamic-Systems_jp)

**Curriculum Module**  
_Created with R2020b. Compatible with R2020b and later releases._  

## 日本語訳について ##
それぞれのファイルについて、MATLABコードがないファイルとMATLABコードを記述した解答ファイル(末尾にSolnとついているもの)があります。現在、日本語訳はMATLABコードがないファイルのみ翻訳しています（Solnファイルのテキスト部分は英語のままです。テキスト部分の内容は日本語化されたものと同一です）。

## 概要 ##

このカリキュラムモジュールには、動的システムについての伝達関数の解析を学ぶためのインタラクティブな[ライブスクリプト](https://www.mathworks.com/products/matlab/live-editor.html) と[MATLAB&reg; アプリ](https://www.mathworks.com/products/matlab/app-designer.html) が含まれています。最初のスクリプトでは、学生はODEから伝達関数を導出し、インパルス応答、ステップ応答、強制応答を計算することを学びます．続くスクリプトでは、極-零点プロットと周波数領域の解析を行います．このモジュール全体を通して，生徒は伝達関数を応用して物理的および電気的システムの力学を解析します．最後のレッスンでは、降圧コンバータ内のLCフィルタの周波数領域解析を行います。また、ラプラス変換の復習も含まれているので、再確認することができます。これらのレッスンは、講義の一部として、あるいは教育現場での実習として、あるいは授業外のインタラクティブな課題として使用することができます。

ライブスクリプト内の説明に沿って練習問題や課題を進めていくことができます。各ライブスクリプトを 1 セクションずつ実行することから始めてください。スクリプトまたはセクションの実行を途中で停止するには（たとえば、アニメーションの進行中など）、MATLABツールストリップのLive EditorタブのRUNセクションにあるStopボタンを使用します。

## お勧めの事前演習 ##
[MATLAB入門](https://matlabacademy.mathworks.com/details/matlab-onramp/gettingstarted) – MATLABの基礎について2時間で学べる無料のオンラインコース。<br>
[MATLAB によるシンボリック計算](https://matlabacademy.mathworks.com/details/introduction-to-symbolic-math-with-matlab/symbolic) – MATLABのシンボリック演算について学ぶための２時間の自学自習形式のコース。Online Training Suiteのライセンスをお持ちの方（大学の包括ライセンスなど、ご利用中のライセンスに含まれている場合があります）のみ利用可能です。

## 詳細 ##
**`Part0_ConceptReview.mlx, Part0_ConceptReviewSoln.mlx`**  
ラプラス変換について復習するインタラクティブな授業。

<img src="https://user-images.githubusercontent.com/81383420/122928267-b055b100-d337-11eb-962d-80c290c1e6a6.gif" width="500">

**学習到達目標:**
- 手計算とシンボリック演算でラプラス変換を計算する
- ラプラス変換の性質を説明する
- 初期値問題を解くためにラプラス変換を用いる
- 線形時不変(LTI)作用素の定義を復習する

## ##
**`Part1_TransferFunctionBasics.mlx, Part1_TransferFunctionBasicsSoln.mlx`**  
伝達関数の導出と時間応答について、解析的に求めたりMATLABで計算する方法を学ぶインタラクティブな授業。

<img src="https://user-images.githubusercontent.com/81383420/122928938-573a4d00-d338-11eb-80ef-2c979eb17236.png" width="550">

**学習到達目標:**
- 伝達関数を手計算で求める
- シンボリック演算を使って伝達関数を求める
- システムのインパルス応答、ステップ応答、強制応答を数値的に計算してプロットできる
- システムのステップ応答と強制応答を解析的に求めることができる
- 時間応答の物理的な意味づけを説明することができる

## ##
**`Part2_PoleZeroAnalysis.mlx, Part2_PoleZeroAnalysisSoln.mlx`**  
（未翻訳）極-零解析について学ぶ授業。
<!-- 
<img src="https://user-images.githubusercontent.com/81383420/122929255-bb5d1100-d338-11eb-8d05-7aa7b6666f71.png" width="550">

**学習到達目標:**

（未翻訳）  
- Describe how the transfer function of a DC motor is derived
- Identify the poles and zeros of a transfer function
- Assess the stability of an LTI system based on the transfer function poles
- Relate the position of poles in the s-plane to the damping and natural frequency of a system
- Explain how poles of a second-order system relate to its dynamics
- Examine how transfer function zeros affect the dynamics of a system
-->
## ##
**`Part3_FrequencyDomainAnalysis.mlx, Part3_FrequencyDomainAnalysisSoln.mlx`**  

（未翻訳）  
伝達関数を使った周波数領域解析が学べるインタラクティブな授業。
<!-- 
<img src="https://user-images.githubusercontent.com/81383420/122929840-65d53400-d339-11eb-8a8a-2c1522bbfcf0.gif" width="550">
  
**学習到達目標:**

（未翻訳）  

- Explain how a Bode plot is generated
- Use MATLAB to numerically calculate the frequency response of a transfer function
- Discuss how features of the Bode plot relate to characteristics of physical systems
- Describe how to derive a differential equation model for a buck converter with an LC filter
- Apply the Bode plot to analyze an LC filter in a buck converter
-->
## ##
**`polesApp.mlapp`**  

極とゼロをグラフィカルに配置することで伝達関数をつくることができるMATLABアプリです。インパルス応答とステップ応答を計算し、プロットすることもできます。

## 利用製品 ##
MATLAB, Symbolic Math Toolbox&trade;, Control System Toolbox&trade;

## ライセンス ##
このモジュールのライセンスについては、リポジトリの [LICENSE.TXT](license.txt) をご覧ください。

## Educator Resources ##
* [Featured Courseware](https://www.mathworks.com/academia/courseware/course-materials.html)
* [Teach with MATLAB and Simulink](https://www.mathworks.com/academia/educators.html)
* [MATLAB Grader](https://www.mathworks.com/products/matlab-grader.html)

ご質問やご感想は <a href="mailto:onlineteaching@mathworks.com">MathWorks online teaching team</a>までお願いいたします。日本語での対応をご希望の場合、<a href="mailto:cse-jp@groups.mathworks.com">カスタマーサクセスエンジニア</a>までご連絡ください。

# #

_Copyright 2022 The MathWorks, Inc._
