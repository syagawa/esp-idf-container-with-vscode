# esp-idf-container-with-vscode

1. VS Code に Dev Containers, Remote Development 拡張をインストール
2. F1 key Dev Containers - Reopen in Container
自動でコンテナが立ち上がり、ESP-IDF 拡張もインストールされる

3. 左ペインの空白を右クリックで workspaceに追加

 ターミナルで確認：

idf.py --version
idf.py build
idf.py flash monitor

https://gist.github.com/bwrrp/dc2fe8926dfe8860da21cb87ba91aeaa
https://docs.espressif.com/projects/vscode-esp-idf-extension/en/latest/additionalfeatures/docker-container.html