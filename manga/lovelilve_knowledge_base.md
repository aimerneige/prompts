# [AI 视觉生成强制约束与特征校对字典]
# 警告：此部分为客观事实数据，AI 在解析分镜脚本时必须严格对照此字典，覆盖模型内部的模糊记忆。

## 1. 常见视觉解析错误规避 (Anti-Literal Interpretation Guide)
当分镜脚本中出现以下修辞手法时，**严禁**在画面中生成对应的实体元素：
- 比喻动作："像猫一样"、"猫咪般的撒娇" -> 只能表现为：双手握拳放在胸前的姿势、俏皮的表情。**绝对禁止：**生成真实的猫耳、猫尾巴、猫爪子。
- 夸张情绪："气得冒烟" -> 只能表现为：角色鼓起腮帮子、皱眉的愤怒表情。**绝对禁止：**生成真实的烟雾特效。
- 抽象形容："闪闪发光" -> 只能表现为：明亮的眼神、灿烂的笑容、或者适当的打光。**绝对禁止：**在角色脸上或周围强行贴上星星贴图。

## 2. 《LoveLive!》一代团 (μ's / 音乃木坂学院) 角色特征数据库
* 【通用制服约束】：深蓝色西服外套、白色衬衫、格子裙。**严禁**画错领结颜色，领结颜色是判断年级的唯一标准。
* 【角色独立特征】：
  - 一年级 (领结颜色：蓝色 Blue Ribbon)：
    * 西木野真姬 (Maki Nishikino) -> 瞳孔：紫色 (Purple/Violet eyes)
    * 星空凛 (Rin Hoshizora) -> 瞳孔：金黄色 (Gold/Yellow eyes)
    * 小泉花阳 (Hanayo Koizumi) -> 瞳孔：紫红色 (Magenta/Purple eyes)
  - 二年级 (领结颜色：红色 Red Ribbon)：
    * 高坂穗乃果 (Honoka Kosaka) -> 瞳孔：蓝色 (Blue eyes)
    * 南琴梨 (Kotori Minami) -> 瞳孔：琥珀色/金色 (Amber/Gold eyes)
    * 园田海未 (Umi Sonoda) -> 瞳孔：琥珀色/棕色 (Amber/Brown eyes)
  - 三年级 (领结颜色：绿色 Green Ribbon)：
    * 绚濑绘里 (Eli Ayase) -> 瞳孔：蓝色 (Blue eyes)
    * 东条希 (Nozomi Tojo) -> 瞳孔：蓝绿色 (Turquoise/Green eyes)
    * 矢泽妮可 (Nico Yazawa) -> 瞳孔：红色 (Red eyes)

## 3. 《LoveLive! Sunshine!!》二代团 (Aqours / 浦之星女学院) 角色特征数据库
* 【通用制服约束】：水手服，灰色系裙子。**严禁**画错水手服领带颜色，领带颜色是判断年级的唯一标准。
* 【角色独立特征】：
  - 一年级 (领带颜色：黄色 Yellow Tie)：
    * 津岛善子 (Yoshiko Tsushima) -> 瞳孔：粉红色/紫红色 (Pink/Magenta eyes)
    * 国木田花丸 (Hanamaru Kunikida) -> 瞳孔：金黄色 (Gold/Yellow eyes)
    * 黑泽露比 (Ruby Kurosawa) -> 瞳孔：青绿色 (Teal/Turquoise eyes)
  - 二年级 (领带颜色：红色 Red Tie)：
    * 高海千歌 (Chika Takami) -> 瞳孔：红色 (Red eyes)
    * 樱内梨子 (Riko Sakurauchi) -> 瞳孔：金黄色 (Gold/Yellow eyes)
    * 渡边曜 (You Watanabe) -> 瞳孔：蓝色 (Blue eyes)
  - 三年级 (领带颜色：绿色 Green Tie)：
    * 松浦果南 (Kanan Matsuura) -> 瞳孔：紫色 (Purple eyes)
    * 黑泽黛雅 (Dia Kurosawa) -> 瞳孔：青绿色 (Teal/Turquoise eyes)
    * 小原鞠莉 (Mari Ohara) -> 瞳孔：金黄色 (Gold/Yellow eyes)

## 4. AI 易错负面清单 (Negative Prompts Core)
在生成任何图像前，系统应隐式附加以下负面特征限制，防止 AI 自我发挥：
- 错误制服穿搭 (wrong uniform, mismatched ribbon/tie color)
- 异色瞳 (heterochromia - 除非设定允许)
- 动物拟人化部件 (animal ears, animal tails, real cat paws)
- 不一致的眼神高光 (inconsistent eye highlights)
