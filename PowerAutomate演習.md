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







