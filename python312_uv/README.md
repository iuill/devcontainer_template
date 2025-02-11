# Python 3.12 + uv Dockerテンプレ

## 開発

初回

```console
uv init
```

最新パッケージを導入する場合

```console
uv sync
uv add -r requirements.txt
uv pip list
```

lockファイルのバージョンでパッケージを導入する場合
```console
uv sync --frozen
```
