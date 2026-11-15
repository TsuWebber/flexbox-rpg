# Flexbox 勇者傳說

打怪學 CSS Flexbox 的網頁小遊戲。怪物用一段亂掉的排版施法攻擊你，在時間內輸入正確的 Flexbox 屬性值破解它，就能反擊。

**線上玩：<https://tsuwebber.github.io/flexbox-rpg/>**

## 怎麼玩

- 依序挑戰四隻怪物：困惑史萊姆、搗亂哥布林、黑暗法師、混沌巨龍。越後面的怪物血越厚、攻擊越痛，破解時間也越短（最後一關只有 9 秒）。
- 每回合怪物會出一題排版，你要用對 `justify-content`、`align-items`、`flex-direction`、`flex-wrap` 這類屬性的值把它排回來。
- 答對造成傷害，答得快還有速攻加成；超時或答錯就會被打。
- 卡住可以按「提示」，但結算時會被記下來。

## 兩種操作方式

| 模式 | 適合 | 怎麼答題 |
|---|---|---|
| 點擊模式 | 剛開始學 Flexbox | 從按鈕裡選 CSS 值 |
| 打字模式 | 想挑戰自己 | 直接輸入 CSS |

## 技術

單一個 `index.html`，純 HTML、CSS、JavaScript，不需要安裝或建置。部署在 GitHub Pages。

本機遊玩：直接用瀏覽器打開 `index.html` 就可以。
