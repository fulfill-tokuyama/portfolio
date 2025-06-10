# Tokuyama Takashi Portfolio

バイブコーダーとしてのスキルと実績を紹介するポートフォリオサイトです。

## 特徴

- モダンでプロフェッショナルなデザイン
- レスポンシブ対応
- スムーズなアニメーション
- パフォーマンス最適化

## 技術スタック

- HTML5
- CSS3 (Flexbox/Grid)
- JavaScript (ES6+)
- Intersection Observer API
- レスポンシブデザイン

## セットアップ手順

1. リポジトリをクローン
```bash
git clone [リポジトリURL]
```

2. プロジェクトディレクトリに移動
```bash
cd portfolio
```

3. ローカルサーバーで実行
```bash
# Pythonの場合
python -m http.server 8000

# Node.jsの場合
npx serve
```

4. ブラウザで確認
```
http://localhost:8000
```

## ディレクトリ構造

```
portfolio/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── images/
│   ├── royal-brew.jpg
│   └── rc-house.jpg
└── README.md
```

## カスタマイズ

### 画像の追加
1. `images/` ディレクトリに画像を配置
2. `index.html` の該当箇所で画像パスを更新

### スタイルの変更
1. `css/style.css` の変数を編集
```css
:root {
    --primary-dark: #1a202c;
    --secondary-dark: #2d3748;
    --accent-blue: #3182ce;
    /* その他の変数 */
}
```

## ライセンス

MIT License

## 作者

Tokuyama Takashi 