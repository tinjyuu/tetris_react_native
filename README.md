# tetris_react_native
プロンプトだけで、テトリスを作ってみましょう。


以下のプロンプトをClineに入力してテトリスを作成してください。


```
# Expo Goを使用したReact Native テトリスゲーム開発指示書

## 概要
React NativeとExpo Goを使用し、スマートフォンで動作するテトリスゲームを開発してください。

## 要件

### 1. 技術スタック
- React Native（JavaScriptまたはTypeScript）
- Expo Go（開発および実機テスト用）
- 状態管理ライブラリ（Redux、Recoil、Zustand等）の使用は任意ですが、まずはReactの標準Hooks（useStateやuseEffect）を用いたシンプルな実装を推奨します。

### 2. ゲームプレイの実装
- 標準的なテトリスのルールを実装してください（テトリミノの落下、左右移動、回転、ライン消去、スコア加算、ゲームオーバー条件など）。
- アプリ起動後、すぐにゲーム画面が表示されプレイ可能な状態にしてください。
- 現在のスコアと次のテトリミノを常に表示してください。

### 3. UIデザイン
- Expo標準コンポーネントを活用し、シンプルかつ直感的なデザインを目指してください。
- レスポンシブ対応を行い、異なる画面サイズのスマートフォン（iOSとAndroid両対応）で適切に表示・操作できるようにしてください。
- **ゴーストピース機能**を実装し、現在操作中のテトリミノの最終落下位置を半透明で表示してください。

### 4. 操作方法
- タップ: テトリミノの回転
- 左右スワイプ: テトリミノを左右に移動。スワイプした量に応じて移動する。
- 下スワイプ: スワイプするとハードドロップ（瞬間落下）する。

### 5. Expo Goでの動作確認
- Expo CLI (`expo start`) を使って開発サーバーを起動し、スマホのExpo GoアプリからQRコードを読み取ってリアルタイムで動作確認を行えるようにしてください。

### 6. 推奨ファイル構成
- `App.js` または `App.tsx`: メイン画面のエントリーポイント
- `components/GameBoard.js`: ゲームボードとゲームロジック表示用コンポーネント
- `components/Piece.js`: テトリミノ表示・制御用コンポーネント
- `components/ScoreBoard.js`: スコア表示用コンポーネント
- `README.md`: プロジェクトの説明と操作方法

### 7. ドキュメント（`README.md`）
- アプリの簡単な説明
- Expo Goを使ったスマートフォンでの動作確認方法を明確に記載
- アプリのビルド・実行手順を記載してください（`expo start` → QRコードスキャンまで）

## 最終目標
完成したプロジェクトは、Expo Goを使ってスマートフォンで簡単にテスト可能であり、直感的な操作でプレイできるテトリスゲームとして動作する状態になっていること。

```
