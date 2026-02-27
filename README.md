# zmk-config-roBa

<img src="keymap-drawer/roBa.svg" >

## トラックボール設定

このキーボードには **PMW3610トラックボール** が統合されており、X軸（横方向）とY軸（縦方向）の感度を独立して調整できます。

### クイックスタート

トラックボールのX軸・Y軸の感度を異なる値に設定する場合：

**編集ファイル**: `boards/shields/roBa/roBa_R.conf`

```properties
# 例: 横方向を低感度（300）、縦方向を標準（400）に設定
CONFIG_PMW3610_CPI_X=300
CONFIG_PMW3610_CPI_Y=400
```

### 詳細ガイド

詳しくは **[TRACKBALL_SENSITIVITY_GUIDE.md](TRACKBALL_SENSITIVITY_GUIDE.md)** を参照してください。

以下の内容をカバーしています：
- ✅ X軸・Y軸独立感度設定方法
- ✅ 用途別設定例（精密作業・ゲーム・スクロール等）
- ✅ CPI値の推奨範囲
- ✅ ディバイダー設定
- ✅ トラブルシューティング

