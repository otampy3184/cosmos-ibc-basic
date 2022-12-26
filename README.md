# Cosmos inter-blockchain communication basic

IgniteCLIのチュートリアルに従って、ブロックチェーン間のmsgのやりとりについての理解を深める

## モジュール作成

最初にignite cliでplanetという独自チェーンを作成する

```:
% ignite scaffold chain planet --no-module
cd planet
```

この時点でオリジナルモジュールは特に設定されていない

次にplanet内に移動し、独自モジュールの雛形を作成する

```:
% ignite scaffold module blog --ibc
```

独自モジュールはxディレクトリ内に生成される

