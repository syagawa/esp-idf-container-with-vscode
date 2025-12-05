# esp-idf-container-with-vscode

1. VS Code に Dev Containers, Remote Development 拡張をインストール
2. ターゲットとなるプロジェクトのディレクトリをVS Codeで開く
3. .devcontainerをそのままターゲットのプロジェクトにコピー
4. プロジェクトに合わせてDockerfileの下記を変更
```
# latestよりバージョンを指定したほうがいい
#ARG DOCKER_TAG=latest
ARG DOCKER_TAG=release-v5.2
```
5. F1 key Dev Containers - Reopen in Container
自動でコンテナが立ち上がり、ESP-IDF 拡張もインストールされESP-IDF拡張での開発が可能に


https://gist.github.com/bwrrp/dc2fe8926dfe8860da21cb87ba91aeaa
https://docs.espressif.com/projects/vscode-esp-idf-extension/en/latest/additionalfeatures/docker-container.html