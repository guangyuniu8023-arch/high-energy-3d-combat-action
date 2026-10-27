# 参考帧职责与映射

## 使用原则

这 14 张 JPG 是用户提供的高能 3D 双人战斗参考帧，只校准可观察的材质、轮廓、动作、特效、构图和镜头语法。

- 用户本轮上传素材始终是身份、人数、脸、服装、武器、姿势含义、构图和场景布局的最高视觉锚点。
- 内置帧不是固定角色或场景要求；不得用它们覆盖上游角色、颜色、武器或关系。
- 每次按任务选择 2–4 张最相关帧，不要把 14 张全部传给生成工具。
- 若工具不能同时接收用户附件与内置帧，优先用户附件；先观察内置帧，再把动作或视觉规则写入提示词。

## 通用别名与稳定文件名映射

| 稳定文件 | 通用别名 | 主要职责 | 可观察贡献 |
|---|---|---|---|
| `../assets/reference-01.jpg` | `close-range-energy-parry` | motion / composition | 近距离防御、武器前景、放射能量背景与招架接触关系 |
| `../assets/reference-02.jpg` | `restrained-blade-fighter` | style / character | 直立克制姿态、深色高领服装材质、侧脸微表演、冷环境光 |
| `../assets/reference-03.jpg` | `weighted-blade-fighter` | style / character | 松弛而有重量的成年战斗者、旧化皮革、宽幅武器与近景脸部质感 |
| `../assets/reference-04.jpg` | `close-blade-combo` | motion / effects | 贴身连续斩击、身体交错、刀光沿真实武器路径产生 |
| `../assets/reference-05.jpg` | `dual-enhanced-standoff` | character / transformation | 基础身份向两套强化轮廓升级、同场双人空间可读性 |
| `../assets/reference-06.jpg` | `final-energy-collision` | motion / effects | 终结碰撞、中央亮核、两侧轮廓、外扩尘雾与碎片 |
| `../assets/reference-07.jpg` | `first-energy-clash` | motion / effects | 刀光、接触闪光、粒子与短促色差集中在命中点 |
| `../assets/reference-08.jpg` | `knockdown-closeup` | composition / reaction | 受创贴地近景、武器前景、微表演与电影化插入方式 |
| `../assets/reference-09.jpg` | `low-angle-result-pose` | composition / character | 低机位近景、武器前景、动作完成姿态与场地纵深 |
| `../assets/reference-10.jpg` | `opposed-final-charge` | motion / composition | 双方从场地两侧相向冲锋、低位近对称构图与明确攻击线 |
| `../assets/reference-11.jpg` | `organic-crystal-battleground` | scene / composition | 第三人称过肩、双人距离、中央净空、强阴影分区与可破坏地面 |
| `../assets/reference-12.jpg` | `enhanced-aerial-attack` | motion / transformation | 强化形态空中进攻、翼状轮廓、对手防守与垂直空间 |
| `../assets/reference-13.jpg` | `teleport-impact` | motion / effects | 高速接近后的命中闪光、碎屑、身体遮挡与接位结果 |
| `../assets/reference-14.jpg` | `blade-vortex-clash` | motion / effects | 环形刀光、双向攻防、受控运动模糊与中心接触点 |

通用别名只用于检索职责，Skill 内实际素材路径均为 JPG。

## 按任务选择

- **角色与材质**：选 `reference-02.jpg` 或 `reference-03.jpg`；涉及形态升级再补 `reference-05.jpg`。只借鉴材质层级、姿态性格和轮廓变化，不复制脸、服装、颜色或武器。
- **场景与战斗空间**：选 `reference-11.jpg`；只借鉴战斗净空、主体分离、过肩空间关系和可破坏表面，按用户的原创世界观重做建筑与材料。
- **招架或接触**：选 `reference-01.jpg` 或 `reference-07.jpg`，校准来袭方向、接触点、短暂亮核和双方姿态。
- **近身连招**：选 `reference-04.jpg` 或 `reference-14.jpg`，校准身体交错、轨迹与可控特效层级。
- **瞬移接位**：选 `reference-13.jpg`，只迁移起点—方向—抵达—后续动作的因果。
- **空中段或升级**：选 `reference-12.jpg`，必要时补 `reference-05.jpg`。
- **终结对撞**：先选 `reference-10.jpg` 观察蓄势和攻击线，再选 `reference-06.jpg` 观察主碰撞与余波。
- **受创或结果姿态**：选 `reference-08.jpg` 或 `reference-09.jpg`，用于关键电影化插入，不扩张为全程镜头规则。

## 参考观察边界

以下只属于帧内偶发内容：具体人物外貌、对比发色、对立能量、长外套、不同剑型、有机晶体空间、翼状强化轮廓和单帧机位。它们可说明“角色差异化”“场景大形”“升级轮廓”等职责，但不能成为生成时的固定内容。所有角色和世界观元素依据上游输入重新设计。
