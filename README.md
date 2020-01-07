﻿# AI-100-DesignImplementAzureAISol
AI100T01A ILT コースのラボ ファイル


## ラボ 1: 技術的な要件を満たす

このラボでは、ワークショップのケース スタディを紹介し、Microsoft Cognitive Services スイート内でツールを構築できるように、ローカル ワークステーションと Azure インスタンスにツールをセットアップします。

## ラボ 2: ボットの Computer Vision 機能を実装する

このハンズオン ラボでは、Cognitive Services (特に Computer Vision API) を使用して、エンド ツー エンドでインテリジェント コンソール アプリケーションを作成する方法について説明します。ここでは ImageProcessing ポータブル クラス ライブラリ (PCL) を使用します。その内容と、自分で作成したアプリケーションでの使用方法についても説明します。

## ラボ 3: 基本的なフィルタリング ボット

このラボでは、ユーザーのチャット ウィンドウのテキスト プロンプトに応答できるインテリジェントなボットをエンド ツー エンドから設定します。Azure 内でのボットの構築について既に学習したことを基に構築しますが、さらにカスタム ロジックの層を追加して、独自のボット機能を実装します。

このボットは、Microsoft Bot Framework に組み込まれます。ボット インターフェイスがテキスト メッセージで受信して応答できるようにするアーキテクチャを呼び出し、ボットが特定のテキストを含む問い合わせに対応できるようにするロジックを構築します。

また、ここではBot Emulator でボットをテストし、ボットがユーザーから受け取るメッセージに対して特殊なタスクを実行できるミドルウェアを取り扱います。

Azure Search とマイクロソフトの Language Understanding Intelligent Service (LUIS) に関するいくつかの概念について取り上げますが、このラボでは実装しません。

## ラボ 4: ボットのチャットをログに記録する

前のラボでは、エコー ボット プロジェクトを構築し、ダウンロードしたコードをニーズに合わせて変更しました。  次に、ボット チャットをログに記録して、顧客サービス チームが問い合わせをフォロー アップし、ボットが想定どおりに動作しているかどうかを判別して、顧客データを分析できるようにします。

このハンズオン ラボでは、ボット ソリューションでさまざまなログの記録方法を有効にできるようにします。

高度な分析空間では、会話のログを格納するために使用されることが多くあります。チャットの会話のコーパスを持つことにより、開発者は次のことができます。

1. ドメインに固有の質問と回答のエンジンを構築する。
2. ボットが想定どおりに応答しているかどうかを確認する。
3. 特定のトピックまたは製品に関する分析を実行して、傾向を特定する。

次のラボでは、チャットのログを有効にしてメッセージをインターセプトする方法について説明します。データ ソリューションはこのワークショップの範囲内にはありませんが、データを格納するさまざまな方法のいくつかを呼び出します。

## ラボ 5: QnA Maker

このラボでは、Microsoft QnA Maker アプリケーションを使用してナレッジベースを作成し、公開してボットで使用します。

## ラボ 6: LUIS モデルを実装する

独自のイメージを取り込み、Cognitive Services を使用してイメージ内のオブジェクトや人物を検索して、説明やタグを取得することが可能なエンド ツー エンドのシナリオを構築します。後で、LUIS を使用して、簡単なターゲットを絞ったクエリを実行できる Bot Framework ボットを構築します。

## ラボ 7: Dialogues を使用して LUIS をボットに統合する

これでボットがユーザーの入力と、ユーザーの入力に基づく応答を受け取ることができるようになったため、[ラボ 6](/Lab6-Implement_LUIS/02-Implement_LUIS.md) で構築した LUIS モデルを使用して自然言語を理解できるようになりました。

## ラボ 8: ユーザー言語を検出する

このラボでは、ボットがユーザー入力から言語を検出する機能を追加します。

ボットをトレーニングしたり、QnA Maker と統合したが、言語を1つだけ使用してトレーニングした場合、その事実をユーザーに知らせることが推薦されます。  

## ラボ 9: DirectLine でボットをテストする

このハンズオン ラボでは、ボットのテストの基本について説明します。このワークショップでは、(DirectLine を使用して) 機能テストを実行する方法を示します。
