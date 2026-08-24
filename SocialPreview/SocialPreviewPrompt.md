# Panopticon Iron Bloc Social Preview Image Prompt

## Purpose

X向けのSocial Preview画像を生成するためのプロンプトです。

この画像は、ゲームストーリー全体の印象を一枚で伝えるキービジュアルとして使用します。単なる戦争難民ものではなく、「戦争しか知らない少女が、AIによって管理された平和な社会に保護され、その社会と故郷の両方を見つめ始める物語」であることが伝わる構図にしてください。

## Output Requirements

- 推奨サイズ: 1280 x 640 px
- 最低サイズ: 640 x 320 px
- アスペクト比: 2:1
- 形式: PNG, JPG, or GIF
- ファイルサイズ: 1MB未満
- Social Preview用途のため、細部を詰め込みすぎず、小さく表示されても主題が読める構図にする
- 文字、ロゴ、タイトル、UIテキストは入れない

## Visual Direction

暖かいノヴォラドのアパートの窓辺に立つマリューシャを中心にした、静かなキービジュアル。

画面左または中央寄りにマリューシャ。彼女は窓ガラスに片手を触れて、外の雪の街を見ている。部屋の中は暖かい灯りで満たされ、背後には眠っている、または静かに休んでいるスネジャーナがいる。テーブルにはリンク端末が置かれ、中央計画AIの監査協力画面とベルザニア支援公開記録を示す抽象的な2つの画面が淡く光っている。

窓の外には、雪の降るノヴォラドの街。暖色の街灯、白い集合住宅、路面電車の線路、遠い高架交通、整備された近未来的な公共都市の気配。そこに、中央計画AIが都市を支えていることを示す、細い発光ライン、物流・医療・交通・教育を表す抽象的なネットワーク線、少数の赤い異常点が控えめに重なっている。

窓ガラスの反射、または外の雪景色の奥に、ベルザニアの記憶を薄く重ねる。壊れた工場、割れた窓、国境フェンス、監視灯、雪原の暗い輪郭。ただし露骨な戦場絵や爆発にはしない。記憶の影として静かに見える程度にする。

画像全体の感情は、救済の暖かさと、まだ解けない問いが同居していること。悲劇的にしすぎず、明るすぎるユートピアにもせず、静かで重い余韻を持たせる。

## Main Prompt

```text
Social preview key visual for a story-driven visual novel game, 2:1 horizontal composition, 1280x640 px.

Scene:
Night in a warm Novorad apartment during winter. A former Belzanian refugee girl stands by a large window, touching the cold glass with one hand. Outside the window is a quiet snowy Avrora Federation city: warm streetlights, white apartment blocks, old stone rooftops, tram lines, distant elevated railway, clean public infrastructure, calm winter streets. Subtle translucent AI planning network lines overlay the city, connecting food, medicine, transport, schools, housing, power, and communication. A few tiny red anomaly markers appear in the network, restrained and not flashy.

Through the window reflection, or faintly layered in the snowy distance, show quiet memories of Belzania: a ruined factory silhouette, broken window frames, a torn border fence, dim watchtower lights, dark snowfield. These should look like memory fragments, not a literal battlefield.

Characters:
Maryusha, female, 17 or 18, former Belzanian refugee now living in Novorad, Avrora Federation special protected resident, early life observation collaborator for the Central Planning Audit Department. She has a pale winter complexion becoming healthier, slender recovering build, faint dark circles under the eyes, cold gray-green reflective eyes, dark ash-brown shoulder-length hair cleaner and loosely tied back with a simple cloth tie. She wears modest Avrora settlement-period indoor winter clothes: plain dark sweater or knit top, practical trousers, simple scarf nearby, no weapon, no military styling. Her expression is guarded, quiet, observant, emotionally restrained, touched by warmth but still unable to fully relax.

Snezhana, female, 13, former Belzanian refugee now living in Novorad, gentle and vulnerable, beginning to trust peaceful life. She is in the warm apartment background, sleeping or quietly resting under a blanket, safe domestic presence. Light ash-blonde chin-length clean brushed hair, pale blue-gray eyes if visible, warm modest indoor clothes, small school notebook or colored pencils nearby.

Objects:
A slim Avrora link terminal on the table in the foreground or midground, glowing softly. It shows two abstract open records without readable text: one blue-gray AI audit cooperation interface with planning graphs and small red anomaly dots, one muted amber Belzania aid public record interface with archive-like symbols. A repaired cloth shoulder bag from refugee days rests nearby. A small resident ID badge or link card holder may be placed on the table. No readable letters or numbers.

Composition:
Maryusha is the main subject, placed slightly left of center or center. Her silhouette must be readable even as a small social preview thumbnail. Warm apartment interior on one side, cold snowy city and faint Belzania memory outside the window on the other side. The image should clearly communicate the contrast between safety and trauma, AI-managed peace and unresolved homeland, without needing text. Use strong simple shapes, clear focal hierarchy, and enough negative space for social preview readability.

Visual style:
anime illustration, Japanese visual novel key visual, 2000s visual novel illustration, early 2010s light novel illustration, clean lineart, cel shading, expressive eyes, stable character design, character-focused composition, quiet emotional atmosphere, soft winter lighting, restrained near-future socialist AI society, warm interior light versus cold blue snowy exterior, polished game promotional artwork, high readability at small size.
```

## Negative Prompt

```text
photorealistic, realistic skin texture, photography style, cinematic movie poster, Hollywood poster, live action film still, 3D render, CGI, hyperrealism, painterly realism, excessive dramatic lighting, lens flare, shallow depth of field, cyberpunk neon overload, flashy holograms, dystopian horror, surveillance horror poster, explosion, active battle, gunfire, gore, graphic wounds, dead bodies, soldiers as main focus, weapon brandished, military propaganda poster, heroic rescue spectacle, luxury apartment advertisement, tech commercial aesthetic, cluttered background, too many UI details, readable text, logos, title text, watermark, speech bubbles, exaggerated sadness, melodrama, glamour pose, sexualized styling, exposed skin, fantasy outfit, magical elements, changed hairstyle, changed hair color, changed eye color, distorted hands, cropped face, unreadable silhouette
```

## Generation Notes

- まず 1280 x 640 px で生成する。
- 1MBを超える場合は、PNGから高品質JPGへ変換するか、PNGを圧縮する。
- Xのカード表示では中央付近が最も重要なので、マリューシャの顔、窓、端末、AIネットワークが中央寄りに読めるようにする。
- 文字情報は入れない。端末画面も、記号・線・抽象アイコンに留める。
- 赤い異常点は小さく、数個だけにする。サイバー演出を主役にしない。
- ベルザニアの記憶は背景の薄い影として扱う。画像の主題は「救われた後に、まだ問いを抱えている少女」。
- 既存コンセプトアートの方向性に合わせ、写実や映画ポスターではなく、ビジュアルノベルのキービジュアルとして描く。

