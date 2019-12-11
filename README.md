# 教員側システム

想定される利用の流れに沿って各機能を説明します。

## ログイン

#### 1.ログイン

URLにアクセスし、共有させていただいたユーザーIDとパスワードを入力してください。

![1](https://user-images.githubusercontent.com/42822454/70636797-7b17cf80-1c79-11ea-9a01-96df8ba4f2a2.png)

#### 2.ログイン完了

ログインが完了すると、メニューが表示されます。

![2](https://user-images.githubusercontent.com/42822454/70637150-18730380-1c7a-11ea-9275-0e30121d750a.png)



## 教員登録

メニュー画面の「教員登録」の「編集」ボタンを押すことでページが遷移します。

![3](https://user-images.githubusercontent.com/42822454/70637360-70aa0580-1c7a-11ea-85da-c1878d936841.png)

#### 1.csvを選択

csvファイルで保存された情報を教員ユーザーとして登録し、権限を付与できます。

「ファイルを選択」ボタンでユーザー情報の入ったcsvファイルを選択し、送信でユーザー登録ができます。

登録されているユーザーIDはページ下部にて確認できます。

![4](https://user-images.githubusercontent.com/42822454/70637741-152c4780-1c7b-11ea-90a0-fa7ea8bc24e9.png)

#### 2.ユーザー登録完了

ユーザーの登録が完了すると、下記画面に遷移します。OKボタンを押してメニュー画面に戻ります。

![5](https://user-images.githubusercontent.com/42822454/70638847-e8792f80-1c7c-11ea-91d1-9105fdb28f23.png)

#### 3.注意点

- 登録できるファイル形式は.csvのみとなります。
- 文字コードは**UTF-8**で統一してください。文字化けの原因となります。
- 1行目のデータをを必ず「**ID,PASS**」としてください。1行目にユーザー情報を入力しても反映されません。(下図参照)
- 2行目以降に1行目の項目に沿った情報を入力してください。(下図参照)
- 既に登録されているユーザーIDは登録できません。

もしcsv登録時にエラーが発生した場合は上記の注意点をご確認ください。

![usr](https://user-images.githubusercontent.com/42822454/70638525-64bf4300-1c7c-11ea-8c3e-9e091d3260fa.jpg)



## 学生登録

メニュー画面の「学生登録／分析」の「編集」ボタンを押すことでページが遷移します。

![6](https://user-images.githubusercontent.com/42822454/70639040-3b52e700-1c7d-11ea-8b3b-60169078588e.png)



#### 1.csvを選択

csvファイルで保存された情報を学生ユーザーとして登録できます。

「ファイルを選択」ボタンでユーザー情報の入ったcsvファイルを選択し、送信でユーザー登録ができます。

登録されているユーザーIDはページ下部にて確認できます。

![7](https://user-images.githubusercontent.com/42822454/70639362-b9af8900-1c7d-11ea-80aa-dd6960b6ea05.png)

#### 2.ユーザー登録完了

ユーザーの登録が完了すると、下記画面に遷移します。OKボタンを押してメニュー画面に戻ります。

![5](https://user-images.githubusercontent.com/42822454/70638847-e8792f80-1c7c-11ea-91d1-9105fdb28f23.png)

#### 3.注意点

- 登録できるファイル形式は.csvのみとなります。
- 文字コードは**UTF-8**で統一してください。文字化けの原因となります。
- 1行目のデータをを必ず「**ID,PASS**」としてください。1行目にユーザー情報を入力しても反映されません。(下図参照)
- 2行目以降に1行目の項目に沿った情報を入力してください。(下図参照)
- 既に登録されているユーザーIDは登録できません。

もしcsv登録時にエラーが発生した場合は上記の注意点をご確認ください。

![usr](https://user-images.githubusercontent.com/42822454/70638525-64bf4300-1c7c-11ea-8c3e-9e091d3260fa.jpg)



## アンケート作成

メニュー画面の「アンケート作成／分析／ダウンロード」ボタンを押すことでページが遷移します。

![8](https://user-images.githubusercontent.com/42822454/70639641-190d9900-1c7e-11ea-9c5a-df862612acf3.png)



#### 1.新規アンケート登録機能へ移動

ページ上部の「新規アンケート登録」ボタンを押します。

![9](https://user-images.githubusercontent.com/42822454/70639947-8a4d4c00-1c7e-11ea-92f1-82e1ac19532d.png)



#### 2.事項の記入

使用するルーブリック、実施内容(アンケートのタイトルとして表示されます。)、実施期間を入力し「登録」ボタンを押します。

![10](https://user-images.githubusercontent.com/42822454/70640112-d00a1480-1c7e-11ea-801d-8107f0c9e61a.png)



#### 3.アンケート登録完了

アンケートの登録が完了すると、下記画面に遷移し、期間内に学生がアンケートに回答できるようになります。

OKボタンを押してメニュー画面に戻ります。

![11](https://user-images.githubusercontent.com/42822454/70640332-2414f900-1c7f-11ea-9871-82440a15628a.png)



## アンケート回答登録

#### 1.csvを選択

csvファイルで保存された回答結果を登録できます。

アンケート結果入力の横のプルダウンリストから実施内容を選択、「ファイルを選択」ボタンで回答結果の入ったcsvファイルを選択し、送信で回答の登録ができます。

![12](https://user-images.githubusercontent.com/42822454/70641422-f03ad300-1c80-11ea-936c-238cba066e68.png)

#### 2.回答結果登録完了

回答の登録が完了すると、下記画面に遷移します。OKボタンを押してメニュー画面に戻ります。

![5](https://user-images.githubusercontent.com/42822454/70638847-e8792f80-1c7c-11ea-91d1-9105fdb28f23.png)

#### 3.注意点

- 登録できるファイル形式は**.csv**のみとなります。
- 文字コードは**UTF-8**で統一してください。文字化けの原因となります。
- 1行目のデータをを必ず「**ID,分類名,構成要素,選択**」としてください。1行目にユーザー情報を入力しても反映されません。(下図参照)
- 2行目以降に1行目の項目に沿った情報を入力してください。(下図参照)

もしcsv登録時にエラーが発生した場合は上記の注意点をご確認ください。

![result](https://user-images.githubusercontent.com/42822454/70641629-3d1ea980-1c81-11ea-8fc2-660163ca17ac.jpg)



## 回答結果のダウンロード

メニュー画面の「アンケート作成／分析／ダウンロード」ボタンを押すことでページが遷移します。

![8](https://user-images.githubusercontent.com/42822454/70639641-190d9900-1c7e-11ea-9c5a-df862612acf3.png)



#### 1.アンケートデータの選択

「csvダウンロード」と書かれている列から、ダウンロードしたいアンケートのボタンを押します。

![13](https://user-images.githubusercontent.com/42822454/70642002-dbab0a80-1c81-11ea-8e6b-96b6a6892737.png)



#### 2.csvのダウンロード

回答結果がcsv形式でダウンロードが開始されます。文字コードはUTF-8で出力されます。



## アンケートの全体分析

メニュー画面の「アンケート作成／分析／ダウンロード」ボタンを押すことでページが遷移します。

![8](https://user-images.githubusercontent.com/42822454/70639641-190d9900-1c7e-11ea-9c5a-df862612acf3.png)

#### 1.アンケートデータの選択

「箱ひげ図」と書かれている列から、可視化したいアンケートの「分析」ボタンを押します。

**注意:可視化の表示には時間がかかります。**

![14](https://user-images.githubusercontent.com/42822454/70642702-06499300-1c83-11ea-805f-affab204aab3.png)



#### 2.箱ひげ図の表示

選択されたアンケートの統計がPlotly.jsにより箱ひげ図で可視化されます。

横軸がコンピテンシー項目、縦軸が項目の習得率(百分率)となります。

グラフをマウスオーバーさせると以下の情報が表示されます。

- 箱ひげ図
  - 最大値・最小値
  - 上限・下限
  - 第一四分位数・中央値・第三四分位数
- 外れ値
  - そのユーザーの習得率
  - ユーザーID



また、ページ右上のモードバーより、以下のような機能が利用できます。[詳細](https://help.plot.ly/getting-to-know-the-plotly-modebar/)

- グラフの移動・拡大・縮小
- 箱ひげ図をpngファイルで保存
- Chart Studioでの箱ひげ図の詳細確認・編集

![15](https://user-images.githubusercontent.com/42822454/70643105-c800a380-1c83-11ea-845d-ca667b71a7e5.png)

「戻る」ボタンでアンケートデータ選択メニューに遷移します。



## アンケートの個人分析

メニュー画面の「学生登録／分析」の「編集」ボタンを押すことでページが遷移します。

![6](https://user-images.githubusercontent.com/42822454/70639040-3b52e700-1c7d-11ea-8b3b-60169078588e.png)

#### 1.アンケートデータの選択

可視化したいユーザーのIDの「分析」ボタンを押します。

![16](https://user-images.githubusercontent.com/42822454/70644465-6988f480-1c86-11ea-870a-b32e4434ef49.png)



#### 2.アンケートの選択

可視化したいアンケートをプルダウンリストから選択し、「表示」ボタンを押します。

**注意:可視化の表示には時間がかかります。**

![17](https://user-images.githubusercontent.com/42822454/70644828-182d3500-1c87-11ea-961a-b5bd5c4b9785.png)



#### 3.箱ひげ図の表示

Plotly.jsにより個人の回答の習得率がひし形で、全学校の学生のアンケートの統計が箱ひげ図で可視化されます。

横軸がコンピテンシー項目、縦軸が項目の習得率(百分率)となります。

グラフをマウスオーバーさせると以下の情報が表示されます。

- 個人結果
  - 習得率

- 箱ひげ図
  - 最大値・最小値
  - 上限・下限
  - 第一四分位数・中央値・第三四分位数
- 外れ値
  - そのユーザーの習得率
  - アンケートのタイトル:ユーザーID



また、ページ右上のモードバーより、以下のような機能が利用できます。[詳細](https://help.plot.ly/getting-to-know-the-plotly-modebar/)

- グラフの移動・拡大・縮小
- 箱ひげ図をpngファイルで保存
- Chart Studioでの箱ひげ図の詳細確認・編集

![18](https://user-images.githubusercontent.com/42822454/70644998-6f330a00-1c87-11ea-804d-3a65104d32dc.png)

「戻る」ボタンで学生登録メニューに遷移します。



# 学生側システム

#### 1.ログイン

URLにアクセスし、登録した学生用のユーザーIDとパスワードを入力してください。

![19](https://user-images.githubusercontent.com/42822454/70645974-54619500-1c89-11ea-962a-4c9b6b212ae1.png)



#### 2.ログイン完了

ログインが完了すると、回答受付期間中のアンケート表示されます。

![20](https://user-images.githubusercontent.com/42822454/70646313-fe412180-1c89-11ea-86fa-22332502f875.png)



#### 3.アンケートの回答

回答画面では、

- 問題番号
- 残り問題数
- 質問内容（目標）
- 回答内容(ラジオボタン)

が表示されます。目標に対し当てはまるものをタップし、「つぎへ」をタップしてください。

**注意:回答中のページから他サイトに移動すると回答結果が正しく反映されない、またはアンケートの回答ができなくなる可能性があります。アンケート回答中は他サイトに移動しないでください。**

![21](https://user-images.githubusercontent.com/42822454/70646582-8f17fd00-1c8a-11ea-94ca-75fbcdf7dbd4.png)



#### 4.回答の終了

全ての回答が終了したら、以下のような画面になりますので、「ログアウト」をタップしてください。

![22](https://user-images.githubusercontent.com/42822454/70646660-b79ff700-1c8a-11ea-97e0-e504bc8206b6.png)
