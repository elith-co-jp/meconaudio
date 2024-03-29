# Mecon Audio

Mecon Audio(Medical Conference Audio)は厚生労働省主催の先進医療会議の議事録の日本語での読み上げデータセットです。株式会社Elith ( https://elith.co.jp )が作成、公開しています。

24歳の女性話者1人に読み上げてもらいました。
- 先進医療会議: 2012年から2013年(一部)の議事録である2384文
- ITAコーパス: Emotion(100文) と Recitation(396 文) の計496文

読み上げ総時間は10時間となっています。

このデータセットは非営利の研究利用に限定されています。

商用利用は許可されておらず、商用利用を希望する場合は、まずご連絡してください。

## データセットの概要

MeconAudioデータセットは、「先進医療会議」での発表内容を録音した音声データと、それに対応する読み上げ用のテキストデータが含まれています。データセットの詳細は以下の通りです。

- データ形式: WAVファイル
- データ量: m001からm005までの合計10時間の音声データ
- テキストデータ: 読み上げ用のテキストファイル

## 入手方法

### 1) 非商用利用または研究目的の利用の場合:
- 無料公開セット（m001のみ) -> 以下のリンクからzipファイルをダウンロードし、解凍してご利用ください。
  * [v1-20230422-no_charge.zip](https://drive.google.com/file/d/1fR3Y-TRdow9T9Se2HQVwHIbJrZBijvV5/view?usp=share_link)
- フルセット(m001 ~ m005,ita1 ~ ita2) → ページ最下部の記載よりお問い合わせください。
### 2) 商用利用の場合:
- フルセット(m001 ~ m005,ita1 ~ ita2) → ページ最下部の記載よりお問い合わせください。

## データセットの詳細
### ディレクトリ構成
- /dataset/
  - wav/ ( 音声ファイル)
    - m001-0001.wav ~ m005-xxxx.wav, ita1-0001.wav ~ ita2-xxxx.wav ※無料公開セットはm001のみ
  - text/ (テキストファイル)
    - transcribe-text.txt
    - transcribe-hiragana.txt

### 音声ファイル
- 周波数：16kHz
- サンプルサイズ：16bit

### テキストファイル
- transcribe-text.txt・・・ 漢字カナ混じり(記号あり)
- transcribe-hiragana.txt (ひらがなのみ）

## 利用方法

このデータセットは、非営利の研究目的での利用が許可されています。

商用利用を希望する場合は、下記のお問い合わせから連絡して利用許可を得てください。

テキストデータのtranscribe-text(漢字カナ混じり)のみに関しては先進医療会議のライセンスに従い、CC BYとします。

- /dataset/
  - wav/ ( 音声ファイル)：非営利の研究目的での利用可、商用利用の場合はご相談
  - text/ (テキストファイル)
    - transcribe-text.txt：CC BY 4.0
    - transcribe-hiragana.txt：非営利の研究目的での利用可、商用利用の場合はご相談

ライセンスの詳細は[LICENSE](https://github.com/elith-co-jp/meconaudio/blob/main/LICENSE)ファイルをご覧ください。

## 商用利用
商用利用を歓迎しております。下記のお問い合わせからご相談ください。

## 引用方法

MeconAudioデータセットを論文や報告書で引用する場合は、以下の形式で引用してください。

Elith Inc., Mecon Audio, https://github.com/elith-co-jp/meconaudio, 2023

## 出典

「先進医療会議」（厚生労働省）https://www.mhlw.go.jp/stf/shingi/other-hoken_129195.html （2023年4月13日に利用）を加工して作成

## お問い合わせ

商用利用の許可やデータセットに関する質問がある場合は、以下の連絡先までお問い合わせください。

- お問い合わせ先: `contact@elith.co.jp`
- メールフォーマット:
```
お名前：
ご所属：
希望データセット：Mecon Audio フルセット(m001 ~ m005, ita1 ~ ita2)
利用目的： ※1)非商用利用または研究目的 または 2)商用利用 のいずれかを明記した上で、ご利用目的の詳細をお知らせください
```
