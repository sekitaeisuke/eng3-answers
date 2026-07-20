# eng3-answers

中3英語 4技能統合ドリル eng3_full（地域教育工房）の **Web解答**。

問題集PDF（上巻／下巻）の各単元冒頭にあるQRコードから、その単元の解答解説に
スマホ／タブレットでアクセスできます（紙の解答解説編は廃止し、これで置換）。

- 目次: `index.html`（上巻 U1〜U9＋総合演習／下巻 U10〜U16＋総合演習）
- 単元ごとの解答: `u1.html` 〜 `u16.html`・`sup.html`・`sup2.html`
- 公開URL（GitHub Pages）: https://sekitaeisuke.github.io/eng3-answers/

※ リスニング音声は別リポジトリ **eng3-audio**（問題編の各問QR）。

## 更新方法

元データは ai-system リポジトリの `data/kyozai_out/eng3_{UNIT}_解答解説編.md`
（問題集PDFと同一・講師チェック済み本文）。更新時は ai-system 側で再生成して
このリポジトリへコピーし直す:

```
python scripts/build_eng3_answers_web.py
# → output/eng3_answers_web/ の中身をこのリポジトリにコピーして commit & push
```
