# CocoNut-Humoresque

Contributor: [Hitoshi Suda / 須田仁志](https://www.sdhts.io) (suda.h@aist.go.jp)

## Summary

This corpus consists of subjective scores of voice attractiveness in 1,800 audio clips from Coco-Nut.

Each clip has 6-scale attractiveness scores (from 1 to 6) by at least 11 listeners (22 listeners for valid and test sets), listener by listener.

このコーパスは，Coco-Nut 中の 1800 音声に対する主観的な声質の好感度のデータからなります．

各音声につき 11 人以上（ただし valid セットおよび test セットについては 22 人以上）の聴取者による評点が，1 から 6 の 6 段階で，各聴取者ごとに付与されています．

## Structure

### listeners.csv

This file includes information about all the listeners. Columns `video1`, `video2`, and `video3` represent IDs of their favorite YouTube videos.

このファイルには全聴取者の情報が含まれます．`video1`，`video2`，`video3` の列には好みの YouTube 動画の ID が含まれます．

- gender: 0—male, 1—female, 2—not answered
- age: 0—10s, 1—20s, 2—30s, 3—40s, 4—50s, 5—60 or above, 6—not answered

### subsets.csv

This file includes information about subsets for corpus construction.

このファイルには，構築時に分割されたサブセットの情報が含まれます．

### train.csv / valid.csv / test.csv

These files include listener IDs and their 6-scale scores (from 1 to 6) for audio clips.

各音声ごとの，1 から 6 の評点と，その評点を与えた聴取者の ID が含まれます．

In valid and test sets, each audio clip belongs to two subsets; scores are included in a separate line for each subset and audio clip ID.

Valid セットおよび test セットでは，各音声が 2 つのサブセットに含まれているため，それぞれ独立した行で表記されています．

## Papers / 論文

- 須田仁志，渡邊亞椰，高道慎之介．「キミは私の声、好きかな?」 大規模主観評価による声質好感度コーパスの構築とその分析．研究報告音声言語情報処理（SLP），2024-SLP-152，2024.

## License

This corpus is provided under CC BY 4.0.

Copyright 2024 Hitoshi Suda
