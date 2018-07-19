
## 【Visual C#】.NET Framework / VisualStudio環境に触れる
#### 本『作って覚えるVisualC# 2017』を参考に、いくつかのアプリを開発  

　【アプリの使用】 ※ Windowsのみ  
１、このページ右上の [Clone or download] → [Download ZIP] → DLしたフォルダーを解凍する  
２、好きなアプリをクリック → [〇〇〇.exe]で使用できます。  

| アプリ名 | 見た目 | 備考 |
| -- | -- | -- |
| 簡単計算プログラム | [![simplecals](https://user-images.githubusercontent.com/39142850/42465438-ec2e5fd6-83e6-11e8-95c4-b375aa308b8d.jpg)](https://github.com/aocattleya/TestVisualC-/blob/master/SimpleCals/SimpleCals/Form1.cs) | 数字以外は 0 |
| タイマー | [![timer](https://user-images.githubusercontent.com/39142850/42465442-f0d8d96c-83e6-11e8-8c87-dae8b94006c8.jpg)](https://github.com/aocattleya/TestVisualC-/blob/master/Timer/Timer/Form1.cs) | カウントダウン式 |
| 付箋メモ | [![fusen](https://user-images.githubusercontent.com/39142850/42465448-f4443470-83e6-11e8-849d-a9af699e5d13.jpg)](https://github.com/aocattleya/TestVisualC-/blob/master/Fusen/Fusen/Form1.cs) | [Esc]キーで終了 |
| 今日の占い | [![uranai](https://user-images.githubusercontent.com/39142850/42465589-5fdc3b4c-83e7-11e8-8977-0e032a09d581.jpg)](https://github.com/aocattleya/TestVisualC-/blob/master/Uranai/Uranai/Form1.cs) | 結果は5種類 |
| 間違い探しゲーム | [![kanjidifferencehunt](https://user-images.githubusercontent.com/39142850/42587763-b04c87fe-8576-11e8-9093-c569f9961a7f.jpg)](https://github.com/aocattleya/TestVisualC-/blob/master/KanjiDifferenceHunt/KanjiDifferenceHunt/Form1.cs) | 間違えると+10秒 |
| Twitter投稿アプリ | [![twitterpost](https://user-images.githubusercontent.com/39142850/42652758-56e00f00-864e-11e8-8f64-ca550ea70f44.jpg)](https://github.com/aocattleya/TestVisualC-/blob/master/TwitterPost/TwitterPost/Form1.cs) | 下記へ記載 [※1](#※1) |
| 間違いボール探しゲーム | [![movecircle](https://user-images.githubusercontent.com/39142850/42757022-6de15e00-8939-11e8-9a5f-84b647f7b0f8.jpg)](https://github.com/aocattleya/TestVisualC-/blob/master/MoveCircle/MoveCircle/Form1.cs) | 下記に記載 [※2](#※2)|
| 簡易家計簿 | [![myhousekeepingbook](https://user-images.githubusercontent.com/39142850/42778437-039a7b46-8978-11e8-88d4-8121a462e2ee.jpg)](https://github.com/aocattleya/TestVisualC-/blob/master/MyHouseKeepingBook/MyHouseKeepingBook/Form1.cs) | 下記に記載 [※3](#※3) |  
  
　  
　  
　  
### <a name="※1"></a>※1　Twitter投稿アプリ  
　手順：１、アプリの[Twitter連携]ボタンを押すとブラウザが立ち上がる  
　　　　２、ブラウザの[連携アプリを認証]を押すとPINコードが画面に出るのでアプリにコピーする  
　　　　３、アプリのテキストボックスにツイート内容を書いてツイートボタンをクリックすると投稿  
  
・『連携するとアプリからツイートが出来る』という機能となります。    
・ アプリ連携に抵抗がある方もいると思うので、心配な方は使用を控える  
　 又は、Twitterの[設定とプライバシー] → [アプリ連携] → [許可を取り消す]で連携解除できます。  
・ 連携したままでも特に何もありません。  
　  
  
　  
### <a name="※2"></a>※2　間違いボール探しゲーム  
  ★ ゲームのルール ★  
　  
  　  ・一つだけ違う文字があります。  
  　  ・見つけたら上の5種の中から同じ色のボールをクリック  
  　  ・間違えたら +10秒 されてボールの速度が落ちます。  
　  
　  
　  
### <a name="※3"></a>※3　簡易家計簿  
　下にある[追加ボタン]をクリックすると登録用の項目が表示されます。  

　■ 一覧表示 ■  
　　追加：日付, 分類, 品名, 金額, 備考  
　　変更：追加項目で登録した内容を変更  
　　削除：選択した一覧内容の1つ削除  
　　終了：アプリを閉じる  
　  
　■ 集計表示 ■  
　　入金合計 - 給料  
　　出金合計 - 食費, 雑費, 住居  
　　※ 追加ボタンで "分類" に指定した内容が入出金として集計  
　  
　　Q. 登録画面のカレンダーが大きく表示される。  
　　A. 現在"Windows7"で確認しています。  
　　　 カレンダー(MouthCalenderコントロール)は、Windowsのバージョンによって大きさが違うようです。  
　　 　Window10推奨、カレンダーの大きさ以外は同じです。  
　  
修正済：一覧表示(DataGridView)にそのまま記入するとエラーが出る
