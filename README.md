# infrastructure-auth0


## tools
### 1. direnv
   ローカルで Auth0 の設定を行うために利用(仮)

1. direnv をインストール
```bash
brew install direnv
```

2. シェルの設定を追加（~/.zshrc や ~/.bashrc）
```
eval "$(direnv hook zsh)" 
```

3. direnv の許可
```bash
direnv allow
```

4. 環境変数テンプレートをコピー
```bash
cp .envrc.example .envrc
```

5`.envrc` を編集
