# Privacy Policy — 台日地震監測 / 台日地震監視

> 🇹🇼 本 repo 託管「台日地震監測」iOS App 的隱私權政策頁面。
>
> 🇯🇵 本リポジトリは「台日地震監視」iOS アプリのプライバシーポリシーをホストしています。

---

## 🌐 公開 URL / 公開 URL

GitHub Pages 啟用後,政策頁將可透過以下網址公開瀏覽:

GitHub Pages を有効化後、ポリシーページは以下の URL で公開されます:

```
https://<your-username>.github.io/<repo-name>/privacy.html
```

此 URL 用於填寫:
この URL は以下に記入します:

- **App Store Connect** → App 隱私權 → 隱私權政策 URL
- **App Store Connect** → App プライバシー → プライバシーポリシー URL
- **App 內「關於」或「設定」頁面** (推薦但非必要)
- **アプリ内「アプリについて」または「設定」ページ** (推奨、必須ではありません)

---

## 🚀 部署到 GitHub Pages(三分鐘) / GitHub Pages へのデプロイ(3 分)

### 1️⃣ 建立 repo / リポジトリの作成

**繁中:**
1. 進入 GitHub → **New repository**
2. 命名,例如 `privacy-policy` 或 `eq-monitor-legal`
3. 設為 **Public**(GitHub Pages 免費版必須)
4. 勾選 Initialize with README

**日本語:**
1. GitHub → **New repository**
2. 名前を付ける(例:`privacy-policy` または `eq-monitor-legal`)
3. **Public** を選択(GitHub Pages 無料版に必須)
4. Initialize with README にチェック

### 2️⃣ 上傳 privacy.html / privacy.html のアップロード

從網頁拖放 / Web からドラッグ&ドロップ:
直接把 `privacy.html` 拖入 repo 即可。

或使用 git / git で:

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
# 將 privacy.html 放入此目錄 / privacy.html をこのディレクトリに配置
git add privacy.html
git commit -m "Add privacy policy"
git push
```

### 3️⃣ 啟用 GitHub Pages / GitHub Pages の有効化

1. Repo → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / `/(root)`
4. **Save**
5. 約 1 分鐘後,Pages 設定頁面最上方會顯示 URL
   約 1 分後、Pages 設定の上部に URL が表示されます

### 4️⃣ 驗證 / 動作確認

打開 URL,應顯示帶有語言切換功能的隱私權政策頁面。

URL を開くと、言語切替機能付きのプライバシーポリシーページが表示されます。

---

## 📝 部署前必填項目 / デプロイ前の必須項目

送審 App Store 前,請打開 `privacy.html` 並替換以下佔位符:

App Store 申請前に、`privacy.html` を開き、以下のプレースホルダーを置き換えてください:

| 佔位符 / プレースホルダー | 位置 / 場所 | 替換為 / 置き換え内容 |
|---|---|---|
| `[請填寫您的聯絡信箱]` | § 08 聯絡我們(中文版) | 您的聯絡 Email |
| `[ご連絡先メールアドレスをご記入ください]` | § 08 お問い合わせ(日本語版) | 您的聯絡 Email |

> 💡 用 `Cmd/Ctrl + F` 搜尋上述字串最快。
>
> 💡 `Cmd/Ctrl + F` で上記の文字列を検索すると最速です。

如 Bundle ID、AdMob App ID 或第三方服務有變更,請更新對應章節。

Bundle ID、AdMob App ID、第三者サービスに変更があった場合は、該当セクションを更新してください。

---

## 🔄 政策更新 / ポリシー更新

當需要修改政策時 / ポリシーを変更する際:

1. 編輯 `privacy.html` / `privacy.html` を編集
2. 更新 header 中的「最後更新日期 / Last Updated」/ ヘッダーの「最終更新日 / Last Updated」を更新
3. Commit & push — GitHub Pages 將自動重建(約 1 分鐘)
   Commit & push — GitHub Pages が自動的に再ビルドされます(約 1 分)

---

## 🪪 授權 / ライセンス

隱私權政策內容以「現狀」(as-is)提供,可自由改用於您的 App。

プライバシーポリシーの内容は「現状有姿(as-is)」で提供されます。ご自身のアプリへの利用は自由です。
