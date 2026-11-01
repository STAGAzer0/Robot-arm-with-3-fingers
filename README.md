# Robot-arm-with-3-fingers
# Autonomous Fruit Harvesting Robot Simulation (Physical AI)

AIを活用した農作物（果実）の選果シミュレーションシステムです。

## 概要
- **シミュレータ**: PyBullet
- **ロボット**: 産業用7軸マニピュレータ (KUKA LBR iiwa) + 自作120度対称3指求心グリッパー
- **視覚AI**: トップダウンRGBカメラによる熟期果実のリアルタイム色相・輪郭検出
- **制御**: 逆運動学 (IK)、2段階ソフトアプローチ、農作物の損傷を防ぐソフト把持力制御 (Damage-free Soft-touch Control)

## 動作環境
- Google Colab (Python 3.10+)
- 依存ライブラリ: `pybullet`, `ultralytics`, `opencv-python`, `imageio`

## 実行方法
Google Colab上でコードセルを実行することで、シミュレーションおよび動画レンダリングが自動的に行われます。
