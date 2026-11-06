# agame-cdn

agame 各遊戲的靜態檔（JS、CSS、圖片、音效）與維護版頁面，由各遊戲 repo 的部署流程用 `tools/publish-asset-cdn.mjs copy` 加進來（只增不刪）。設計見 pixi-colyseus-card 決策 0019。

- `<遊戲 id>/assets/`：與 agame 上同一份打包結果，檔名帶內容雜湊。
- `<遊戲 id>/index.html`：agame 連不上時啟動頁開的維護版。
