# Coco-Nut (Corpus of connecting NIHONGO utterance and text) corpus

Japanese follows English. / 日本語の記述は英語に続きます．

Coco-Nut corpus is an corpus including Japanese speech and it's voice characteristics descriptions.

Coco-Nutコーパスは日本語音声および話者の声質を表現する自由記述文を含む音声合成用のコーパスです．

Project page: https://sites.google.com/site/shinnosuketakamichi/research-topics/coconut_corpus

## Description / 内容

This corpus consists of speech audio, transcription and voice characteristics description.

The voice characteristics descriptions are in this repository, separated into train, validation, and test csv files. These csv files include:

* segment id (corresponding to wav file names)
* characteristics_prompt_1~5
  * more than 1 per segment in train set, 5 for validation and test sets.
* annotator_1~5
  * note that the same annotator writes several characteristics prompts.

The speech audio and transcriptions are currently in preparation. We plan to distribute them through the Informatics Research Data Repository (https://www.nii.ac.jp/dsc/idr/index.html).

このコーパスは日本語音声と書き起こし文，および声質表現文からなります．

声質表現文はこちらのリポジトリで公開します．学習・検証・評価セットに分けてcsvファイルに記述しております．内容は以下のとおりです

- 音声セグメントID（音声セグメントのファイル名と対応）
- characteristics_prompt_1~5（声質表現文）
  - 音声セグメント1件につき，学習セットは1件以上，検証および評価セットは5件収録されています．
- annotator_1~5（アノテータID）
  - 1人のアノテータが複数の音声セグメントに対して声質表現文を付与しています．

音声及び書き起こし文は現在準備中です．情報学研究データリポジトリ（https://www.nii.ac.jp/dsc/idr/index.html）を通しての配布を予定しています．

## Terms of use / 使い方

The voice characteristics descriptions within this repository is licensed under CC BY 4.0 ([https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)). For the speech audio and transcriptions, the terms of use will adhere to the guidelines specified by the Informatics Research Data Repository.

本リポジトリ内の声質表現文はCC BY 4.0（[https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)）にてライセンスされます．音声データと書き起こし文は，音声資源コンソーシアムの利用規約に基づいて使用してください．

## Contributors / 作成者

Aya Watanabe / 渡邊 亞椰 (University of Tokyo / 東京大学)

Shinnosuke Takamichi 高道 慎之介 (@forthshinji, University of Tokyo / 東京大学)

Yuki Saito / 齋藤 佑樹 (University of Tokyo / 東京大学)

Detai Xin / 辛 徳泰 (University of Tokyo / 東京大学)

Hiroshi Saruwatari / 猿渡 洋 (University of Tokyo / 東京大学)

## Paper / 論文

Aya Watanabe, Shinnosuke Takamichi, Yuki Saito, Wataru Nakata, Detai Xin, Hiroshi Saruwatari,
"Coco-Nut: Corpus of Japanese Utterance and Voice Characteristics Description for Prompt-based Control,"
Proc. ASRU, 2023.
渡邊 亞椰，高道 慎之介，齋藤 佑樹，辛 徳泰，猿渡 洋，
"Coco-Nut: 自由記述文による声質制御に向けた多話者音声・声質自由記述ペアデータセット,"
日本音響学会2023年秋季研究発表会, 2023.

## Contact

For any inquiries, please contact Shinnosuke Takamichi (shinnosuke_takamichi@ipc.i.u-tokyo.ac.jp).

本コーパスに関するお問い合わせは，高道 慎之介 (shinnosuke_takamichi@ipc.i.u-tokyo.ac.jp) にお願いいたします．
