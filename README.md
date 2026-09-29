# 株式会社サンプル コーポレートサイト（たたき台）

架空の会社「株式会社サンプル」のホームページのたたき台です。
配色は青を基調とした仮デザインです（ダークモード対応）。色は `css/style.css` 冒頭の変数で一括変更できます。

## ページ構成

| ページ | ファイル | 主な内容 |
| --- | --- | --- |
| ホーム | `index.html` | メインビジュアル、私たちについて（概要）、サービス（抜粋）、お知らせ、会社概要への導線 |
| 私たちについて | `about.html` | ミッション、ビジョン、バリュー、代表メッセージ |
| サービス一覧 | `services.html` | サービスA〜Cの詳細、ご利用の流れ |
| 会社概要 | `company.html` | 基本情報、沿革、アクセス |

## ディレクトリ構成

```
.
├── index.html
├── about.html
├── services.html
├── company.html
├── images/
│   └── profile.jpg # 代表者プロフィール画像
├── css/
│   └── style.css   # 共通スタイル（仮）
└── js/
    └── main.js     # スマホ用メニューの開閉
```

## 確認方法

ビルド不要です。`index.html` をブラウザで直接開いてください。

## 表示イメージ（output/）

各ページのスクリーンショットを `output/` に格納しています。

| ページ | PC（1280px） | スマホ（375px） |
| --- | --- | --- |
| ホーム | `output/index_pc.png` | `output/index_sp.png` |
| 私たちについて | `output/about_pc.png` | `output/about_sp.png` |
| サービス一覧 | `output/services_pc.png` | `output/services_sp.png` |
| 会社概要 | `output/company_pc.png` | `output/company_sp.png` |
| メニュー展開時 | — | `output/menu_open_sp.png` |
