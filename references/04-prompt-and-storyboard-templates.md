# 04｜工业化生产模板库（4 锚点卡 / 分镜表 / 10 套 T2I / 8 套 I2V / 后期指令）

本模板库用于把前 3 份文档的剪辑节奏、视觉语法与 AI 避坑工艺，直接落地为可复制给 **Veo / 可灵 / 即梦 / Seedance / Sora / Midjourney / Flux / 剪映 / AE** 的生产资产。

---

## 一、 全局 4 张一致性锚点卡（开工前必须先锁死）

> **铁律**：以下 4 张卡一旦定稿，后续所有分镜（包括纯手部/道具微距！）必须原样复用卡内核心短语，**严禁随手换同义词**；服装必须按变体编号显式调用，杜绝跨场景毛领/肩甲漂移。

```markdown
### [1] Global Style & Rendering Anchor（全局画风与渲染锚点）
- **Visual Style**: Dark realistic 3D Chinese fantasy animation (UE5 cinematic render), hyper-detailed skin pores/scars/fabric weave, dramatic volumetric lighting with Tyndall godrays, fine film grain, shallow cinematic depth of field.
- **Aspect & Lens**: 16:9 widescreen (or 9:16 vertical), anamorphic cinematic lens, 35mm establishing / 85mm close-up grammar.
- **Negative / Hard Avoid**: No flat 2D anime (except intentional impact/chibi cuts), no glossy plastic skin, no oversaturated neon rainbow, NO text, NO Chinese characters, NO numbers, NO watermarks, no distorted extra fingers, no T-pose.

### [2] Character & Costume Variant Anchor（角色与服装变体锁死卡）
- **PROTAGONIST_FACE [主角面部固定词]**: Young East Asian woman in her early 20s, sharp cold dark eyes, subtle thin scratch across nose bridge, jet-black hair tied in a high ponytail with loose damp strands framing her cheeks.
- **COSTUME_A [囚服/初期]**: Tattered muted gray-brown coarse linen tunic with mud stains and frayed hem.
- **COSTUME_B [黑金战袍/中期]**: Fitted matte-black Zhenmosi uniform with crimson cloud-pattern embroidery, thick crimson-tinted fur collar, and weathered bronze beast-head shoulder pauldrons.
- **COSTUME_C [便服/室内]**: Simple ivory-white inner robe with loose sleeves, zero armor pieces.
- **SUPPORTING_MASKED [配角省口型标配]**: Armored imperial guards wearing half-face weathered bronze demon masks covering nose and mouth, dark steel pauldrons.
- **BOSS_ANTAGONIST [反派/巨妖锁死词]**: Towering 4-meter battle-scarred tiger demon, dark striped fur, glowing amber-crimson vertical slit pupils, swirling heavy crimson demonic mist around massive shoulders.

### [3] Scene & Lighting Color-Code Anchor（场景与光色分区卡）
- **PALETTE_MAIN（主线危局）**: Desaturated cold slate-blue and overcast teal-gray atmosphere, wet dark mud reflections, punctuated by high-contrast blood crimson accents.
- **PALETTE_INDOOR（权谋/室内）**: Warm amber candlelight and dim dark-wood shadows contrasted against cool slate-blue moonlight streaming through carved lattice windows.
- **PALETTE_CLASH（高燃对战）**: High-contrast complementary clash — crisp cyan-blue / molten gold protagonist aura vs heavy blood-crimson / eerie emerald-green enemy mist.
- **PALETTE_VOID（系统/识海零背景空间）**: Pure pitch-black cosmic void with subtle floating dust motes, isolating glowing golden holographic constructs with zero background geometry.

### [4] VFX & Post-UI Spec（特效与后期叠层边界卡）
- **In-AI Generated**: Glowing pupils, volumetric fog/godrays, blade aura arcs, spark bursts, shockwave rings, **blank translucent 3D-angled black-gold ancient scroll panels (STRICTLY NO TEXT)**.
- **Post-Production Only (Jianying/AE)**: All vertical Chinese calligraphy title/character/location cards, all system panel Chinese text & numbers, 2-frame impact white-flash, camera shake, RGB chromatic glitch, black title drops.
```

---

## 二、 工业化分镜头与声画剪辑方案表模板

为每一场戏输出如下 11 列生产表（可直接交付生图、生视频、配音与剪辑协同）：

| 镜号 | 时间码 | 时长 | 场景 / 节奏档 | 算力级 | 景别与构图 | 运镜 | 首帧 → 唯一动作 → 落幅 | 光色 / 特效 | 台词（≤10字）与切点 | 音压 / SFX / 后期指令 |
| :---: | :---: | :---: | :---: | :---: | :--- | :--- | :--- | :--- | :--- | :--- |
| `S01` | `00:00–00:02.4` | `2.4s` | 建立 / R2 | B级 | 远景·微仰拍 | 极缓推进 | 阴云尸堆巨妖瘫坐 → 细雨雾气流动 → 锁定巨妖胸口断剑 | 冷青灰 + 天光丁达尔 | `(无台词，纯氛围)` | `-24dB` 低沉风声+远雷铺底 |
| `S02` | `00:02.4–00:03.6` | `1.2s` | 建立 / R2 | A级 | 高空垂直俯拍 | 略微下压 | 主角跌坐尸骸正中 → 猛然抬头环顾 → 定格惊愕仰视 | 冷灰调 + 泥水反光 | `(无台词，J-cut呼吸声起)` | `+4dB` 冲击切：心跳骤起 |
| `S03` | `00:03.6–00:05.8` | `2.2s` | 对峙 / R3 | B级 | 手部微距 Insert | 固定微震 | 沾泥双手特写 → 死死攥紧破旧粗麻衣角 → 指节发白定格 | 冷青灰 + 泥污纹理 | `[3.8s]穿越了`（句尾+0.3s切） | `-28dB` 布料摩擦声+急促呼吸 |
| `S04` | `00:05.8–00:06.1` | `0.3s` | 惊悚 / R1 | **C级** | 2D黑白脱色静帧 | 瞬切+震动 | 巨妖胸口黑雾阴影定格（高反差黑白去色） | 纯黑白高反差 | `(句首同步切)` | **`+8dB` 金属锐鸣 Stinger + 2帧抖动** |
| `S05` | `00:06.1–00:09.1` | `3.0s` | 惊悚 / R3 | B级 | 眼部大特写 ECU | 极缓推近 | 主角双眼满框 → 瞳孔骤缩倒映巨妖轮廓 → 死锁惊骇眼神 | 冷暗底 + 瞳孔微反光 | `[6.3s]上来就遇到顶级大妖`（句尾切） | `-32dB` 骤静切：耳鸣+心跳 |

---

## 三、 10 套模块化首帧生图（T2I Keyframe）提示词公式

> **万能组装公式**：`[景别与机位] + [Character/Costume Anchor] + [瞬时姿态与微表情] + [前景层次/环境] + [Color/Lighting Anchor] + [Global Style & Lens Anchor] + [no text, no watermark]`

### 公式 1｜“瞳中人”眼部大特写（情绪反转 / 觉醒 / 倒影双信息）
> `Extreme close-up (ECU) tightly framing only the sharp eyes and scarred nose bridge of [PROTAGONIST_FACE], dark pupils widening in tension with a crisp glowing reflection of [ENEMY SILHOUETTE / GOLDEN LIGHTNING / POISON CUP] visible inside her irises, loose wet hair strands clinging to pale skin. Dramatic low-key rim lighting, overcast background completely blurred. Shot on 85mm cinema lens, [Global Style Anchor], no text.`

### 公式 2｜手/足/器物微距插镜（全片第一高频标点，替代全身表演）
> `Cinematic macro close-up insert shot of [A MUD-STAINED HAND GRIPPING A WEATHERED BRONZE SWORD HILT / A BLACK LEATHER BOOT STOMPING INTO A WET PUDDLE SPLASHING MUD / WITHERED ELDER FINGERS TURNING DARK WOODEN PRAYER BEADS], gritty tactile textures, shallow depth of field with dark blurred courtyard background. Slanted volumetric Tyndall light beam illuminating floating dust motes. 85mm macro cinema lens, [Global Style Anchor], no text.`

### 公式 3｜巨物压迫尺度构图（Boss 登场 / 越级对峙 / 绝境压迫）
> `Epic low-angle ultra-wide shot emphasizing extreme megalophobia scale contrast: a colossal towering [BOSS_ANTAGONIST / ANCIENT STONE DEITY / GOLDEN TIGER DHARMA PHANTOM] occupying 80% of the stormy frame; directly centered at the lower third stands the tiny solitary dark silhouette of [PROTAGONIST_FACE + COSTUME_B] holding a blade, occupying only 5% of the frame. Swirling storm vortex clouds overhead, volumetric pale godrays piercing darkness, [PALETTE_MAIN], 24mm anamorphic wide lens, [Global Style Anchor], no text.`

### 公式 4｜权谋文戏“逆光剪影过肩 OTS”（零配角建模 + 省口型 + 高压迫）
> `Over-the-shoulder (OTS) medium-wide shot inside a dimly lit ancient imperial palace hall. In the dark right foreground, the pure pitch-black backlit silhouette of a standing mysterious advisor frames 30% of the edge. In the warm candlelit midground, [CHARACTER Anchor] sits symmetrically on a carved throne with a cold calculating half-smile. Cool teal-blue moonlight through wooden lattice windows contrasts against warm amber candlelight and curling incense smoke. 35mm anamorphic lens, [Global Style Anchor], no text.`

### 公式 5｜红青互补能量对撞（高速打戏敌我秒分）
> `Dynamic low-angle action wide shot capturing an explosive mid-air clash: streaking molten-gold and blood-crimson energy aura colliding violently against jagged ice-cyan lightning and dark teal mist in a rain-soaked night courtyard, brilliant orange impact sparks erupting at the center contact point, dramatic motion blur along weapon arcs. High-contrast [PALETTE_CLASH], wet stone reflections, [Global Style Anchor], no text.`

### 公式 6｜2D 黑白水墨/线稿冲击帧（C 级静态零穿模斩杀/破境，0.15–0.3s）
> `Stylized high-contrast pure black-and-white 2D Chinese ink-wash and manga impact frame, stark jagged brush strokes, dramatic radial speed lines bursting from a single razor-sharp white slash silhouette cutting through darkness, extreme graphic contrast, zero gray midtones, explosive kinetic tension, 16:9, no text.`

### 公式 7｜黑底聚光灯 Q 版反差小剧场（低成本喜剧吐槽 / 设定科普）
> `Cute stylized 3D chibi super-deformed (2-head-tall) version of [PROTAGONIST_FACE + COSTUME_B] with exaggerated wide shocked eyes and tiny sweating expression, sitting alone under a single soft overhead spotlight beam against a completely pure pitch-black void background, clean comic lighting, high visual contrast against realistic drama, 16:9, no text.`

### 公式 8｜3D 斜角空白全息古卷 UI（纯黑/实景叠层，文字留给后期！）
> `Medium close-up three-quarter angle of [PROTAGONIST_FACE + COSTUME_B] gazing intently to the side at a translucent 3D-angled holographic black-and-gold ancient Chinese scroll floating in mid-air near her face without blocking her eyes; the scroll surface is blank glowing golden energy mist with intricate geometric border patterns and strictly NO text or characters, casting warm golden rim light onto her cheekbones. [PALETTE_VOID / PALETTE_MAIN], [Global Style Anchor], no text, no letters, no numbers.`

### 公式 9｜门框/窗棂冷暖色温分区构图（阶层压迫 / 空间转场名场面）
> `Symmetrical doorway depth-framing wide shot looking from inside a warm amber candlelit wooden palace interior outward through tall open double doors into a freezing cold slate-blue blizzard night. Centered in the icy backlit threshold, [PROTAGONIST_FACE + COSTUME_B] in a flowing crimson cloak stands framed by drifting snow and volumetric moonlight, dramatic warm-vs-cold color contrast dividing foreground and background. 35mm cinema lens, [Global Style Anchor], no text.`

### 公式 10｜中轴对称威权大殿 / 百官阵列（稳态省算力群像）
> `Grand ultra-wide symmetrical axial shot inside a monumental ancient throne hall, towering carved red pillars receding in strict one-point perspective toward an elevated throne bathed in a single vertical shaft of volumetric sunlight; two neat symmetrical rows of bowed armored guards wearing dark helmets and bronze masks stand motionless along both sides. Gritty stone floor reflections, drifting dust motes, [PALETTE_INDOOR], [Global Style Anchor], no text.`

---

## 四、 8 套模块化图生视频（I2V Motion）提示词公式

> **铁律**：每条仅限 **40–65 英文单词**，严格使用**现在时**，锁定 **`1 种明确运镜 + 1 个单一连续物理动作 + 次级微物理（发丝/衣摆/雨雪/烟尘） + 明确落幅终点（Destination Frame）`**。严禁写 `then cut to / suddenly switch to / scene changes`！

### 模板 1｜慢推心理压迫（适用 R3/R4 眼部 ECU 与对峙，2.5–4s，B 级）
> `Smooth slow push-in toward the character's eyes. She holds completely still as her pupils subtly tighten and faint golden light ignites along her irises. Loose damp hair strands drift gently across her cheek in the cold breeze while misty rain floats in the soft background. Ends locked in a piercing, tense close-up gaze.`

### 模板 2｜微距局部触发动作（适用拔刀/踩泥/叩案/翻卷，1.0–2.0s，A/B 级）
> `Locked-off macro camera with subtle handheld tension. The mud-stained hand tightens abruptly around the weathered bronze sword hilt, knuckles turning pale as the thumb clicks the guard slightly open by an inch. Fine rain droplets tremble on the cold steel. Ends in a sharp poised freeze ready to draw.`

### 模板 3｜高速起势冲锋与刀气劈斩（适用 R1/R2 战斗爆发，1.5–2.5s，A 级）
> `Dynamic low-angle fast tracking shot following the warrior as she plants her boot hard into wet mud—splashing dark droplets upward—and lunges forward in a single swift diagonal slash. A blazing cyan blade aura arcs cleanly through swirling crimson mist, erupting in bright orange sparks. Ends mid-follow-through with embers whipping past the lens.`

### 模板 4｜低机位慢摇仰拍立威（适用 Boss 登场 / 英雄换装定格，3.0–4.0s，A/B 级）
> `Slow dramatic low-angle crane-up starting from muddy clawed feet and rising steadily up the towering armored frame to the snarling face. Heavy crimson mist rolls continuously off broad scarred shoulders beneath storm clouds while torn fabric flaps in strong wind. Ends with glowing amber eyes locking directly onto the camera.`

### 模板 5｜主体锁定横移 + 背景时空溶变（适用 R5 史诗独白，5.0–8.0s，A 级）
> `Steady smooth lateral tracking shot moving left to right, keeping the cloaked figure walking at a calm constant pace in the left-center frame. Without breaking stride, the misty background behind her seamlessly dissolves from smoldering dark ruins into a twilight rain-swept river dock. Flowing robes and drifting fog unify the continuous passage of time.`

### 模板 6｜静帧微动文戏呼吸（适用 R4 权谋长台词/站桩，3.0–5.0s，B 级低成本）
> `Subtle slow lateral dolly drift inside the dim hall. The seated ruler remains poised and nearly motionless, giving only a slow calculated blink and slight knowing smirk while warm candlelight flickers softly across silk embroidery and thin incense smoke curls lazily upward in the foreground. Ends in quiet imposing stillness.`

### 模板 7｜大远景冲击波/法相绽放（适用 R1 结果态秒杀，2.0–3.5s，A 级）
> `High-angle wide shot pulling slowly backward as a colossal translucent golden shockwave ring blasts outward across the misty courtyard from the center figure. Dust clouds, swirling dry leaves, and glowing golden embers surge outward in all directions beneath dark thunderclouds. Ends revealing a vast smoking crater in dramatic stillness.`

### 模板 8｜环境色温/光影突变转场（适用悬疑压迫/大敌降临，2.0–3.0s，B 级）
> `Static top-down close-up of rain-damp stone tiles. Warm golden lantern light smoothly drains away as an eerie cold slate-blue shadow and creeping icy mist sweep rapidly across the stone surface from left to right, water puddles rippling slightly from distant heavy tremors. Ends fully engulfed in frigid blue darkness.`

---

## 五、 后期剪辑、字效与音效速查指令表（C 级提质关键）

| 导演意图 | 剪映 / AE 后期标准操作 | 推荐音效组合（SFX） |
| :--- | :--- | :--- |
| **打击命中 / 秒杀瞬间** | 画面前插 `1–2 帧纯白闪` 或 `2D黑白线稿帧` + `0.15s` 强缩放微震（Camera Shake）+ 径向模糊 | `Metallic Stinger` + `Heavy Sub-bass Drop` + `Crisp Slash Whoosh` |
| **反派立 Flag 瞬打脸** | 句中硬切 `0.2s` 彻底静音抽空 BGM → 切嵌墙远景微震 → 慢推主角入场 | `Record-Scratch / Sudden Silence Cut` → `Dull Thud` → `Cold Wind` |
| **Boss / 地名 / 境界登场** | 画面留白侧（左上/右上）压入**竖排粗犷毛笔书法主字 + 细竖排境界副标** + 轻微水墨晕染淡入（`0.3s`） | `Deep War Drum (Taiko)` + `Ink Brush Swish` |
| **系统面板结算升级** | 在 AI 生成的空白发光卷轴上用 `Corner Pin 3D 透视对齐` 贴入清晰中文字体与跳动数值，叠微弱外发光 | `Ancient Bell Chime` + `Crisp Hologram UI Click` |
| **冷开篇 / 跨季落版** | 动作临界点硬切 `1.5–2.5s` 纯黑屏 + 居中白色书法片名缓缩放 +（可选）1秒后硬切灾变黑云 | `Pre-Quiet 0.8s` → `Massive Cinematic Boom` + `Thunder Crack` |

---

## 六、 台词“爆款漫剧化”洗稿 4 步公式

把小说原文或粗稿台词塞进分镜前，强制按以下 4 步洗稿：
1. **一刀劈碎长句（严格 ≤10 字）**：
   - 原句（28 字）：`“一个没有户籍路引的贱籍逃犯，就算侥幸活到下一座城镇又能如何呢？”`
   - 漫剧洗稿（3 镜 / 3 短句）：`没有户籍路引的贱籍逃犯`（11字，OTS）→ `就算侥幸活到下一座城`（10字，手部微距）→ `又能如何`（4字，眼部ECU慢推，句尾+0.3s切对方震惊！）
2. **砍光书面连接词与心理废话**：删除“因为、所以、其实我觉得、不仅如此、总而言之”，全部改写成**短判断 + 视觉动作**。
3. **打戏一键静音瘦身**：进入 `R1/R2` 战斗段，把整段招式说明压缩成 `2–4 字` 爆点短句（`找死` / `全部灌入` / `不够` / `破` / `在你后面`），其余信息全交给红青光效、眼神和旁观者惊呼！
4. **每 90–150 秒强制落 6 大强尾钩**：检查每段最后 3 秒——如果是“众人平安回城休息”，**立刻重写**！必须截断在“未落下的杀招 / 暴露边缘的秘密 / 新降临的更高阶巨妖 / 刚拿到神通准备试刀”上。
