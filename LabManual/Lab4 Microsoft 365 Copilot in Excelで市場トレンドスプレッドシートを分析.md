# 演習：Microsoft 365 Copilot in Excelで市場トレンドスプレッドシートを分析

Microsoft 365 Copilot in Excelは、マーケティング担当者がデータを分析し、ビジネスに関する洞察を得るための強力なツールです。Copilot in Excelを使用することで、マーケティング担当者は簡単にデータの作成、編集、理解、視覚化を行うことができます。

例えば、四半期のビジネス結果の分析、主要トレンドの要約、テーブルへの色分けの適用、モデルやシナリオの作成、フィルタリングとソート、チャートの追加などをワンクリックで実行できます。Copilotのプレゼンテーション機能により、マーケティング担当者は反復的な作業を自動化し、情報に基づいた意思決定に役立つ貴重な洞察を得て、時間と労力を節約できます。Copilot in Excelを使用することで、最も重要なこと、つまりビジネス目標と目的に集中できるようになります。

Copilot in Excelは、マーケティング担当者のツールボックスにおいて貴重なツールです。以下のような多くのメリットを提供します：

- **データのハイライト、フィルタリング、ソート**：Copilot in Excelは、データを素早く特定し整理するために、ハイライト、フィルタリング、ソートを行えます。例えば、マーケティング担当者は大規模なデータセットから無関係なデータ（顧客の人口統計など）をフィルタリングし、マーケティング目標に最も関連性の高いデータに焦点を当てることができます。

- **複雑な計算のための数式列の提案**：Copilot in Excelは、マーケティングキャンペーンの投資収益率（ROI）の計算など、複雑な計算のための数式列の提案を生成できます。例えば、マーケティング担当者はCopilotを使用して、キャンペーン期間中に生成された収益をキャンペーンのコストで割ることで、メールマーケティングキャンペーンのROIを計算できます。

- **データ分析、理解、視覚化の支援**：Copilot in Excelは、マーケティング担当者がデータトレンドの分析、データの理解と視覚化、自然言語での洞察の説明を行えるよう支援します。手動でチャートやピボットテーブルを作成する必要なく、複雑なデータを解釈できるよう設計されています。

## Copilot in Excelを使用する際の重要な注意事項

Microsoft 365 Copilot in Excelを効果的に使用するためには、ワークシート内のデータが**Excelテーブル形式**になっている必要があります。特にデータの要約、洞察の生成、高度なExcel関数の使用などの複雑なタスクでは、テーブル形式での作業が推奨されます。これにより、Copilotがデータをより効率的に参照し、操作できるようになります。

### データをExcelテーブルに変換する手順

データがまだテーブル形式になっていない場合は、以下の手順で簡単に変換できます：

1. **データの選択**：データ内のセルまたは範囲を選択します
2. **テーブル化の実行**：**[ホーム]** > **[テーブルとして書式設定]** の順に選択します
3. **ヘッダー行の設定**：**[テーブルとして書式設定]** ダイアログボックスで、範囲の最初の行をヘッダー行にする場合は、**[先頭行をテーブルの見出しとして使用する]** の横にあるチェックボックスをオンにします
4. **完了**：**[OK]** を選択します

### Excelテーブルを使用する利点

- **構造化されたデータ参照**：Copilotがデータの範囲と構造を明確に認識
- **効率的な分析**：列名やデータ範囲の自動識別により、より正確な分析が可能
- **高度な機能の活用**：数式の提案、データ分析、視覚化機能が最適に動作
- **動的な範囲管理**：データが追加されても自動的にテーブルが拡張

**注意**：この演習で使用するスプレッドシートには既にExcelテーブルが定義されていますが、今後独自のデータでCopilot in Excelを使用する際は、この手順を覚えておいてください。

## シナリオ

あなたはContoso, Ltd.の一部門であるContoso Beverageのマーケティングディレクターです。過去1年間のContoso社のチャイティー製品の月次活動を示す市場トレンドスプレッドシートを受け取りました。Copilot in Excelの機能を使用してレポートを分析し、月次マーケティングトレンドの詳細な分析を提供したいと考えています。

この演習では、Copilot in Excelが提供するさまざまな事前定義されたプロンプトと機能を確認し、市場トレンドスプレッドシートの分析を行います。

## 実習手順

### Excelでのスプレッドシート分析

5. マイファイルページで、ファイル一覧から「**Contoso Chai Tea market trends 2023.xlsx**」を選択します。

6. スプレッドシートがExcelで開いたら、リボンの右側にある「**Copilot**」オプションを選択します（リボンが表示されていない場合は、ホームタブにカーソルを合わせてください）。これによりCopilotペインが開きます。

### データインサイトの表示

7. 表示されるCopilotペインで、選択できる事前定義されたプロンプトがいくつか表示されます。「**データの分析情報を表示する**」というプロンプトが表示される場合は、それを選択してください。

8. 「データの分析情報を表示する」が表示されない場合は、以下のプロンプトを手動で入力し、送信アイコンを選択してください：
    ```
    データの分析情報を表示する
    ```

### 生成されたグラフの確認

9. Copilotが生成したグラフを確認します。テスト中、Copilotはいくつかの異なるチャートを作成しました：
    - Artisanal Chai売上（単位）のグラフ
    - 月別ソーシャルメディアエンゲージメント（ビュー数）の棒グラフ
    
    どのようなタイプのチャートが作成されましたか？

10. Copilotペインのスペース制限により、チャートの完全な凡例は含まれていないことに注意してください。Copilotが作成したピボットテーブルと完全なチャートを表示するには、チャートの下に表示される「**+ 新しいシートに追加**」ボタンを選択します。

11. **Sheet 2**を選択します。Copilotが作成した新しいデータシートを確認します。Copilotには、グラフとスプレッドシートからのデータ列の両方が含まれており、これがこのグラフの基盤となっています。

### 追加のデータインサイトの要求

12. 別のデータインサイトを要求するか、独自のプロンプトを送信するには、スプレッドシートを含むデータシートに戻る必要があります。**Sheet 1**を選択して、Excelテーブルに戻ります。

13. プロンプトフィールドの上に表示される事前定義されたプロンプトを確認します。「**更新**」ボタンを選択して別のプロンプトセットを表示します。興味のある事前定義されたプロンプトを自由に選択して、Copilotがどのように応答するかを確認してください。

### 数式列の提案

16. Copilotがどのようなデータ分析を推奨するかを確認したいと思います。「**数式列の提案を表示**」という事前定義されたプロンプトが表示される場合があります。このプロンプトを選択すると、Copilotがデータを分析し、データセットに役立つ可能性のある数式や計算を提案します。

17. 「数式列の提案を表示」のプロンプトが表示されない場合は、「更新」ボタンを数回選択してください。数回の更新後もこのプロンプトが表示されない場合は、以下のプロンプトを入力してください：
    ```
    数式列の提案を表示
    ```

18. Copilotが提供する提案を確認します。受け取った提案で、「**説明を表示**」ドロップダウン矢印を選択します。計算を説明するCopilotの説明を確認します。

19. 数式の提案の確認が完了したら、「**+ 列を挿入**」ボタンを選択して、列をExcelテーブルに挿入します。

### 追加の数式列の挿入

20. CopilotがSheet 1のExcelテーブルの末尾にデータ列を追加したことを確認します。この機能に興味を持ったので、他にどのような数式の提案があるかを確認したいと思います。

21. 「数式列の提案を表示」の事前定義されたプロンプトが表示される場合は、それを選択してください。この事前定義されたプロンプトが表示されない場合は、以下のプロンプトを入力してください：
    ```
    数式列の提案を表示
    ```

22. 提案を確認し、「**+ 列を挿入**」ボタンを選択して、この提案された列をExcelテーブルに挿入します。

### その他の事前定義されたアクションの探索

23. この演習の目的は、Copilotが実行できるさまざまなタイプの事前定義されたアクションの感触を掴むことです。興味のあるアクションを探しながら、「**更新**」アイコンをさらに数回選択してください。

24. プロンプトを選択してCopilotの動作を確認してください。他のプロンプトも自由に選択してください。

25. 作業が完了したら、適切なファイル名でOneDriveに保存します：
    **「Contoso Chai Tea Analysis.xlsx」**

### 最終調整と保存

26. 作業完了後、ファイルを保存して演習を終了します。

## 完了

以上でMicrosoft 365 Copilot in Excelを使用した市場トレンドスプレッドシート分析演習は完了です。
