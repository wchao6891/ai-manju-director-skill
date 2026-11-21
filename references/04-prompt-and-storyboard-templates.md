# 04｜工业化生产模板库（4 锚点卡 / 分镜表 / 12 套 T2I / 8 套 I2V / 后期指令）

本模板库用于把前 3 份文档（100% 全量 2,455 张拼图 + 40.9h 一手数据 + 原片 5fps 拆解）的剪辑节奏、镜头纵深语法与 AI 避坑工艺，直接落地为可复制给 **Veo / 可灵 / 即梦 / Seedance / Sora / Midjourney / Flux / 剪映 / AE** 的生产资产。

---

## 一、 全局 4 张一致性锚点卡（开工前必须锁死，治 #1 头号服装漂移翻车）

> **铁律**：全剧 164 区块中 `59.1%` 出现跨镜服饰/配饰漂移、`18.3%` 出现汉字乱码。以下 4 张卡定稿后，每条分镜（含手部/道具微距）必须原样复用核心短语，服装必须按编号显式调用！

```markdown
### [1] Global Style & Lens Anchor（全局画风与光学焦段锚点）
- **Visual Style**: High-contrast cinematic 3D Chinese fantasy animation (UE5 film render, mature s05 bright-crisp contrast), tactile skin pores/scars/fabric weave, dramatic volumetric Tyndall light shafts, deep foreground-midground-background parallax, shallow depth of field.
- **Aspect & Optical Grammar**: 16:9 widescreen (or 9:16 vertical); alternate extreme wide-angle (18–24mm) for megalophobia/foreground perspective vs. telephoto (85–135mm) for emotional compression and macro inserts; avoid flat eye-level symmetrical posing except deliberate authority/power-up tableaux.
- **Negative / Hard Avoid**: No flat 2D anime (except intentional C-tier impact/chibi/ink cuts), no glossy plastic skin, NO text, NO Chinese characters, NO numbers, NO watermarks, no extra limbs, no T-pose.

### [2] Character & Costume Variant Anchor（角色与服装变体编号锁死卡）
- **PROTAGONIST_FACE [主角面部固定词]**: Lean young East Asian woman in her early 20s, sharp determined dark eyes, subtle fine scratch across nose bridge, jet-black hair tied in a high ponytail with loose strands framing her cheeks.
- **COSTUME_A [囚服/初期]**: Tattered muted gray-brown coarse linen tunic with mud stains and frayed hem.
- **COSTUME_B [黑金战袍/中期]**: Fitted matte-black uniform with crimson cloud-pattern embroidery, thick crimson-tinted fur collar, and weathered bronze beast-head shoulder pauldrons.
- **COSTUME_C [白衣便服/室内]**: Crisp ivory-white martial inner robe with loose sleeves, strictly zero armor pieces and zero fur collar.
- **SUPPORTING_MASKED [配角省口型标配]**: Armored guards wearing half-face weathered bronze demon masks covering nose and mouth.
- **BOSS_ANTAGONIST [反派/巨妖锁死词]**: Towering 4-meter battle-scarred demon general, dark striped armor/fur, glowing amber-crimson vertical pupils, heavy crimson demonic mist rolling off shoulders.

### [3] Scene & Color-Clash Anchor（场景与阵营互补色卡）
- **PALETTE_MAIN（主线危局）**: Desaturated cold slate-blue and overcast teal-gray atmosphere, wet dark ground reflections, punctuated by high-contrast blood crimson accents.
- **PALETTE_INDOOR（权谋/室内）**: Warm amber candlelight and dark carved wood contrasted against cool blue moonlight/snow visible through open lattice windows.
- **PALETTE_CLASH（巅峰对战）**: High-contrast complementary clash — crisp cyan-blue / molten gold protagonist aura vs. heavy crimson-red / eerie emerald-green enemy mist.
- **PALETTE_VOID（纯黑虚空零背景空间）**: Pure pitch-black cosmic void with subtle floating dust motes, isolating glowing golden holographic constructs or chained trauma memories with zero background geometry.

### [4] Post-Production Only Spec（后期叠层边界，严禁 AI 生字）
- **AI 生成范围**：发光瞳孔、体积光雾、刀气弧光、火星、环形冲击波、水墨晕染、**空白半透明 3D 斜角黑金古卷/光幕（STRICTLY NO TEXT）**。
- **后期剪映/AE 专属**：全部竖排毛笔书法字卡（地名/人名/境界/招式）、全部系统面板中文与数字、双色交替冲击闪帧（2 帧白闪/黑闪）、Camera Shake 震动、RGB 色差、103% 四角去水印裁边。
```

---

## 二、 工业化分镜头与声画剪辑方案表模板（11 列标准）

| 镜号 | 时间码 | 时长 | 场景 / 档位 | 算力级 | 焦段与景别构图 | 运镜 | 首帧 → 唯一动作 → 落幅 | 光色 / 特效 | 台词（≤10字）与切点 | 音压 / SFX / 后期 |
| :---: | :---: | :---: | :---: | :---: | :--- | :--- | :--- | :--- | :--- | :--- |
| `S01` | `00:00–00:02.4` | `2.4s` | 建立 / R2 | B级 | 24mm 广角仰拍·前景框 | 极缓推进 | 暗色残檐前景框住阴云尸堆巨妖，细雨天光倾泻 | 冷青灰 + 丁达尔光柱 | `(无台词，纯氛围)` | `-24dB` 低沉风声+远雷 |
| `S02` | `00:02.4–00:03.6` | `1.2s` | 建立 / R2 | A级 | 90° 高空垂直俯拍 | 略微下压 | 主角跌坐尸骸正中 → 猛然抬头环顾 → 惊愕仰视 | 冷灰调 + 泥水反光 | `(J-cut 急促呼吸起)` | `+4dB` 冲击切：心跳骤起 |
| `S03` | `00:03.6–00:05.8` | `2.2s` | 对峙 / R3 | B级 | 85mm 手部微距 Insert | 固定微震 | 沾泥双手特写 → 死攥破麻衣角 → 指节发白定格 | 冷青灰 + 泥污纹理 | `[3.8s]穿越了`（句尾+0.3s切） | `-27dB` 布料摩擦声 |
| `S04` | `00:05.8–00:06.0` | `0.2s` | 高潮 / R1 | **C级** | **红底黑剪影瞬杀/冲击** | 硬切+强震 | 纯正红底+纯黑极简剪影爆发（0.2s 零穿模冲击） | 高饱和纯红+纯黑 | `(无台词)` | **`+8dB` 金属爆鸣+2帧闪白** |
| `S05` | `00:06.0–00:09.0` | `3.0s` | 惊悚 / R3 | B级 | 100mm 瞳中人 ECU | 极缓推近 | 双眼满框 → 瞳孔骤缩倒映巨妖轮廓 → 死锁惊骇 | 冷暗底 + 虹膜倒影 | `[6.3s]上来就遇到顶级大妖` | `-32dB` 骤静切：耳鸣+心跳 |

---

## 三、 12 套模块化首帧生图（T2I Keyframe）提示词公式

> **万能公式**：`[焦段+景别+前景层次] + [Character & Costume Variant Anchor] + [瞬时姿态与视线] + [环境] + [Color/Lighting Anchor] + [Global Style Anchor] + [no text, no watermark]`

### 公式 1｜“瞳中人”眼部大特写（情绪反转 / 觉醒 / 倒影双信息）
> `Extreme close-up (ECU) on 100mm macro cinema lens tightly framing only the sharp eyes and nose bridge of [PROTAGONIST_FACE], glowing amber-gold irises widening with a crisp visible reflection of [ENEMY SILHOUETTE / GOLDEN LIGHTNING / INCOMING NEEDLES] inside both pupils, stray damp hair strands clinging to pale textured skin. Moody low-key lighting with rim reflection, dark blurred background. [Global Style Anchor], no text.`

### 公式 2｜手/足/器物微距插镜（全剧 98.8% 区块第一标点）
> `Cinematic 85mm macro close-up insert shot of [A MUD-STAINED HAND TIGHTENING ON A BRONZE SWORD HILT / BLACK LEATHER BOOT STOMPING INTO A RAIN PUDDLE / WITHERED FINGERS TURNING DARK PRAYER BEADS], gritty tactile textures, shallow depth of field with dark blurred courtyard behind. Slanted volumetric Tyndall light beam illuminating floating dust motes. [Global Style Anchor], no text.`

### 公式 3｜巨物压迫尺度构图（后期 `s03–s05` 飙至 40% 核心奇观）
> `Epic 20mm ultra-wide low-angle shot emphasizing extreme megalophobia scale contrast: a colossal towering [BOSS_ANTAGONIST / ANCIENT STONE DEITY / GOLDEN DHARMA PHANTOM] occupying 80% of the stormy frame; centered near the lower third stands the tiny solitary silhouette of [PROTAGONIST_FACE + COSTUME_B] holding a blade, occupying only 5% of the frame. Swirling storm clouds overhead, volumetric pale godrays piercing darkness, [PALETTE_MAIN], [Global Style Anchor], no text.`

### 公式 4｜三层纵深前景框构图（告别平淡正面摆拍的电影感秘诀）
> `Dynamic 24mm wide cinema shot utilizing deep three-layer foreground framing inside [ANCIENT PALACE / CLIFFSIDE TEMPLE]: extreme dark foreground left and right framed tightly by [HEAVY HANGING IRON CHAINS / CARVED WOODEN DOOR GAP / BLURRED WEAPON BLADE & DRIFTING PETALS], drawing the eye straight into crisp midground focus on [CHARACTER + COSTUME], while towering backlit architecture recedes into misty volumetric background depth. [PALETTE_INDOOR], [Global Style Anchor], no text.`

### 公式 5｜权谋文戏“逆光剪影过肩 OTS”或“强圣光遮面留白”
> `Over-the-shoulder (OTS) 35mm anamorphic medium-wide shot inside a dimly lit palace hall. Extreme dark right foreground shows the pure pitch-black backlit silhouette of a standing mysterious figure framing 30% of the edge (OR: at the far top of monumental stone steps, an authoritative figure stands completely veiled behind blinding golden-white volumetric sunlight shafts, revealing only a majestic silhouette). Warm amber candlelight contrasts against cool slate-blue lattice window moonlight and curling incense smoke. [Global Style Anchor], no text.`

### 公式 6｜红青互补能量对撞（高速打戏敌我秒分）
> `Dynamic low-angle 24mm Dutch-tilted action shot capturing an explosive mid-air clash: blazing molten-gold and crimson sword aura colliding violently against jagged ice-cyan lightning and dark teal mist in a rain-soaked night arena, brilliant orange impact sparks erupting at the center contact point, dramatic motion blur along weapon arcs. [PALETTE_CLASH], [Global Style Anchor], no text.`

### 公式 7｜2D 双色交替冲击帧（C 级静态 0.10–0.20s，原片 5fps 实测核爆点）
> - **黑底白爆版**：`Stylized high-contrast 2D impact frame, pure pitch-black void background with an explosive blinding pure-white radial energy starburst erupting from the exact center, razor-sharp jagged kinetic speed lines, zero gray midtones, 16:9, no text.`
> - **白底黑墨版**：`Stylized high-contrast 2D Chinese ink-wash manga impact frame, stark pure white background with violent jagged black sumi-e ink splatters and radial fracture lines exploding outward from a slashing blade silhouette, zero colors, 16:9, no text.`

### 公式 8｜★ [s03–s05 进阶] 纯红底 + 纯黑剪影艺术瞬杀帧（C 级静态 0.2s，100% 过审）
> `Hyper-stylized graphic 2D/2.5D kill impact frame: saturated deep blood-crimson solid background illuminated by a stark blinding diagonal white slash flash; in crisp flat pitch-black silhouette, a cloaked warrior strikes clean through a towering enemy shadow with stylized abstract black-and-red ink droplets spraying across the frame, zero gore details, extreme graphic cinema contrast, 16:9, no text.`

### 公式 9｜★ [s03–s05 进阶] 漫画多格斜切分屏群像震惊/同步出招（C 级省多镜成本）
> `Dynamic 4-panel diagonal manga-style split-screen composition separated by razor-sharp thin glowing black-and-white border slashes, simultaneously framing four distinct alarmed rival elders' tight eye close-ups reacting in shock from alternating dramatic angles, dark moody lighting with glowing red and cyan rim highlights, 3D Chinese fantasy render style, 16:9, no text.`

### 公式 10｜黑底聚光灯 Q 版反差小剧场 / 写实肩头迷你 Q 版（57.9% 区块使用）
> `Cute stylized 3D super-deformed chibi (2-head-tall) version of [PROTAGONIST_FACE + COSTUME_B] with exaggerated shocked starry/spiral eyes and comical sweating expression, sitting alone under a single soft overhead spotlight beam against a completely pure pitch-black void background, high comic contrast, 16:9, no text.`

### 公式 11｜3D 斜角空白全息古卷 UI（文字 100% 留给后期防乱码！）
> `Three-quarter medium close-up of [PROTAGONIST_FACE + COSTUME_B] gazing intently to the side at a translucent 3D-angled holographic black-and-gold ancient Chinese scroll floating in mid-air near her face without blocking her eyes; the scroll surface contains ONLY abstract glowing golden energy mist and ornate geometric border lines with strictly NO text, NO characters, and NO numbers, casting warm golden rim light onto her cheekbones. [PALETTE_VOID], [Global Style Anchor], no text.`

### 公式 12｜90° 上帝垂直俯拍几何法阵 / 跨季匹配剪辑帧
> `Strict 90-degree top-down bird's-eye overhead ultra-wide shot looking straight down onto [A PERFECT CIRCULAR GLOWING CYAN-GOLD RUNES ARRAY ON SNOW / A SYMMETRICAL AUTUMN LEAF COURTYARD RING], a solitary figure centered precisely at the geometric bullseye as concentric shockwave dust ripples outward in a crisp circle, dramatic volumetric godrays, [Global Style Anchor], no text.`

---

## 四、 8 套模块化图生视频（I2V Motion）提示词公式

> **铁律**：每条仅限 **40–65 英文单词**，现在时，锁定 **`1 种明确运镜 + 1 个单一连续物理动作 + 次级微物理 + 明确落幅终点（Destination Frame）`**。严禁写 `then cut to / scene switches`！

1. **慢推心理压迫（R3/R4 眼部 ECU，2.5–4s，B 级）**：
   > `Smooth slow push-in toward the character's eyes. She holds completely still as her pupils subtly contract and molten golden light ignites along her irises. Loose damp hair strands drift gently across her cheek in the cold breeze while faint mist floats behind. Ends locked in a piercing, unblinking close-up gaze.`
2. **微距局部物理触发（拔刀/踏水/叩案，1.0–2.0s，A/B 级）**：
   > `Locked-off macro camera with subtle handheld tension. The mud-stained hand tightens abruptly around the weathered bronze sword hilt, knuckles turning pale as the thumb pushes the guard open an inch. Rain droplets tremble on cold steel. Ends in a sharp poised freeze ready to draw.`
3. **高速起势冲锋与刀气劈斩（R1/R2 战斗爆发，1.5–2.5s，A 级）**：
   > `Dynamic low-angle fast tracking shot following the warrior as she plants her boot hard into wet mud—splashing dark droplets upward—and lunges forward in a single swift diagonal slash. A blazing cyan blade aura arcs cleanly through swirling crimson mist, erupting in bright orange sparks. Ends mid-follow-through with embers whipping past the lens.`
4. **低机位慢摇仰拍立威（Boss 登场 / 英雄定格，3.0–4.0s，A/B 级）**：
   > `Slow dramatic low-angle crane-up starting from muddy clawed feet and rising steadily up the towering armored frame to the snarling face. Heavy crimson mist rolls continuously off broad scarred shoulders beneath storm clouds while torn fabric flaps in strong wind. Ends with glowing amber eyes locking directly ahead.`
5. **主体锁定横移 + 背景时空溶变（R5 史诗独白，5.0–8.0s，A 级）**：
   > `Steady smooth lateral tracking shot moving left to right, keeping the cloaked figure walking at a calm constant pace in the left-center frame. Without breaking stride, the misty background behind her seamlessly dissolves from smoldering war ruins into a twilight rain-swept lotus pond and river dock. Flowing robes and drifting fog unify the continuous passage of time.`
6. **静帧微动文戏呼吸（原片 5fps 实测确认的低成本 B 级公式，2.0–4.0s）**：
   > `Subtle slow lateral dolly drift inside the dimly lit hall. Both figures remain grounded and nearly motionless—only minimal breathing, a calculated slow blink, and slight wrist shift—while warm candlelight flickers across silk embroidery and thin incense smoke curls upward in the blurred foreground. Ends in quiet imposing stillness.`
7. **大远景冲击波/法相绽放（R1 结果态秒杀，2.0–3.5s，A 级）**：
   > `High-angle wide shot pulling steadily backward as a colossal translucent golden shockwave ring blasts outward across the courtyard from the center figure. Swirling dust clouds, dry leaves, and glowing embers surge outward beneath dark thunderclouds. Ends revealing a vast smoking crater in dramatic stillness.`
8. **物理擦拭遮罩 / 色温渐染转场（2.0–3.0s，B 级）**：
   > `Static close-up of rain-damp stone tiles (OR: fast tracking whip-pan as a massive pink blossom petal sweeps closely across the entire foreground lens). Warm golden lantern light drains smoothly away as cold slate-blue shadow and creeping icy mist sweep rapidly across the frame from left to right. Ends completely engulfed in frigid blue darkness ready for a clean cut.`

---

## 五、 后期剪辑、字效与音效速查指令表（C 级提质关键）

| 导演意图 | 剪映 / AE 后期标准操作 | 推荐音效组合（SFX） |
| :--- | :--- | :--- |
| **巅峰打击 / 秒杀连爆** | 0.6s 内交替插入 **`0.15s 黑底白爆`** + **`0.10s 白底黑墨/红底剪影`** + `15% Camera Shake` + 2 帧白闪 | `Metallic Stinger (+7dB)` + `Sub-bass Drop` + `Crisp Whoosh` |
| **反派立 Flag 骤静打脸** | 句中硬切 **`0.2–1.2s` 彻底静音至 `-35 dBFS`** 抽空 BGM → 单声清脆微物落响（针落/茶滴）→ 慢推反杀 | `Drop-to-Quiet Silence Cut` → `Single Crystalline Ding` |
| **Boss / 地名 / 境界登场** | 画面留白侧压入**竖排粗犷毛笔书法主字 + 细竖排境界副标** + 水墨晕染淡入（`0.3s`） | `Deep War Drum (Taiko)` + `Ink Brush Swish` |
| **系统面板防乱码叠层** | 在 AI 空白发光卷轴上用 `Corner Pin 3D 透视` 贴入透明 PNG 清晰汉字与数值，加微外发光 | `Ancient Bell Chime` + `Hologram UI Click` |
| **防平台水印统一 QC** | 导出前对全部 AI 素材执行 **`103% 微放大裁边`** 或四角巡检，彻底清零 `29.3%` 常见水印残留 | — |

---

## 六、 台词“爆款漫剧化”洗稿 4 步公式

1. **一刀劈碎长句（严格 4–10 字，绝不超 15 字）**：把 25 字书面长句按气口劈成 3 镜短句（中位 6 字），句间气口压缩在 `≤0.5s`。
2. **砍光书面连接词与心理废话**：删掉“因为、所以、其实我觉得、总而言之”，全部改写成短判断 + 物理微距动作。
3. **打戏一键静音瘦身**：进入 `R1/R2` 战斗段，台词压到 `≤10 句/分`，只留 `2–4 字` 爆点短句（`找死` / `破` / `不够` / `动手`），其余交由红青特效、眼神与旁观反应演。
4. **每 1.5–2.0 分钟视觉模态切换 + 强尾钩**：检查是否出现超过 2 分钟的单一站桩文戏或平淡日常——立刻切入喜剧 Q 版、冲突升级、系统结算或更高阶威胁现身！
