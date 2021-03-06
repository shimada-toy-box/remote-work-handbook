---
title: "同期コミュニケーション（オンライン会議など）"
weight: 10
description: "電話やオンライン会議など、相手と時を同じくしてコミュニケーションするときの Tips をまとめています。"
# bookFlatSection: false
# bookToc: true
# bookHidden: false
# bookCollapseSection: false
# bookComments: true
date: 2020-10-22T00:00:00+09:00
lastmod: 2020-11-09T14:03:00+09:00
---

# 同期コミュニケーション（オンライン会議など）

## 概要

同期コミュニケーションとは、オンライン会議など、お互いがお互いの時間を共有しコミュニケーションを成立させるものである。ここではオンライン会議（Teams、Zoom、Meet、Webexなど）を開催・参加する際の注意点や推奨方法についてまとめる。

## 音質

音質が悪い時点で、双方向コミュニケーションは欠損している。相手の発声が聞こえずに、何度も聞き返すのはお互いにとって大きなストレスになる。

そのため、いかに音質を上げていくかが重要なポイントとなる。

### ヘッドセット、イヤフォンマイクの活用

できるだけ、USB接続の有線ヘッドセットを活用する。ヘッドセットはマイク位置が固定されるため、音質が安定しやすい。ヘッドセットが入手困難である場合は、イヤフォンマイクが活用できる。

イヤフォンマイクは口とマイクとの距離が一定にならない、服のこすれる音を拾うなどデメリットがあるが、後述する内蔵マイクよりは音質が良い。

PCに内蔵されたマイクは可能であれば避けるべきだ。なぜならば、キーボードなどの打鍵音や周囲の音を集音するためだ。環境によってはエコーも発生しやすい。ただし、周囲が静かな環境である場合には活用できる。

無線ヘッドセット、イヤフォンマイクも活用できるが次のデメリットがある。たとえば、電波干渉による音質低下（途切れ）、Bluetoothによる遅延、電池切れのリスクなどがある。特に、一時的な途切れはセルフチェックや会議の序盤で気づきづらく、会議中に問い返しが発生するリスクが高まる。

### （ノートPCの場合）ACアダプタの接続

オンライン会議はCPUへの負担が非常に高い。ノートパソコンはバッテリー駆動のとき、稼働時間を稼ぐためにCPUはフルパワーを出せない状態になっていることがある。安定性向上のためには、ACアダプタを接続した上でオンライン会議に接続し、CPUが全力で動作できるようにする。

### 周囲で雑音が多い場合はマイクをミュートする

雑音が思った以上に相手に届けてられており、他の参加者の聞き取りに悪影響を与えている場合がある。周囲に雑音が多い場合は、マイクをミュートする。また、議事録を取得する場合などは、キーボードの打鍵音をマイクが拾ってしまうため、同様にマイクをミュートする。

反対に周囲が静かな環境では、常にマイクをアンミュートしても良い。この場合、マイクのミュート・アンミュートにかかる操作時間がないため、レスポンスがクイックになり、笑い声なども自然に相手に伝わるようになる。

## 宅内ネットワーク環境の改善

オンライン会議では、ネットワーク品質が重要になる。パケットロスやゆらぎが発生すると、音声品質に影響が出るためだ。現代の音声コーデックは、パケットロスなどに応じて、動的に音質（サンプリングレートなど）を上下させるため、ネットワーク品質は安定しているほど良い。

有線LANは無線LANに比べて品質が安定するため、利用可能であれば有線LANが好ましい。無線LANのみであっても、無線アクセスポイントとの距離を物理的に近づける、または中継器などの活用で電波強度を確保することで、品質を安定させる。

## 映像の利用

### カメラ映像はONを推奨

カメラ映像は表示しておいたほうが、相手に情報量を多く与えられる。たとえば、何らかのプレゼンをしているときに、相手の顔のリアクションから理解度をある程度推察できる。仮にカメラ映像が完全に非表示だと、プレゼンターは暗闇に話しているのに近い環境になる。

ただし、カメラ映像のONは必須ではない。たとえば、以下のようなケースだ。

- カメラ映像を常時表示することで、ストレスを感じる場合はOFFでも構わない
- 人によっては一件のオンライン会議のために、化粧などの準備が必要になるかもしれない

ネットワーク環境が安定しない場合は、映像OFFによりコミュニケーションをスムースにできる。

なお、部屋のレイアウトなどの都合から背景が気になり、カメラ映像をOFFにしたい場合もある。アプリの仕様によるが、背景のぼかし機能、またはバーチャル背景によって実際の部屋の背景を隠せる。

カメラ映像をONする文化がない場合もある。オンライン会議開始時に、自ら顔出ししてスタートすると、双方でカメラ映像をONにしやすい場合がある。

### 光源の配置に気を付ける

後ろに明るい光源（たとえば窓や照明）がある場合、カメラの映像を表示していても顔が暗く見えてしまう（逆光）。暗く見えていると、情報源となる表情が見えなくなり、話し手に与える情報が減少する。部屋のレイアウト上難しい場合もあるが、光源が自身の後ろにこないような位置に座ると良い。

## 運用ルール

### 一人がリモートであれば【全員リモート】

リモート一人に対して、複数人が会議室で集まるオンライン会議の場合、多くの弊害が存在する。弊害とはたとえば次のような内容だ。

- 会議室側の盛り上がりに、リモート側がついていけない
- 会議室側の遠方者の声が収音されず、リモート側が聞こえない
- 会議室側で「これ」とディスプレイをポイントされて議論が進むが、リモート側がわからない

そのため、一人でもリモート参加する参加者がいる場合は、集合するのではなく個別に会議参加する。

何らかの事情により、会議室に集まって会議に参加する場合は、ノートPCの内蔵マイクで参加するのではなく、専用のカンファレンスマイクを利用する。

### 会議時間の設定

在宅勤務の場合、移動時間が存在しないため、連続してオンライン会議に参加できてしまう。そのため、オフラインであれば移動時間などで取れていたちょっとした休憩が取りづらくなる。連続してオンライン会議を実施しないために、スケジュール予約やファシリテーションで工夫する（1時間の会議であれば45分間で予約する、5－10分前に終わるなど）。

### 早めに入ってアイスブレイク

余裕があれば、5-10分前から会議に参加しておき、早めに入ってきた参加者と雑談する。これにより、信頼関係の強化やアイスブレイクを狙える。

## 画面共有時のTips

### 画面共有は大きめに映す

Word/Excelの画面を共有する際はリボンを畳み、画面を有効活用する。PowerPointでは面倒がらずにスライドビューにする。画面の解像度が低い場合、リボンだけで画面の上部の多くを占めてしまい、効果的に情報量を与えられない。また、画面転送では細かいところが潰れがちである。

スクリーンシェア時は、ズームレベルを150%程度にすることが望ましい。受信側の画面では共有している画面のほか、参加者ビデオやミュートボタン、チャットウィンドウなどが表示されており、共有している画面は発表者が思う以上に小さく表示されている。資料の内容を共有するときは各アプリケーションのズーム機能で、ユーザーインターフェースの動作を共有したいときは拡大鏡機能を適宜使うことで、必要な個所にフォーカスして説明できる。

### 自分自身でモニターする

オンライン会議の発表者は2台以上の端末から会議に参加することで、片方の端末で発表しながらもう片方で参加者に見えている画面を確認（モニター）する方法がある。この方法は会議参加端末が2台以上必要になるが、オンライン会議参加者にどのような表示がされているかリアルタイムで確認できる。2台目は会議に参加できるのであれば、PCに限らずスマートフォンやタブレットでもよい。また、オンライン会議アプリによっては、画面共有側ではなく参加者のカメラ映像も選択できるため、リアクションを比較的リアルタイムに確認可能だ。

{{< button relref="async-communication" >}}次へ（非同期コミュニケーション）{{< /button >}}
