# フブキボタン - 白上フブキのボイスボタン

![Version](https://img.shields.io/github/package-json/v/lonelyion/fubuki-button)
![Build](https://img.shields.io/github/workflow/status/lonelyion/fubuki-button/FBK-BTN-NG-CI)
![Last Commit](https://img.shields.io/github/last-commit/lonelyion/fubuki-button)
![Starts](https://img.shields.io/github/stars/lonelyion/fubuki-button)

README: [中文](https://github.com/oruyanke/fubuki-button/blob/master/README.md) | **日本語** | [English](https://github.com/oruyanke/fubuki-button/blob/master/README.EN.md)

> 新しい白上フブキのボイスボタン。私たちの目標は白上フブキの総合的なファンサイトを作ることです。

ホームページ https://sfubuki.moe

関連リンク:

* [白上フブキのYouTubeチャンネル](https://www.youtube.com/channel/UCdn5BQ06XqgXoAxIhbqw5Rg)
* [白上フブキのBilibiliチャンネル](https://space.bilibili.com/332704117)
* [白上フブキのTwitter](https://twitter.com/shirakamifubuki)

## 検討中の機能

- 生放送や動画のスケジュールを表示
- フブキのスタンプ/コラ画像のまとめ/検索
- YouTube/Bilibiliのデータを表示

## このプロジェクトへの貢献(コントリビュート)

GitHubの開発に直接参加する方法が分からない場合は、素材や意見を直接以下のメールアドレスに送信してください。([voice@sfubuki.moe](mailto:voice@sfubuki.moe))。またメールのタイトル、内容及びあなたのユーザーネーム（Bilibili、Twitterやその他）を記述してください。そうすることで私達は下のコントリビューターリストにあなたの名前を掲載することができます。

もちろん素材や意見をGitHubの[Issues](https://github.com/copperion/fubuki-button/issues)でページを作成することもできます。メールの場合と同じく、タイトルと内容を記述してください。

GitHubでの開発方法を知っている場合は、このプロジェクトをフォークして編集してください。編集が完了したら、プルリクエストしてください。各項目の編集に関しては以下をさんこうにしてください。

### 音声の追加または変更

音声データはmp3のビットレート128Kbpsで統一し、`static/voices/`に保存してください。対応するURLは`/voices/`に入れてください。

すべての音声データのメタデータは`assets/voices.json`で追加または修正を行ってください。

音声を変更する場合は、ブラウザのキャッシュ絡みの問題が起こらないよう、元のファイルを削除し、新しいファイル名でファイルを追加してください。ファイル名は、以前のものと同じものを使わないようにしてください。

### 翻訳

日本語と英語への翻訳が必要です！

ウェブページのテキストについては、 `assets/locales/` 内に各言語に対応した3つの.jsonファイルがあります。

音声テキストの翻訳ファイルは `aseets/voices.json` 内にあります。

## ローカルでのデプロイ

ローカル開発環境をデプロイする
このサイトはVue + NuxtJS + Vuetifyを使用して開発しています。

ローカル開発環境をデプロイするためには、まず最新版のNodeとYarnをインストールしてください。その後、以下の手順に従ってください。

 1. コードをforkしてcloneする。
 2. コードディレクトリに移動し、yarnを実行して依存関係をインストールする。
 3. `yarn dev`を実行することで、`localhost:3000`でローカル開発サーバーが起動される。ローカル開発サーバーでは、変更した結果をすぐに反映させることが可能です。
 4. デプロイ用ファイルをコンパイルするためには、`yarn generate`を実行してください。静的サイトのホスティングサービス（GitHub Pagesなど）に直接デプロイできるファイルがdist`ディレクトリで生成されます。

## コントリビューター

開発:

- [孤独のイオン](https://github.com/lonelyion)
- [Asrui Morus](https://github.com/Morxi)

オーディオクリップ：

- [孤独のイオン](https://github.com/lonelyion)
- hanyuu

特別協力：

- Bilibili [吹雪的猫咪茶铺](https://space.bilibili.com/431210892/)
- Bilibili [亡音ちゃん](https://space.bilibili.com/2613724)
- GitHub [Dakumasu](https://github.com/dakuamsu)
- GitHub [Yourein](https://github.com/Yourein)
- Twitter [ネコヤナ　こう](https://twitter.com/nekoy0212anagi)

## LICENCE

プログラム： [MIT License](https://github.com/oruyanke/fubuki-button/blob/master/LICENSE)

音声: [Hololive 二次创作条款](https://www.hololive.tv/terms)

このプロジェクトはファンによるもので、Hololive公式とは一切関係がありません
