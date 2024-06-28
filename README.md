# MotionDrive_TwinCAT_MELSERVO

このリポジトリには、実験用電源遮断装置と統合された三菱サーボアンプ (MR-J3-20A1) を使用したモータ制御システムの回路図と簡易プログラムが含まれています。プログラムおよび回路構成は実験用電源遮断装置の回路に依存し、回路図に使用されるシンボルはOpenSchematicsForPLCsライブラリに依存しています。

## Overview / 概要

このプロジェクトの目的は、三菱サーボアンプを用いたモータ制御実験のためフレームワークを提供することです．（動作すること自体が目的．適切な構造であるかは目的外）
このセットアップでは[実験用電源遮断装置](https://github.com/zilmina/SafetyPowerSupply)を使うことで確実に電源だけは遮断できるようにしています．

## Prerequisites / 前提条件

このプロジェクトを使用する前に、実験用電源遮断装置が正しく設定および構成されていることを確認してください。詳細は[実験用電源遮断装置のリポジトリ](https://github.com/zilmina/SafetyPowerSupply)に記載されています。

## Circuit Diagram / 回路図

回路図には以下のコンポーネントが含まれています：
- 三菱サーボアンプ (モデル名，MR-J3-20A1，端子台MR-TB50のみ記載)
- 
回路図に使用されるシンボルは[OpenSchematicsForPLCs]()ライブラリの一部です。回路図を使用する前に、このライブラリが正しく設定されていることを確認してください。

## Program / プログラム

プログラムはStructured Text (ST)、Function Block Diagram (FBD)、およびSequential Function Chart (SFC)で記述されています。プログラムには以下の機能が含まれます：
- サーボアンプの初期化
- 基本的なモータ制御（例：開始、停止、トルク司令）
- 非常停止手順
- 安全チェックとインターロック

## Installation / インストール

1. このリポジトリをローカルマシンにクローンします：
    ```sh
    git clone https://github.com/yourusername/servo-amplifier-shutdown.git
    ```

2. （作成中）

## Usage / 使用方法

（作成中）

## Documentation / ドキュメント

（作成中）

## Contributors / 貢献者

- [Hiroaki Kawase]

## License / ライセンス

このプロジェクトは[MITライセンス](LICENSE)の下でライセンスされています。

## Acknowledgements / 謝辞

- Beckhoff AutomationのIPCおよびI/O端子
- 三菱電機のサーボアンプ
- PILZの安全コントローラ
- 全ての貢献者とサポーター
- 回路図シンボルのためのOpenSchematicsForPLCs

## Contact / 連絡先

質問や提案がありましたら、Issueを作成してください．
