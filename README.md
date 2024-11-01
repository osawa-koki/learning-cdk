# learning-cdk

🎃🎃🎃 CDKでAWSリソースをプロビジョニングしてみる！  

## 実行方法

DevContainerに入り、以下のコマンドを実行します。  

```bash
# テンプレートを生成
cdk synth

# スタックを作成
cdk bootstrap

# スタックをデプロイ
cdk deploy
```

## メモ

1. プロジェクトの初期化

### 1. プロジェクトの初期化

```bash
cdk init app --language typescript
```
