# リアルタイム湾曲ミラー

スマホの内カメラを起動し、リアルタイムで顔を湾曲させるHTMLアプリです。

## GitHub Pagesで公開する手順（PC不要・iPhone想定）

### 1. GitHubアプリまたはSafariでGitHubにログイン
GitHubアカウントがない場合は作成してください。

### 2. 新しいリポジトリを作成
- Repository name: `warp-mirror`
- Publicを選択
- Add a README fileはONでもOFFでも可

### 3. `index.html` をアップロード
このZIPをiPhoneで解凍し、`index.html` をGitHubリポジトリ直下にアップロードしてください。

GitHubアプリまたはブラウザで以下を実行します。
- リポジトリを開く
- `Add file`
- `Upload files`
- `index.html` を選択
- `Commit changes`

### 4. GitHub Pagesを有効化
リポジトリの設定で以下を選択します。

- `Settings`
- `Pages`
- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/root`
- `Save`

### 5. 公開URLを開く
数十秒〜数分後に、以下のようなURLで開けます。

`https://<あなたのGitHubユーザー名>.github.io/warp-mirror/`

このURLはHTTPSなので、iPhoneのSafariでもカメラが起動しやすくなります。

## 使い方

1. 公開URLをSafariで開く
2. `カメラを起動` を押す
3. カメラ権限を許可
4. 画面をドラッグして歪み中心を顔に合わせる
5. 下部スライダーで歪み具合を調整

## 注意

- iPhoneでは、ローカルHTMLを直接開くとカメラが動かない場合があります。
- GitHub PagesのHTTPS URLで開いてください。
- カメラが動かない場合は、Safariの設定でカメラ権限を確認してください。
