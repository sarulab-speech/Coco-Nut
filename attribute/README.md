# Extracted Free-Form Characteristics Descriptions by Attribute

This directory contains CSV files organizing free-form characteristics descriptions into distinct attributes, extracted using ChatGPT.

このディレクトリには，ChatGPTを利用して自由記述文から属性ごとに内容を抽出し，CSVファイルにまとめたものが格納されています．

Contributor: Chihiro Ishikura (https://github.com/kura-karakaru)

Formatting: Aya Watanabe (https://github.com/AyaWatanabe)

## Description / 内容

The CSV files includes the following columns:

* Segment ID
* **Gender_[prompt ID]**
* **Pitch_[prompt ID]**
* **Speaking_rate_[prompt ID]**
* **Others_[prompt ID]**
  * These four columns represent attributes indicated in prompts for the speech segments identified by the Segment ID column.
  * The blank spaces indicate the attribute of the columns couldn't be retrieved.
* Annotator_[prompt ID]
  * Match the annotator column in the CSV file for characteristics descriptions.

CSVファイルに含まれる列は以下のとおりです

* 音声セグメントID
* **Gender_[prompt ID]（性別）**
* **Pitch_[prompt ID]（声の高さ）**
* **Speaking_rate_[prompt ID]（話速)**
* **Others_[prompt ID]（その他）**
  * セグメントID列で示されたIDの音声セグメントについてのプロンプトで示される属性を示しています．
  * 情報が取得できなかった項目は空白です．
* Annotator_[prompt ID]（アノテータID）
  * 声質表現文のcsvファイルのアノテータID列に一致します．

## Example / 例

/train.csv

| id   | characteristics_prompt_1                                                                   | annotator_1 |
| ---- | ------------------------------------------------------------------------------------------ | ----------- |
| 0000 | 30代くらいの男性の声。ゆっくりと穏やかな話し方でした。苦悩に満ちた、けだるそうな声でした。 | debussy4181 |

/attribute/train.csv

| id   | gender_1 | pitch_1 | speaking_rate_1 | others_1                       | annotator_1 |
| ---- | -------- | ------- | --------------- | ------------------------------ | ----------- |
| 0000 | 男性     |         | ゆっくり        | 30代, 苦悩に満ちた, けだるそう | debussy4181 |
