---
title: ▶️Power Automate 演習🤖 
permalink: index.html
layout: home
---
# ▶️Power Automate について🤖

## Power Platform
Power Platform は、Microsoft が提供する低コード/ノーコードプラットフォームで、ビジネスユーザーから開発者まで幅広く利用できます。Power Platform は Power Apps、Power Automate、Power BI、Power Virtual Agents など複数のツールで構成されており、データ連携、業務自動化、分析、チャットボット構築など、企業のデジタル変革を支援します。既存のシステムとの統合も容易で、Microsoft 365 や Azure などの Microsoft エコシステムと seamlessly 連携でき、ビジネスプロセスの効率化と迅速なアプリケーション開発を実現します。

## Power Automate
Power Automate は、Power Platform の一部で、クラウドベースのワークフロー自動化ツールです。Power Automate を使用することで、複数のアプリケーションやサービス間のプロセスを自動化できます。メール送信、ファイル操作、データベース更新、承認フローなど、様々な業務タスクをノーコードで自動化でき、手作業の削減と業務効率の向上を実現します。Microsoft 365、Dynamics 365、Azure、サードパーティサービスなど、1000 を超える事前構築済みコネクタを利用でき、複雑な統合シナリオにも対応しています。

# 🧩演習：機能を試すチャレンジ🧩

<table>
  <tr>
    <th>⭐準備⭐</th>
  </tr>
  <tr>
    <td>
      <strong>Power Automate へのサインイン手順</strong><br>
      共有アカウントを使用して Power Automate にサインインしてください。<br><br>
      1. <a href="https://make.powerautomate.com/" target="_blank">https://make.powerautomate.com/</a> にアクセスします。<br>
      2. 「サインイン」をクリックします。<br>
      3. メールアドレスに <code>Guest&lt;番号&gt;@4gfrxm.onmicrosoft.com</code>（例：Guest1@4gfrxm.onmicrosoft.com）を入力します。<br>
      4. パスワードに <code>PowerPlatform1491</code> を入力します。<br>
      5. サインインが完了すると、Power Automate のホーム画面が表示されます。<br><br>
      ※ ゲストアカウントの番号は講師から指定されます。
    </td>
  </tr>
</table>
# テンプレートフロー☁️
⭐マイクロソフトが用意しているテンプレートからフローを作る

## テンプレートの選択手順

1. Power Automate のホーム画面で、左側のナビゲーションメニューから「**テンプレート**」をクリックします。
2. 検索バーで「**Outlook.com メールで毎日リマインダー**」と検索します。
3. 以下のテンプレートを選択します：

<table>
  <tr>
    <th>📧 テンプレート情報</th>
  </tr>
  <tr>
    <td>
      <strong>テンプレート名：</strong> Outlook.com メールで毎日リマインダーを受け取る<br>
      <strong>作成者：</strong> Microsoft Power Automate コミュニティ<br>
      <strong>実行タイプ：</strong> スケジュール済み<br>
      <strong>評価数：</strong> 80937
    </td>
  </tr>
</table>

## テンプレートの設定

4. 「**このテンプレートを使用する**」をクリックします。
5. 以下の項目を設定します：
   - **メール受信者：** 自分のメールアドレスを入力
   - **リマインダータイトル：** 任意のタイトルを入力（例：「日次リマインダー」）
   - **実行スケジュール：** 毎日の実行時間を設定

## テスト実行

6. 「**保存**」をクリックしてフローを作成します。
7. フロー一覧から作成したフローを選択し、「**テスト**」ボタンをクリックします。
8. テストモードで「**手動**」を選択します。
9. メール受信箱を確認して、リマインダーメールが正常に送信されたことを確認しましょう。


# インスタント　フロー☁️
⭐チャレンジで、自分が作ったコネクターが含まれるフローを試しましょう！
## コネクタとは
コネクタは、Power Automate が外部のアプリケーションやサービスと通信するためのインターフェースです。Power Automate には 1000 を超える事前構築済みコネクタが用意されており、Microsoft 365、Teams、Outlook、SharePoint などの Microsoft サービスや、Salesforce、Slack、GitHub などのサードパーティサービスと簡単に連携できます。コネクタを使用することで、異なるプラットフォーム間でのデータ連携や操作をノーコードで実現でき、複雑な API 統合なしに強力なワークフロー自動化を構築できます。

## 演習ステップ：Teams へ天気情報を送信するフロー

このチャレンジでは、MSN Weather コネクタを使用して天気情報を取得し、Teams を通じて Patti Fernandez（PattiF@4gfrxm.onmicrosoft.com）にメッセージを送信するインスタントフローを構築します。

### フロー作成手順

1. Power Automate のホーム画面で「**フロー**」をクリックし、「**新しいフロー**」から「**クラウド フロー** > **インスタント クラウド フロー**」を選択します。
  - **トリガーの選択：** 「**手動でフローをトリガーします**」を選択します。このトリガーにより、ユーザーが手動でフローを開始できるようになります。
2. フロー名を入力（例：「天気情報を Teams で共有」）して「**作成**」をクリックします。
3. フローデザイナーに遷移します。「**+新しいステップ**」と表示された大きなプラス（**+**）ボタンが表示されます。このボタンをクリックしてアクションを追加します。
4. 検索バーに「**MSN Weather**」と入力し、「**MSN Weather - Get current weather**」コネクタを選択します。
5. Location に任意の都市を入力（例：「Tokyo」）し、Unit を「Celsius」に設定します。
6. 再度「**+新しいステップ**」をクリックして、次のアクションを追加します。
7. 検索バーに「**Microsoft Teams**」と入力し、「**Microsoft Teams - Post a message in a chat or channel**」を選択します。
8. Post in に「**Chat with Flow bot**」を選択し、Recipient に「**PattiF@4gfrxm.onmicrosoft.com**」を入力します。
9. Message に以下の形式で天気情報を入力します：`Weather Update: @{outputs('Get_current_weather')?['body/current/temp']}°C`
10. 「**保存**」をクリックしてフローを保存します。

### テスト実行

9. 「**テスト**」ボタンをクリックして、「**手動**」を選択し実行します。
10. Patti Fernandez の Teams チャットで、天気情報が正常に送信されたことを確認しましょう。







