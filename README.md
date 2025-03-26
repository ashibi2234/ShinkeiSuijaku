🕹️ カードゲーム（神経衰弱）のGUI実装

私は、Java Swingを使用して「神経衰弱ゲーム」のグラフィカルユーザーインターフェース（GUI） を設計・開発しました。このプロジェクトでは、直感的な操作性、リアルタイムのカード操作、プレイヤーのスコア表示 など、視覚的に分かりやすいインターフェースの実現に取り組みました。

✅ 主な機能と特徴

カードのレイアウトと初期化

3行×9列の GridLayout を使用し、26枚のカードを均等に配置。\
各カードの初期状態は「伏せた状態」で、クリック時に反応するようにリスナーを追加。


カードボタンの動作

ActionListener を使用して、各カードがクリックされた際の挙動を制御。\
カードの状態を変更することで、ゲームの進行状況をリアルタイムで反映。


プレイヤーのスコア表示

FlowLayout により、2人のプレイヤーの名前・得点を下部パネルに配置。\
得点の増減やターンの変更に応じて、スコア表示をリアルタイムで更新。


画面サイズと視認性の最適化

ウィンドウサイズを 600x400ピクセル に設定し、カードとスコアがバランスよく表示されるレイアウトを実現。\
Arialフォント（24px/18px） を使用して視認性を向上。


📚 技術スタック

Java Swing: GUI構築、ボタン・ラベル・パネルの制御\
GridLayout & FlowLayout: レイアウトの最適化と柔軟なUI配置\
ActionListener: ユーザー入力に対するイベントハンドリング


🎯 得られた成果

GUI開発の理解と応用：Swingを活用して、動的に変化するゲーム画面の実装に成功しました。\
イベント駆動プログラミングの経験：ユーザーの操作（カードクリック）に応じた即時フィードバックの処理を実装。\
再利用性・拡張性の高い設計：カードの状態管理やプレイヤー情報の更新処理を別クラスで管理し、コードのメンテナンス性を向上。


🔥 今後の展望

AI対戦機能の導入：シングルプレイ時にAIプレイヤーと対戦できる機能を追加予定。\
カードデザインの向上：画像アイコンを使用してカードのビジュアルを強化。
