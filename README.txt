SHADOW QUEST V2.7 - Local 3D Asset Build

部署方式：
1. 解壓縮 ZIP。
2. 將 ZIP 內的 index.html 與 assets/ 資料夾一起上傳至 GitHub Pages 專案根目錄。
3. 不要只上傳 index.html；模型檔必須與 assets 資料夾一起上傳。
4. 等待 GitHub Pages 更新後，Ctrl+F5 重新整理。

本版實際內含模型：
- assets/horror-monster.glb：一般敵人模型（使用你上傳的檔案）
- assets/kraken.glb：Boss 模型（使用你上傳的檔案）
- assets/08_Dragonfang_Blade.glb：聖殿騎士長劍
- assets/01_Archmage_s_Scepter.glb：秘法術士權杖
- assets/15_Crystal_Katar.glb：暗影刺客雙持水晶卡塔匕首

星界遊俠：
- 你提供的武器包內沒有弓模型，因此保留原本弓的顯示，不假裝已換成外部弓模型。
- 盾牌同樣不在這包內，騎士目前使用新長劍，未附加外部盾牌。

授權：
- 你提供的 3D Fantasy Weapons Pack 2 LICENSE.txt 明確標示 CC0 1.0 Universal，可商用、可修改、不需署名；禁止原樣轉售整包。
- horror-monster.glb 與 kraken.glb 依照你提供的資產檔案使用；本包不替其額外宣稱授權，請保留你下載來源的授權紀錄。
- 原始武器包授權全文另存於 assets/WEAPONS-LICENSE.txt。

相容與檢查：
- 所有 GLB 均為 GLB 2.0；武器模型來自你上傳的 ZIP，含 PBR base-color 與 metallic/roughness 貼圖。
- 已檢查 GLB 檔案結構、武器包 ZIP 完整性、程式碼語法與輸出 ZIP 完整性。
- 未在真實瀏覽器完成 Three.js 實際渲染測試。
- 保留 localStorage key：shadowQuestSave。
- 保留原有戰鬥系統與操作方式。
