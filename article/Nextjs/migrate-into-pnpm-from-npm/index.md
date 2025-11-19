# npm から pnpm に乗り換える

npm より pnpm のほうが軽くなるらしい

- pnpm のインストール

```powershell
> npm install pnpm
```

`node_modules/` と `package-lock.json` を削除後、以下を実行する

```powershell
> pnpm install
```

`pnpm-lock.yaml`ができる
