# hinoyasai1984-afk.github.io

Senya Fujiが個人で作った小さなWebアプリをまとめるトップページ。GitHub Pagesのユーザーページ（アカウントのルートドメイン）として公開している。

公開URL: https://hinoyasai1984-afk.github.io/

## 運用ルール

**GitHub Pagesで新しくアプリを公開したら、必ずこのトップページ（`index.html`の`.app-grid`内）にカードを1つ追加すること。**

追加する情報:
- カテゴリタグ（例: 天気・気候、健康記録、資産形成）とアクセントカラー（`--tag-color`、他のカードと被らない色を選ぶ）
- アプリ名（`<h2>`）
- 1〜2文の説明（`<p>`）
- 公開先のGitHub PagesのURL
- リポジトリ名（`.app-link`に表示）

新しいカードは`.app-grid`の先頭に追加し、最新のものが一番上に来るようにする。

## 現在掲載中のアプリ

| アプリ | リポジトリ |
|---|---|
| 今週の地上波/BSアニメ番組表 | [anime-timetable](https://github.com/hinoyasai1984-afk/anime-timetable) |
| 地名で調べる天気・気候アプリ | [weather-climate-app](https://github.com/hinoyasai1984-afk/weather-climate-app) |
| 検査・通院タイムライン | [kensa-timeline](https://github.com/hinoyasai1984-afk/kensa-timeline) |
| 積立投資シミュレーター | [investment-simulator](https://github.com/hinoyasai1984-afk/investment-simulator) |
| 日本主要都市 気象データダッシュボード | [weather2](https://github.com/hinoyasai1984-afk/weather2) |

## ローカル確認

ビルド不要。`index.html`をブラウザで直接開くか、

```
python -m http.server 8000
```

で確認する。
