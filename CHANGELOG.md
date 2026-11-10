# 更新紀錄 / Changelog

## Ver. 0.172 — 2026-11-11

### 繁體中文

- 火箭飛彈在用光彈藥後會自動開始裝填；仍可按右鍵（手柄 Y）提前裝填。
- 降低「全彈發射」飛彈的追蹤性能；目標偏離飛彈前方超過 90 度時，飛彈會放棄該目標繼續前進，不再 180 度大轉彎。
- 兩個 EX 武裝欄位現在可以裝備同一種武裝，各自計算次數與冷卻。
- 「創世紀」炮擊落地後的 10 秒內不會生成新的一般敵人與 Boss（Boss 計時同步暫停），避免白光散去後馬上湧入大量敵人。

### English

- Rocket Missiles now start reloading automatically when the ammo runs out; right click (Y on a gamepad) still reloads early.
- Full Salvo rockets home in less sharply. A rocket drops any target more than 90 degrees off its nose and flies on, so it no longer makes U-turns.
- Both EX armament slots can now hold the same armament, with separate charges and cooldowns.
- No new regular enemies or bosses spawn for 10 seconds after the Genesis strike lands (the boss timer pauses too), so a new crowd no longer floods in as the white flash clears.

## Ver. 0.171 — 2026-11-11

### 繁體中文

- 新增主武器「火箭飛彈」，並改為蜂鳥的預設主武器：每秒 1.6 發，彈藥 8 發，按右鍵（手柄 Y）裝填 3 秒，裝填期間無法射擊。火箭射出後逐漸加速並帶有微幅追蹤，拖曳白色煙霧，接觸敵人或地形後爆炸，對半徑 120 內的敵人造成 100 爆炸傷害。可搭配高能核心、超頻核心、分散射擊、彈體擴展、霜凍彈藥與精密校準。
- 新增火箭飛彈專屬卡片「全彈發射」：彈藥 +100%、每發基礎傷害 -25%；每次開火向機體前方連續彈射 8 發飛彈，短暫滯空後追蹤目標飛去，射擊間隔 1.6 秒。
- 火箭飛彈使用武器狀態欄顯示彈藥：實心飛彈為已裝填，空心飛彈為空彈槽；每排最多 8 發，超過時往上增加一排，裝填時依序填滿。
- 高能核心提高蜂群飛彈與火力覆蓋的傷害；超頻核心縮短所有 EX 武裝的冷卻時間；分散射擊每級讓蜂群飛彈多 2 枚、火力覆蓋多 1 個目標。加成依目前主武器的卡片等級計算。
- 超頻修復改為每秒回復最大裝甲的 10%。
- 火力覆蓋的爆炸直徑提高到 210，標記會以每秒最多 240 的速度追蹤目標。
- 立體機動發動期間有 75% 機率閃避敵方子彈（光束與雷射除外），特效改為沿機體移動軌跡留下快速消散的半透明殘影。
- 蜂群飛彈的煙霧拖尾消散得更快。
- 蜂群飛彈、火力覆蓋、EMP、電子領域與立體機動加入專屬音效。
- 標題畫面的 EX 武裝欄位改為點擊後展開選擇面板。
- 「熾焰過載」的大型光束傷害改為「基礎傷害 × 4 ×（1 + 一般光束數量 × 0.75）」，並持續到 120 熱量為止。
- 移除卡片「相位餘護」、「動能迴路」與「爆發餘勢」。
- Argor-717 的履帶被擊中時會閃紅，艦身被擊中時會噴出金屬火花。
- 敵人圖鑑中的 Argor-717 移到獨立的「EX Boss」分類。
- 同步更新英文介面、說明與中英文圖鑑。

### English

- Added the Rocket Missiles main weapon, now the Hummingbird's default: 1.6 shots per second and 8 rounds of ammo. Right click (Y on a gamepad) reloads over 3 seconds, with no firing meanwhile. Rockets accelerate after launch with slight homing, trail white smoke and explode on enemies or terrain, dealing 100 explosive damage within a radius of 120. Works with Power Core, Overclock Core, Multishot, Projectile Expansion, Frost Ammo and Precision Calibration.
- Added Full Salvo, a Rocket Missiles card: ammo +100% and base damage per rocket -25%. Each trigger ejects 8 rockets in quick succession in front of the ship; they hover briefly, then home in on targets. Salvos are 1.6 seconds apart.
- Rocket Missiles show their ammo in the weapon status bar: filled rockets are loaded, hollow ones are empty slots. Each row holds up to 8, extra rows stack upward, and reloading fills them in order.
- Power Core raises Swarm Missiles and Fire Support damage, Overclock Core shortens every EX armament cooldown, and each Multishot rank adds 2 swarm missiles and 1 Fire Support target. The bonuses use the current weapon's card ranks.
- Overclock Repair now restores 10% of maximum armor per second.
- Fire Support blasts are now 210 across, and the marks follow their targets at up to 240 per second.
- 3D Maneuver now dodges 75% of enemy rounds while active (beams and lasers excepted), and its effect is now fast-fading translucent afterimages along the ship's path.
- Swarm Missile smoke trails fade faster.
- Swarm Missiles, Fire Support, EMP, Electro Field and 3D Maneuver have their own sound effects.
- The title-screen EX armament slots now open a selection panel when clicked.
- The Blazing Overload large beam now deals base damage × 4 × (1 + normal beam count × 0.75) and lasts until heat reaches 120.
- Removed the Phase Guard, Kinetic Circuit and Burst Momentum cards.
- Argor-717's tracks flash red when hit, and its hull throws metal sparks when struck.
- Argor-717 now has its own "EX Boss" section in the enemy codex.
- Updated the English interface, guide and bilingual codex pages.

## Ver. 0.17 — 2026-11-10

### 繁體中文

- 新增 EX 武裝系統：開局前在標題畫面的機體下方選擇最多兩種 EX 武裝，不綁定機體；以 Q／E（手柄 RT／LT）發動。切換機體時若欄位 1 為空，會自動帶入該機體的代表武裝。
- 可選的 EX 武裝共六種：超頻修復（回復裝甲並提升射速）、電子領域（展開法陣，陣內提升射速並減傷）、立體機動（補滿 EN，短時間免除碰撞傷害）、蜂群飛彈（兩側齊射追蹤微型飛彈）、EMP（電磁脈衝癱瘓敵人並消除敵彈）、火力覆蓋（標記最近 5 名敵人後空中砲擊）。
- 擊敗 Argor-717 後取得當局限定的 EX 武裝「創世紀」，可選擇裝備、替換或捨棄：從地圖最遠的斜對角發射電磁砲，擊殺 Boss 以外的所有敵人並重創 Boss。
- EX 武裝 HUD 顯示冷卻、剩餘次數與發動狀態，可在設定中調整位置、大小、透明度與顯示；空欄位以裝甲板圖示呈現。
- 新增實驗性事件「6:14」：11 架菁英敵人「使徒」包圍玩家繞行射擊，事件期間暫停一般敵潮與 Boss 計時。使徒會繞過地形追擊，移動帶有慣性，玩家突然加速時可短暫甩開。
- 新增事件「Argor Arrival」與 EX Boss「Argor-717」：清除「6:14」後接續發生。開場有警告、電磁砲轟擊與陸行艦進場演出；Argor-717 沿地圖邊緣巡行，擁有雙管機砲、雷射砲台、貫穿地形的主砲、使徒出擊、垂直飛彈與狂暴蒸氣排放等兩階段攻擊。擊毀後玩家提升 4 級，並在之後 10 秒內不生成新敵人。
- 新增手柄操作（Xbox 配置，PlayStation 手柄自動切換按鍵圖示）：左搖桿移動、右搖桿瞄準、RB 射擊、LB 加速、Y 砲彈、RT／LT 發動 EX 武裝、A 升級、X 自動射擊；選單可用十字鍵或左搖桿操作。
- 新增介面音效。
- 調整巨噬蠕蟲 Boss：鑽地冷卻 5 秒、每次鑽地都有音效，前兩次破土後朝玩家躍進。玩家核心「饕餮利爪」的破土衝擊波半徑由 120 提高到 180。
- 彩蛋卡「Spin Me Round」改為按 F 切換高速旋轉並持續開火。
- 升級選單中可按 ESC 暫停、按 ~ 開關開發人員工具。
- 移除機體圖示 HUD 與畫面最下方的說明文字；整理靶場工具與開發人員工具的功能分組。
- 修正使用靶場或開發人員工具列後鍵盤失效；移除進入靶場與守望者觸手盡毀時的紅字提示。
- 同步更新英文介面、說明與中英文圖鑑。

### English

- Added EX Armaments: before a run, choose up to two EX armaments below the ship on the title screen. They are not tied to a ship and are triggered with Q / E (RT / LT on a gamepad). Switching ships fills an empty first slot with that ship's signature armament.
- Six EX armaments are available: Overclock Repair (restores armor and raises fire rate), Electro Field (a circle that raises fire rate and reduces damage taken inside it), 3D Maneuver (refills EN and briefly removes collision damage), Swarm Missiles (homing micro-missiles from both sides), EMP (a pulse that disables enemies and destroys enemy rounds) and Fire Support (air strikes on the 5 nearest enemies).
- Defeating Argor-717 awards Genesis, an EX armament for the current run that you can equip, swap in or discard: a railgun shot from the farthest map corner that kills every non-boss enemy and heavily damages bosses.
- The EX armament HUD shows cooldowns, charges and active effects, and can be repositioned, resized, faded or hidden in settings. Empty slots show an armor plate.
- Added the experimental event "6:14": 11 elite Apostles surround and circle the player while firing, and regular waves and the boss timer pause during the event. Apostles path around terrain and move with inertia, so a sudden boost can briefly shake them off.
- Added the event "Argor Arrival" and the EX Boss Argor-717, which follows a cleared "6:14". It opens with warnings, a railgun strike and the landship's entrance. Argor-717 patrols the map edge with twin guns, laser turrets, a terrain-piercing main gun, Apostle sorties, vertical missiles and an enraged steam purge across two phases. Destroying it grants 4 levels, and no new enemies spawn for the next 10 seconds.
- Added gamepad support (Xbox layout, with PlayStation glyphs detected automatically): left stick to move, right stick to aim, RB to fire, LB to boost, Y for cannon rounds, RT / LT for EX armaments, A to upgrade and X for auto-fire. Menus work with the D-pad or left stick.
- Added interface sound effects.
- Updated the Devourer Worm boss: 5-second burrow cooldown, a sound on every burrow, and a lunge toward the player after its first two surfacings. The player's Ravenous Claws core shockwave radius increased from 120 to 180.
- The Spin Me Round easter-egg card now turns F into a high-speed spin with continuous fire.
- ESC pauses and ~ toggles the developer tools from the upgrade picker.
- Removed the ship-icon HUD and the footer text at the bottom of the screen, and regrouped the firing-range and developer toolbars by function.
- Fixed the keyboard stopping working after using the firing-range or developer toolbar, and removed the red notices shown on entering the range and when all Watcher tentacles are destroyed.
- Updated the English interface, guide and bilingual codex pages.

## Ver. 0.164 — 2026-11-05

### 繁體中文

- 新增可在標題畫面開啟的實驗性事件功能，預設關閉。「觀測系統錯誤」會先發出警告，再以警示帶遮蔽部分視野，搭配事件音效與音樂；暫停時事件進度停止。
- 調整事件音樂：危險音樂在升級選單中持續播放，事件結束後淡回一般背景音樂。
- 多 Boss 場面優先生成目前場上沒有的種類，減少同種 Boss 重複出現。
- 調整巨獸核心「破軍巨足」：持續加速前原地蓄力 0.8 秒且不消耗 EN，加速轉向速度降低 30%；不同等級有各自的極速與加速時間。
- 「奈米修復」改為每秒額外回復「卡片等級 × 0.5 ＋ 最大裝甲的 1%」，並隨最大裝甲變動同步調整；移除取得卡片時立即修復 15 裝甲的效果。
- 六張機體防禦卡統一使用青綠色，涵蓋升級選項、靶場卡片、已持有卡與圖鑑；未解鎖卡仍維持灰色。
- 「火箭跳」與「質量效應」改為互斥，靶場套用升級時也會處理衝突。
- 調整「龍息」為每 0.60 秒噴出 80 顆火焰粒子，每顆基礎傷害 3；前端火焰飛得更遠、存在更久，靠近機體的火焰先消散。
- 改善持續噴火音效：起始音只播放一次，持續燃燒段平順循環，停止射擊時短暫淡出。
- 補上電弧武器射擊音效，優化地形碰撞與自動索敵，調整核心獎勵畫面動畫。
- 改善敵人與 Boss 的霜凍表面效果，並同步更新英文介面、卡牌說明與中英文圖鑑。

### English

- Added an opt-in experimental events toggle on the title screen, disabled by default. Observation System Error gives a warning before caution tape obscures parts of the view, with dedicated event audio and music. Event progress freezes while paused.
- Updated event music: danger music continues during upgrade selection and fades back to the regular soundtrack after the event.
- Multi-boss encounters now prefer types not already present, reducing duplicate bosses.
- Updated Titan Treads: sustained boost starts with a stationary 0.8-second charge that consumes no EN, and boost turning speed is reduced by 30%. Each rank has its own top speed and acceleration time.
- Nano Repair now provides additional armor regeneration of rank × 0.5 plus 1% of maximum armor per second, scaling with changes to maximum armor. Removed the instant 15 armor repair on pickup.
- Applied a teal color to all six defensive chassis cards across upgrade choices, the firing range, owned cards and codex pages. Locked cards remain gray.
- Made Rocket Jump and Mass Effect mutually exclusive, including when applying upgrades in the firing range.
- Updated Dragon's Breath to fire 80 flame particles every 0.60 seconds, each dealing 3 base damage. Leading flames travel farther and last longer, while flames near the ship disappear first.
- Improved sustained flamethrower audio: the ignition plays once, the burning section loops smoothly, and releasing fire produces a short fade-out.
- Added the Arc Emitter firing sound, optimized terrain collision and automatic targeting, and adjusted the core reward animation.
- Improved frost surface effects on enemies and bosses, and updated English interface text, card descriptions and both codex languages.

## Ver. 0.163

### 繁體中文

- 新增繁體中文／英文介面，涵蓋選單、卡牌、戰鬥提示與機體、敵人、升級圖鑑；記住語言選擇，切換時重新載入遊戲。
- 語言選單移至 SYSTEM ONLINE 與 ESC 按鈕之間，加入地球圖標，並調整窄螢幕顯示。
- 更新中英文圖鑑中守望者與巨獸的插圖，對應目前遊戲造型。
- 調整「饕餮利爪」破土效果：以持續加速模式鑽地時，破土消耗剩餘 EN 並造成等量範圍爆炸傷害；擊退改為短暫滑移，並新增破土音效。
- 玩家包附上英文操作說明與英文圖鑑；中英文更新紀錄整併為同一份文件。

### English

- Added Traditional Chinese and English interfaces for menus, cards, combat messages, and ship, enemy and upgrade codex pages. Language selection is remembered; switching languages reloads the game.
- Moved the language selector between SYSTEM ONLINE and ESC, added a globe icon, and adjusted its layout for narrow screens.
- Updated the Watcher and Behemoth portraits in both codex languages to match their current in-game designs.
- Updated Ravenous Claws emergence: in sustained boost mode, emerging consumes remaining EN and deals that amount as area explosion damage. Knockback now slides enemies briefly, and emergence has a new sound effect.
- Included English instructions and codex pages in the player package, and combined both languages into one changelog.

## Ver. 0.162

### 繁體中文

- 新增大砲升級「火箭跳」：爆炸能更強力地推動機體，但也會造成少量自傷。
- 強化巨獸核心「破軍巨足」：提高加速極速與撞擊威力，衝刺結束時會產生衝擊波。
- 蜂鳥的基礎 EN 提升至 150；EN 耗盡後，須短暫等待才會開始回復。
- 「Tr1GGEr」現在可按住右鍵，讓新射出的砲彈立即引爆。

### English

- Added Rocket Jump for the Heavy Cannon: stronger blast propulsion at the cost of some self-damage.
- Buffed Titan Treads with higher boost speed, stronger ramming and a shockwave at the end of each dash.
- Increased Hummingbird's base EN to 150. Fully depleted EN now has a short delay before regeneration starts.
- Hold the right mouse button with Tr1GGEr to detonate newly fired shells immediately.

## Ver. 0.161

### 繁體中文

- 遊戲由《NEON RIFT》更名為《Tehom Diver》。
- 新增 Boss「巨噬蠕蟲」：會鑽地追擊、連續破土，並使用酸液與身體甩擊攻擊。
- 新增核心「饕餮利爪」：讓機體鑽地避開傷害，破土時擊退周圍敵人。
- 調整機體特性：壁壘的碰撞傷害提高 30%；蜂鳥加速時射速提高 25%。
- 噴火器升級「聚束噴口」改為「龍息」：按住攻擊可週期性噴出向前展開的密集火焰束，並加入專屬音效。

### English

- Renamed NEON RIFT to Tehom Diver.
- Added the Devourer Worm boss, featuring burrowing strikes, acid spit and body sweeps.
- Added Ravenous Claws: burrow to avoid damage, then knock back enemies on emergence.
- Updated ship traits: Bulwark gains 30% ramming damage; Hummingbird gains 25% fire rate while boosting.
- Replaced the Flamethrower's Focused Nozzle with Dragon's Breath: hold fire to launch dense flame volleys with a dedicated firing sound.
