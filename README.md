# Tripo + Blender IP 精修

把角色参考图拆成 Tripo 建模与 Blender 精修任务，逐步完善造型、材质、灯光与细节，交付高质量 3D 静帧、可编辑工程和贴图。

**视频部分只提供建议，不会因为安装或自动触发这个 Skill 就开始制作、试渲染或启动后台任务。** 只有你明确要求制作或渲染视频时，才在授权范围内执行。

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

常规角色制作可自动选用此 Skill；自动识别不代表获得新的付费生成或视频制作授权。Tripo 调用仍需对应插件/CLI 与账号，Blender 渲染需本机可用环境。

## 内容

- [技能入口](tripo-blender-ip/SKILL.md)
- [Tripo 执行与恢复](tripo-blender-ip/references/tripo-execution.md)
- [Blender 精修与验收](tripo-blender-ip/references/blender-finishing.md)
- [已认可的静帧案例](tripo-blender-ip/references/approved-case.md)
- [可选的 15 秒视频镜头建议](tripo-blender-ip/references/video-shot-suggestions.md)

视频参考包括全身、标志配件、金属、鞋子、羽毛和白模的镜头节奏，以及单向运镜和原生 4K 的规格建议。没有对应部件的角色应重新选择展示重点，不照搬光环或羽毛。

案例记录属于特定角色和设备的已验证结果，不保证其他角色的还原程度、生成费用或渲染速度。仓库发布 Skill 文档，不包含模型、贴图、视频或自动执行渲染的脚本。
