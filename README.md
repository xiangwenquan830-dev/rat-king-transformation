# Rat King Transformation | 鼠王变身

An unofficial Minecraft transformation mod based on **the Rat King character from Deadlock**. This fan project is not affiliated with or endorsed by Valve. Created with AI assistance.

**Minecraft 1.20.1 · Forge 47.4.10+ · Java 17 · test36 Beta**

## What it does

- Transform into a fully animated Rat King with a crown, necklace, shoulder decorations, feather collar, cape and articulated tail.
- Small rat helpers dress the character during transformation and return to replace damaged clothing.
- Quadruped sprinting and a speed-based pounce with collision damage.
- Clothing becomes battle-damaged below 30% health. After recovery and a safe waiting period, helpers repair it while you retain movement and combat control.
- Dedicated poses for movement, attacks, blocking, held items and optional gun/claw integrations.
- Armor already worn contributes attributes during transformation; armor functions are disabled and its appearance is hidden. Permanent health growth is retained on the human baseline.

## Controls

- **G**: transform / revert.
- **Left Shift**: quadruped sprint while moving forward.
- **Configured Jump key** while quadruped sprinting: pounce.
- Change bindings under **Options → Controls → Rat King** when another mod uses the same keys.

Start transformation while standing on supported ground, outside water and off vehicles. Rat form cannot ride vehicles.

## Installation and optional integrations

Install Forge for Minecraft 1.20.1, then put `ratking-0.1.0-test36.jar` in `mods`. Install the matching version on both client and server. Remove older Rat King jars before updating; back up worlds first. Source archives do not belong in `mods`.

Rat King can be installed independently. The following are **optional**, not bundled:

- [Wolverine: Claws & Healing](https://www.curseforge.com/minecraft/mc-mods/wolverine-claws-healing): steel claws, climbing and related combat integrations. test36 adds visual support for r74-beta corner turns. Install Wolverine separately to use these abilities.
- TACZ: gun holding and first-person arms.
- ParCool: Rat King controls its own movement while transformed; normal human movement remains with the original system.

Compatibility depends on versions and gun packs. This beta does not claim compatibility with every mod combination.

## test36 and validation

test36 adds smooth body/hand transitions during Wolverine r74 wall-corner turns, first-person turning alignment and fallback for older optional APIs. The model, textures and animation resources are unchanged from the reviewed test35 optimization build.

Before this publication, test36 was rebuilt offline and all **107 class files** matched the supplied release jar byte-for-byte. Its jar structure, version and SHA-256 were checked. The earlier test35 optimization passed 72 GameTests plus drawing and climbing comparisons; those historical results are **not** a full test36 gameplay or multiplayer certification. Long-running multiplayer and all optional combinations still need testing.

Report problems through this repository's Issues or CurseForge comments. Include the exact versions, reproduction steps and relevant crash report; remove credentials and personal details from logs before posting.

## 中文介绍

这是基于 **《Deadlock》中的鼠王角色**制作的非官方 Minecraft 模组，与 Valve 无官方关联或背书。本项目由 AI 辅助制作。

玩家可以变成鼠王，拥有完整的身体、尾巴、披风与服饰动画；小老鼠会帮助穿戴皇冠、项链和披风。支持四足冲刺、按移动速度决定距离的飞扑，以及低血量战损服装与回血后的助手换装。换装期间保留玩家移动和战斗操作。

默认 **G 变身/解除变身，左 Shift 四足冲刺，冲刺时按跳跃键飞扑**。变身需要站在有支撑的地面，不能处于水中或载具上；鼠王形态不能乘坐载具。按键冲突可在游戏控制设置里修改。

金刚狼、TACZ 和 ParCool 均为可选联动；钢爪和钢爪攀爬能力需要另外安装金刚狼。本版为 test36 测试版，新增金刚狼 r74 绕角时的身体、手臂和第一人称显示适配。

## Source and rights

The release includes a source archive with Java code, model/texture resources and build scripts. Third-party dependency jars, game installations, worlds and private development logs are excluded. See `BUILDING.txt` in the archive for dependency setup. GitHub's automatically generated source archive only contains files committed to this repository.

All Rights Reserved for this project's original contributions. Deadlock, its character concepts and related marks belong to their respective owners. Third-party notices remain applicable to their respective components. Source availability is not a grant of an open-source license.
