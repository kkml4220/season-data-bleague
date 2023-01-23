# season-data-bleague

![GitHub](https://img.shields.io/github/license/kkml4220/season-data-bleague)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/kkml4220/season-data-bleague)
![GitHub repo file count](https://img.shields.io/github/directory-file-count/kkml4220/season-data-bleague)

B リーグの試合データを[B リーグ公式サイト](https://www.bleague.jp/)からスクレイピングしたものです

## データ

次のシーズンのデータを用意しました

- 2018-2019
- 2019-2020
- 2020-2021
- 2021-2022

## データ内容

`csv`形式でまとめました．

### ヘッダー

- `Home`: ホームチーム
- `Away`: アウェイチーム
- `Hscore`: ホームチームのスコア
- `Ascore`: アウェイチームのスコア

次の表の形式に従います．

| Home   | Away   | Hscore | Ascore |
| ------ | ------ | ------ | ------ |
| 琉球   | A 東京 | 63     | 62     |
| 宇都宮 | 群馬   | 69     | 75     |
| 広島   | 北海道 | 83     | 75     |
| 琉球   | A 東京 | 82     | 75     |
| 秋田   | 茨城   | 84     | 63     |

- **試合中止が中止になったものも含まれます**ので注意してください．

## URLs

- B リーグ公式サイト：<https://www.bleague.jp/>

## Author

- 作成者 : 高橋 克征 (Takahashi Katsuyuki)
- E-mail : [Takahashi.Katsuyuki.github@gmail.com](Takahashi.Katsuyuki.github@gmail.com)

## License

"season-data-bleague" is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).
