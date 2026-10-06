# AGENTS.md

115-1 Computer Programming 課程程式碼庫。目前僅有骨架：`README.md` + Python `.gitignore`，尚無原始碼、測試或工具鏈設定。

## 基本規定

- 所有回應一律使用繁體中文。
- 專案程式語言為 Python。
- 使用 conda 管理 Python 套件，環境名稱為 `iem_python`。
- 執行 Python 前先啟用環境：`conda activate iem_python`；安裝套件使用 `conda install`，僅在 conda 無提供時才用 `pip install`。

## 工作慣例

- 尚無 build、test、lint、typecheck 指令。不要臆測指令，執行前先確認新增的設定檔。
- 保持程式簡單且符合課程程度：以標準函式庫為主，除非另有指示，否則一個練習／主題一個腳本。
- 未經要求，不要加入重型骨架（打包、框架、CI、monorepo 工具）。
- 異動腳本後直接驗證：`conda activate iem_python && python <file>`。
