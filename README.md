# 丑三つの宿 月影亭怪談 / TSUKIKAGE INN — Ghost Hour Escape

日本の怪談をモチーフにした、HTML単体のポイント＆クリック型脱出ゲーム。
A single-file, point-and-click escape adventure inspired by Japanese kaidan (ghost stories).

---

## 日本語

### あらすじ
丑三つ時——夜中の二時すぎ。旅の宿「月影亭」の間（ま）で目を覚ますと、襖は開かない。
長廊下、脱衣場、便所、広間、床の間、屋根裏、中庭、井戸、土蔵、通用口——
どこにも「まだ解けるべき物」が残っている。門は生きたまま封じられた「生き封じ」。
夜明けの前に、宿を出よ。

### 起動方法
1. index.html をブラウザで開くだけ（ダブルクリックでOK）。サーバーもインストールも不要。
2. インターネット connection 不要の完全オフライン動作。
3. スマートフォンでは横向きでプレイ（縦にするとお告げが出ます）。
4. 対応ブラウザ: Chrome / Edge / Safari / Firefox の近年版。

### 遊び方
- 光って脈打つ場所や物をタップ／クリックして調べる。
- 下部の持ち物欄をタップで選択 → 別の場所へ使って解決。同じ持ち物を再度タップすると詳しく読める。
- 右上ボタン: 💡ヒント / 🗺地図（訪問済み地点へ直接移動） / 💾保存 / 🔊サウンドOn-Off / 言語切替（日本語⇄EN）。
- 場面転換のたびに自動保存（ブラウザの localStorage に記録）。「続ける」で中断から再開、タイトル画面でセーブ消去も可能。

### 収録した怪談・仕掛け（ネタバレなし一覧）
- お岩さんの鏡と井戸（霜の数字・数え唄・「名」呼びの封）
- 皿屋敷（九枚の皿と、時計に隠れた十枚目）
- 平重盛の首実検（三人の人形を左・中央・右へ並べ替える）
- 耳なし芳一を思わせる巻軸、一反木綿・傘松、黒猫、蜘蛛の巣の短冊、無面の立怪 ほか
- 解錠の鍵は「紙・鉄・名」の三つの封と巻き锁。短冊は全7枚、コンプリートで★。
- ヒント使用回数と短冊収集数はクリア画面に表示されます。

### 技術メモ
- 単一HTMLファイル（約110KB）。画像・音声・フォントの外部ファイルなし。
- 画像はすべて手描きSVG、効果音・環境音（風、きしみ、鉦、井戸の声など）はすべてWeb Audio APIで合成。
- セーブデータはブラウザの localStorage（キー: tsukikage_inn_save_v1）にのみ保存。外部送信は一切なし。
- 画面は 16:9（1280×720 基準）で、端末サイズに自動追従。

---

## English

### Synopsis
The hour of the ox — past two a.m. You wake in a room of the wayside inn "Tsukikage", and the shoji will not open.
Corridor, bathhouse, latrine, parlor, alcove room, attic, courtyard, well, storehouse, side gate —
everywhere, something still bound remains. The gate has been sealed by a living ritual. Leave the inn before dawn.

### Launch
1. Just open index.html in any modern browser (double-click works). No server, no install.
2. Runs fully offline — no internet required.
3. On smartphones, play in landscape (a gentle reminder appears if you turn sideways-back).
4. Supported: recent Chrome / Edge / Safari / Firefox.

### How to play
- Tap / click the softly pulsing spots and objects to examine them.
- Tap an item in the bottom bar to select it, then tap a place to use it. Tap a selected item again to read it closely.
- Top-right buttons: 💡 hint / 🗺 map (fast-travel to visited places) / 💾 save / 🔊 sound on-off / language switch (日本語 ⇄ EN).
- Auto-save on every scene change (stored in your browser's localStorage). "Continue" resumes your stay; the title screen can also erase the save.

### Kaidan & puzzles (no spoilers, list only)
- Oiwa's mirror and the well (frost digits, a counting chant, a seal that asks for a name)
- Saru-mishi / the plate-house (nine plates, and the lost tenth plate hidden in the clock)
- The head-inspection of Taira no Shigemori (turn three dolls to Left · Middle · Right)
- A wall scroll echoing Biwa no Hyakuchi, Hitokumenmomi the cloth, Kasa-matsu the umbrella, a black cat, a spider's strip, a faceless standing ghost, and more
- The gate yields to three seals — Paper, Iron, Name — plus the wound chain. Seven paper strips collect; collecting all shows a ★.
- Your hint count and strip count appear on the dawn (clear) screen.

### Technical notes
- One single HTML file (~110 KB). No external images, audio, or fonts.
- All artwork is hand-drawn inline SVG; all sound (wind, creaks, gong, the well-voice…) is synthesized live with the Web Audio API.
- Save data lives only in your browser's localStorage (key: tsukikage_inn_save_v1). Nothing is ever sent anywhere.
- The stage is 16:9 (1280×720 design basis) and scales to fit any device.

### License
同人・個人利用は自由。再配布・改変も可（クレジット "Tsukikage Inn" を添えてくれると嬉しいです）。
Free for personal and doujin use; modification and redistribution welcome (a "Tsukikage Inn" credit is appreciated).