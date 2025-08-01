# 演習：Microsoft 365 Copilot in Outlookで保険会社へのメールを作成

Microsoft 365 Copilot in Outlookは、財務担当者がカスタムメールやメール返信を作成する際の時間と労力を節約するためのAIベースのツールです。Copilotを使用することで、何時間もかけて作成・編集する必要なく、特定のニーズに合わせてCopilotが調整したメールドラフトを素早く生成できます。この演習では、Outlook内のCopilotを使用して、一連のユーザー提供プロンプトに基づいて新しいメールを作成します。

Copilot in Outlookは、以下のような強力な機能を提供します：

- **カスタムメールの自動生成**：複雑なビジネスメールも簡単なプロンプトから作成
- **トーンと長さの調整**：フォーマル、カジュアル、ダイレクトなど、目的に応じたトーンの設定
- **コーチング機能**：作成したメールの改善提案と自動適用
- **反復的な改善**：複数回のコーチングによる段階的な品質向上

## 重要な注意事項

OutlookでのCopilotシナリオは、ユーザーのプライマリメールボックスでのみ利用可能です。アーカイブメールボックス、グループメールボックス、またはユーザーがアクセス権を持つ共有・委任メールボックスでは利用できません。MicrosoftはExchange OnlineでホストされているメールボックスでのみOutlookのCopilotをサポートしています。また、Outlook内のCopilotは、Microsoft 365の職場または学校アカウント、および特定のメールドメインを持つMicrosoftアカウントでのみサポートされています。

## シナリオ

あなたはNorthwind TradersのCFO（最高財務責任者）です。会社の健康保険会社であるHumongous Insuranceに対して、Copilot in Outlookを使用してメールを作成したいと考えています。保険代理店から最近連絡があり、Northwind社の健康保険料が全面的に値上げされることが通知されました。個人保険では9%以上、家族保険では15%以上の増加で、この上昇率は業界平均を大幅に上回っています。

このメールの目的は二つあります：
- 保険料増加の水準に対する懸念を表明する
- この件について議論し、代替案を検討するため、保険会社チームとの会議を要請する

## 実習手順

### Outlookでのメール作成開始

1. Microsoft 365のナビゲーションペインで「**Outlook**」を選択します。左側のナビゲーションペインに表示されていない場合は、「アプリ」を選択してからOutlookを選択してください。

2. Outlookで「**新しいメール**」を開きます。

3. 開いたメッセージタブで、リボンの「**Copilot**」を選択します（通常、右端にあります）。表示されるドロップダウンメニューで「**下書き**」を選択します。

### 初期ドラフトの作成

4. メッセージ本文にCopilotウィンドウが表示されます。プロンプトフィールドには「このメールで何を伝えたいですか？」というメッセージが表示されます。

5. 「このメールで何を伝えたいですか？」フィールドの下には、選択可能なさまざまなメールタイプに適用される**推奨プロンプト**のリストが表示されます。

6. 推奨プロンプトタイプの代わりに、以下のプロンプトを「このメールで何を伝えたいですか？」フィールドに入力してください：

   ```
   私はNorthwind TradersのCFOです。保険会社のHumongous Insuranceに対して、来年度の当社健康保険料の増加水準への懸念を表明するメールを作成してください。提案された増加について議論し、代替案を検討するため、保険会社チームとの会議を要請してください。
   ```

7. プロンプトフィールドに表示される「**生成**」ボタンを選択します。

### トーンの調整と複数ドラフトの比較

8. ドラフトを確認します。メッセージの下にCopilotが表示するメニューでは、コンテンツを「記憶する」、「破棄」、またはさまざまな方法で「変更」することができます。

9. メッセージに満足していますが、異なるトーンと長さを使用した場合の変化を確認したいと思います。メニューの下部にある「**スタイルの変更**」を選択します。

10. 表示されるメニューで「**ダイレクト**」を選択します。これにより、Copilotがよりダイレクトなトーンでメールの新しいドラフトを生成します。

11. 修正されたドラフトを確認します。ドラフトウィンドウの上部で、Copilotがこのドラフトが「2 of 2」であることを示していることに注意してください。これは2つのCopilotドラフトの2番目を見ていることを意味します。

12. 戻る矢印（<）を選択して前のCopilotドラフト（フォーマルトーンで長い長さの最初のドラフト）に戻ることができます。

### さらなるトーン調整

13. ドラフト2（2 of 2）を確認中であることを確認してください。このダイレクトドラフトの挨拶文、結びの言葉、メッセージ全体のトーンに注意してください。

14. 要点をストレートに伝えたいものの、ダイレクトなトーンは非人間的すぎると感じるため、異なるトーンで新しいドラフトを生成したいと思います。今度は、トーンを「**カジュアル**」に変更してください。

15. ダイレクトトーンからカジュアルトーンへの変化を確認してください。

### ドラフトの比較と長さの調整

16. これで3つのドラフトができました：ドラフト1（デフォルトのフォーマルトーン）、ドラフト2（ダイレクトトーン）、ドラフト3（カジュアルトーン）。

17. ダイレクトトーンは好ましくないが、フォーマルトーンとカジュアルトーンのどちらが良いか決められない場合は、前後の矢印を使用してドラフト1（フォーマル）とドラフト3（カジュアル）を比較してください。

18. 使用したいドラフトが決まったら、そのドラフトがCopilotウィンドウに表示されていることを確認してください。まだ「**記憶する**」は選択しないでください。

19. より長いバージョンがどのように見えるか興味があります。メニューで「**長くする**」を選択してください。

### 詳細情報の追加

20. Copilotが選択したドラフトに基づいて4番目のドラフト（4 of 4）を生成しましたが、今度はより長いバージョンが作成されました。

21. この最新ドラフトを確認後、これが使用したいバージョンだと感じますが、保険料増加に関する詳細情報、特に個人保険と家族保険の内訳が不足していることに気づきます。

22. メニュー上部のプロンプトフィールドに以下のプロンプトを入力してください：

    ```
    Northwind Tradersに提案されている保険料増加の水準を業界全体の保険料増加と比較してください。当社の個人保険料は9%以上増加し、家族保険は15%以上増加しました。当社の増加がそれぞれ6%と10%の業界平均を大幅に上回っていることを言及してください。
    ```

23. 更新されたドラフトを確認します。より良く見えますが、高控除額/低保険料プランへの変更の可能性について最後に一言追加することにしました。

24. 以下のプロンプトを入力してください：

    ```
    高控除額、低保険料の保険への変更について議論すべきことを言及してください。
    ```

### 最終確認と保存

25. この最新の反復を確認後、ドラフトに満足したら、メニューの「**記憶する**」オプションを選択します。

26. メッセージがメール本文に表示されることを確認してください。

### コーチング機能の使用

27. Copilotドラフトを実際のメールに変換したので、Copilotの「**コーチング**」機能について確認してみましょう。コーチング機能は手動で作成したメールを確認し、改善提案を行います。

28. Outlookリボンで、リボンの最後にある「**Copilot**」ボタンを選択します。演習の開始時には「下書き」オプションを選択しましたが、今度は「**コーチング**」を選択してください。

29. Copilotが生成した提案を確認します。以前のプロンプトで送信したトーンとメッセージングに応じて、Copilotは自分自身を批判的に評価できることに注意してください。

30. この場合、メニューで「**すべての提案を適用**」を選択します。

31. Copilotが提案を適用した別のドラフトウィンドウが開くことに注意してください。コーチング提案をドラフトモードで適用することで、実際のメールメッセージに影響を与えることなく、必要に応じてドラフトバージョンにさらなる変更を加えることができます。

32. コーチング提案に満足した場合は、メニューで「**置換**」を選択します。

### 追加のコーチング

33. Outlookリボンで「**Copilot**」ボタンを選択し、表示されるドロップダウンメニューから「**コーチング**」を選択してもう一度コーチング機能を試してみましょう。

34. Copilotが生成する提案を確認します。以前の提案とどのように異なるかに注目してください。

35. 「**すべての提案を適用**」を選択し、その後「**置換**」を選択して、メールの前のバージョンを更新されたバージョンに置き換えます。

36. メールに満足するまで、これらのコーチング手順を必要なだけ繰り返すことができます。

### 演習の完了

37. このメールを送信する予定がないため、メール画面の右上にあるゴミ箱（破棄）アイコンを選択し、メッセージを破棄することを確認してください。

## 完了

以上でMicrosoft 365 Copilot in Outlookを使用した保険会社へのメール作成演習は完了です。