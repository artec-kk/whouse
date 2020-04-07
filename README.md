# whouse
Scartch3.0で変数ブロックとそれを使用しているスプライトを調査するコマンド

## Usage

whouse.exe sb3_project [csv]

Scratch3.0のプロジェクトを渡すと、変数名とそれを使用しているスプライトのリストを下記のjson形式で出力します。  
>{'変数名1': ['スプライト1', 'スプライト2'...], '変数名2': ['スプライト1', 'スプライト3'...] ... }

csvオプションを付けるとcsv形式で出力します。  
>変数名1, スプライト1, スプライト2  
変数名2, スプライト1, スプライト3  
...

## Example


下記からダウンロードしたプロジェクト("Dear Lisa.sb3")に対して実行した結果です。  

https://scratch.mit.edu/projects/314166329/editor/


```
whouse.exe "Dear Lisa.sb3"
```

{'intro': ['Stage', 'Open Text', 'Control'], 'Message #': ['Stage', 'Open Text', 'Control', 'CB', 'Zinnea', 'mres', 'me_win', 'me_win2', 'Champ99', 'Lilyland', 'Khanning', 'KayOh', 'carmelo', 'Eric1', 'Eric2', 'Eric3', 'Me', 'ChrisG', 'Shruit'], 'card ready': ['Stage'], 'clone stop': ['Shruit']}

```
whouse.exe "Dear Lisa.sb3" csv
```

intro,Stage,Open Text,Control,
Message #,Stage,Open Text,Control,CB,Zinnea,mres,me_win,me_win2,Champ99,Lilyland,Khanning,KayOh,carmelo,Eric1,Eric2,Eric3,Me,ChrisG,Shruit,
card ready,Stage,
clone stop,Shruit,

