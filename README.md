# Tripo + Blender IP 精修 Skill

一套面向 **IP 角色、潮玩与吉祥物** 的 3D 静帧制作工作流：从角色参考图或已有模型出发，用 Tripo 建立基础模型与贴图，再用 Blender 完善造型、材质、灯光和细节，整理成片、可编辑工程与贴图交付。

既适合开始一个新角色，也适合接着已有工程继续精修。每个 IP 都以自己的设计特征为准，重新判断制作重点。

[了解能力](#能力与交付) · [安装 Skill](#安装) · [开始使用](#使用) · [查看 IP 作品](#ip-作品展示)

## 能力与交付

| 环节 | Skill 帮你完成什么 |
| --- | --- |
| 参考分析与分工 | 拆解轮廓、姿态、表情和标志配件，明确 Tripo 基础与 Blender 精修各自负责的部分 |
| 基础模型与贴图 | 优先复用已有模型；需要新生成时，规划 Tripo 任务、核对预算并记录结果 |
| Blender 精修 | 检查局部结构，完善金属、皮肤、布料、毛绒等材质，调整构图、灯光与色彩 |
| 静帧与工程交付 | 按目标尺寸渲染、检查画面与资源打包，整理静帧、可编辑 `.blend` 和贴图 |
| 可选镜头建议 | 根据当前 IP 的展示重点，提供 15 秒展示片的镜头节奏与运镜建议 |

默认以高质量静帧为目标，支持长边 4096 像素的 4K 输出，实际尺寸按构图和需求确定。动画、游戏资产或 3D 打印需要另行定义拓扑、绑定或实体要求。

## 工作流程

1. **看参考、定目标**：确认角色特征、主视角、输出尺寸与验收重点。
2. **生成或复用底模**：优先使用已有模型，需要时再调用 Tripo。
3. **在 Blender 中精修**：先锁定构图，再处理影响画面的结构、材质与细节。
4. **预览与验收**：先低分辨率检查，再按目标尺寸渲染，核对脸、手、边缘与材质交界。
5. **整理交付**：提供成片、工程和贴图，说明实际修改、费用与仍存在的偏差。

## 安装

将下面这段话发给 Codex：

```text
请帮我安装这个 Skill：
https://github.com/huangxin-design/tripo-blender-ip
将仓库里的完整 tripo-blender-ip 文件夹安装到本机可识别的个人 Skill 目录，保留 agents 和 references。
如果已有同名版本，先比较并保留我的自定义修改；完成后验证文件和引用完整，并告诉我安装位置。
这次只安装 Skill，不调用 Tripo、不开始建模或渲染。
```

## 使用

- 制作静帧：`使用 $tripo-blender-ip，把这张角色参考图做成高质量 3D 静帧，先拆分 Tripo 与 Blender 的工作。`
- 继续精修：`按上次 IP 流程继续这个工程，改善金属和毛发细节。`
- 只要镜头建议：`参考这个 IP，给我一套 15 秒展示片的镜头建议，先不要制作或渲染。`

**运行条件**：Tripo 调用需要对应插件或 CLI 与账号，Blender 精修与渲染需要本机可用环境。常规角色制作可自动选用此 Skill；自动识别不代表获得新的付费生成或视频制作授权。

**视频默认只提供建议。** 安装 Skill、完成静帧或阅读案例都不会自动开始视频制作、试渲染或后台任务；只有你明确要求制作或渲染视频时，才在授权范围内执行。

## 参考文档

- [技能入口](tripo-blender-ip/SKILL.md)
- [Tripo 执行与恢复](tripo-blender-ip/references/tripo-execution.md)
- [Blender 精修与验收](tripo-blender-ip/references/blender-finishing.md)
- [已认可的静帧案例](tripo-blender-ip/references/approved-case.md)
- [可选的 15 秒视频镜头建议](tripo-blender-ip/references/video-shot-suggestions.md)

安装目录 `tripo-blender-ip/` 保存 Skill 工作流文档；作品预览与制作说明放在 `examples/`，公开的 Blender 工程通过对应 Release 下载，不随 Skill 安装或自动执行。

## IP 作品展示

每个 IP 以独立案例记录成片、制作分工和交付资源。下方保留作品预览与入口，细节图、实际参数和工程下载说明集中在各自的案例页，便于持续收录新作品。

案例效果、生成费用与渲染速度来自对应角色和设备的实际记录，不代表其他 IP 的固定结果。

| 作品预览 | 项目与资源 |
| --- | --- |
| [<img src="examples/clockwork-angel/images/hero.png" width="260" alt="机械羽翼角色成片预览">](examples/clockwork-angel/README.md) | **机械羽翼角色**<br>Tripo 整体底模 · Blender 局部精修<br>金色发光光环、蓝色金属与毛绒纤维；包含全身、细节和真实白模预览。<br><br>[查看案例](examples/clockwork-angel/README.md) · [下载 Blender 工程](https://github.com/huangxin-design/tripo-blender-ip/releases/tag/clockwork-angel-case-v1) |

<!-- 新增作品：在 examples/<作品名>/ 中整理封面和 README.md，并在上表添加一行。沿用“封面 + 名称 + 制作重点 + 案例/资源入口”的格式，具体参数与下载说明写在案例页。 -->
