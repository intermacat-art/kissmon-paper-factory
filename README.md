# 親親獸剪紙工廠

HTML5 Canvas 小遊戲。親親獸在輸送帶左側，剪右邊傳來的紙，躲掉生物，讓菸過會暈眩。

## 玩法

- **SPACE** = 剪
- 剪到紙張 ✂️ → 正確
- 剪到 VT 生物 ❌ → 扣血
- 紙張沒剪跑出左邊 → 扣血（任務失敗）
- 菸跑過去 → 暈眩 2.8 秒
- 每 10 秒速度 +1 倍

3 滴血歸零 = Game Over。

## 線上試玩

https://intermacat-art.github.io/kissmon-paper-factory/

## 本機跑

```bash
python -m http.server 8765
```

打開 http://localhost:8765/
