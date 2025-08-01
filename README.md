<h1 style="color:#0d47a1;"> データ分析体験アプリ</h1>
<img src="images/1.png" width="600">


<h2 style="color:#1976d2;"> 目的</h2>

このアプリは、<strong>だれでも簡単にデータ分析を体験</strong>できることを目指して開発されました。  
教育現場などでも活用しやすい設計となっており、<strong>直感的な操作でグラフ作成や回帰分析を行う</strong>ことができます。  

---

<h2 style="color:#1976d2;">🛠 主な機能</h2>

- 約60種類のオープンデータに対応    
- グラフは以下の<strong>6種類</strong>から選択可能：  
  - 散布図、折れ線グラフ、棒グラフ、円グラフ、ヒストグラム、箱ひげ図  
- <strong>単回帰分析</strong>による決定係数（R²）の算出  
- <strong>チームランキング機能</strong>を搭載し、ゲーム感覚で楽しめる  

---

<h2 style="color:#1976d2;"> 使い方</h2>

1. サイドバーで <strong>X軸・Y軸のデータを選択</strong>します  
<img src="images/2.png" width="600">
2. グラフの種類を選び、「📈 グラフ化」ボタンをクリックすると、右側にグラフが表示されます  
<img src="images/3.png" width="600"> 
3. グラフ下の「解析」セクションで、<strong>チーム名</strong>と<strong>仮説（なぜ関係があると思うか）</strong>を入力して「解析」をクリック  
<img src="images/5.png" width="600">
4. 回帰分析と決定係数が表示され、内容は自動的にランキングへ登録されます（最大5回まで）  
<img src="images/6.png" width="600">
---

<h2 style="color:#1976d2;"> ランキング発表モード（運営用機能）</h2>

以下の手順で、上位3チームの発表が可能です：  

<div>
1. チーム名に <code>security</code>、仮説に <code>0728</code> と入力して解析を実行  
<img src="images/8.png" width="600">
</div><br>

<div>
2. <code>output/team_ranking_full.csv</code> がダウンロードされます  
</div><br>

<div>
3. それを <code>data/</code> フォルダに保存し、<code>happyou.py</code> を実行  
</div><br>

<div>
4. <code>team_ranking_announcement.html</code> が生成され、ランキング発表ページとして利用できます  
<img src="images/10.png" width="600">
</div>

本アプリは、<strong>データリテラシー教育</strong>や<strong>統計学の導入教材</strong>としても活用できます。  
使いながら分析力を養い、楽しく競い合いましょう！  
