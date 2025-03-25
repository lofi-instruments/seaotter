# キーマップ変更方法
[英語版ページはこちら(Click here for English Instructions)](https://github.com/lofi-instruments/seaotter/blob/main/keymap_instructions.md)

## Via

1. **Viaアプリのインストール、またはブラウザでViaを使用**  
   - [https://caniusevia.com/](https://caniusevia.com/)

2. **キーボードの接続**  
   - Sea Otter KeyboardをPCに接続してください。  
     ※キースイッチを押さずにUSBをコンピュータに接続  
   （もしキーを押しながら接続すると、キーボードはブートローダーモードに入ります。ブートローダーモードは、キーマップ変更ではなく、プログラム全体を書き換える際に使用します。ブートローダーモードではキーが反応せず、6秒後に通常モードに戻ります。）

3. **jsonファイルのアップロード**  
   「SETTINGS」タブ > Show Design Tab > 「DESIGN」タブ > Load Draft Definition > "[SeaOtter_via.json](https://github.com/lofi-instruments/seaotter/blob/main/codes/SeaOtter_via.json)"ファイルをアップロードする  

4. **キーマップを変更する**  
「CONFIGURE」タブ > 画面上部に表示されている1キーの四角をクリック（画面上で、選択されたキーが薄く点滅した状態になります） > 画面下半分のキーコード一覧から、変更したいものを選びクリック > 画面上部に表示されている1キーに新しいキーが割り当てられているのを確認  

5. **新しいキーマップに変更されたことを確認**  
「KEY TESTER」タブ > ラッコキーボードのスイッチを押す > 新しく割り当てたキーの位置が画面上で紫色になるのを確認する

以上で、キーマップの変更は完了です

----

## Remap

1. **Remapのサイトへアクセス**
   - [https://remap-keys.app/](https://remap-keys.app/)

3. **キーボードの接続**  
   - Sea Otter KeyboardをPCに接続してください。  
     ※キースイッチを押さずにUSBをコンピュータに接続  
   （もしキーを押しながら接続すると、キーボードはブートローダーモードに入ります。ブートローダーモードは、キーマップ変更ではなく、プログラム全体を書き換える際に使用します。ブートローダーモードではキーが反応せず、6秒後に通常モードに戻ります。）
   - 「キーボードをカスタマイズ」ボタンをクリック

4. **jsonファイルのアップロード**  
   "[SeaOtter_remap.json](https://github.com/lofi-instruments/seaotter/blob/main/codes/SeaOtter_remap.json)"ファイルをダウンロード後、ブラウザ画面中央の四角部分にjsonファイルをドロップするか、「インポート(.JSON)」ボタンをクリックしてjsonファイルをアップロードする  

5. **キーマップを変更する**  
  画面上部に表示されている1キーの四角をクリック（画面上で、選択されたキーが青色になります） > 変更したい内容のキーコードを入力するか、画面下半分のキーコード一覧から、変更したいものを選びドラッグし、画面上部の1キーにドロップする > 画面上部に表示されている1キーに新しいキーが割り当てられているのを確認  

6. **キーマップの書き込み**  
画面右上の「書き込み」ボタンをクリックする  

以上で、キーマップの変更は完了です

補足：Remapの使用方法については、下記サイトの解説が分かりやすいです。  
- [https://salicylic-acid3.hatenablog.com/entry/remap-manual](https://salicylic-acid3.hatenablog.com/entry/remap-manual)

