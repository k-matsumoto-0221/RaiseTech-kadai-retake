1. EC2 ダッシュボードへ

2. 中央ペインから「インスタンスを起動」をクリック
    - 名前とタグ
      - 省略
    - アプリケーションおよび OS イメージ (Amazon マシンイメージ)
      - Amazon マシンイメージ (AMI)
        - Amazon Linux 2 AMI（HVM）- kernel 5.10, SSD Volume Type
      - アーキテクチャ
        - 64 ビット (x86)
    - インスタンスタイプ
      - インスタンスタイプ
        - t2.micro
        - **すべての世代** は Off
    - キーペア (ログイン) 
      - キーペア名 - 必須
        - 省略
    - ネットワーク設定
      - VPC - 必須
        - 作成済みの VPC
      - サブネット
        - 作成済みのパブリックサブネット
      - パブリック IP の自動割り当て
        - 有効化
      - ファイアウォール (セキュリティグループ)
        - 既存のセキュリティグループを選択する
      - 共通のセキュリティグループ
        - 作成済みの EC2 用のものを選択
      - 高度なネットワーク設定
        - すべて規定値
    - ストレージを設定
    - 高度な詳細
    - 概要
      - すべて規定値

3. 「インスタンスを起動」をクリック