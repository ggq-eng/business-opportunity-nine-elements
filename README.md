# business-opportunity-nine-elements

> 来源分类：**待确认** ｜ 导出批次：review

商机九要素企业调研与Excel生成技能。当用户提供一批企业名单（Excel、截图、文本均可）并要求输出「商机九要素」（对接角色/合作主体/客户业务/目标场景/采购时间/项目进度/竞品/预算/使用AI经验）时使用。适用于销售售前、To B 商机梳理、客户画像分析场景。核心流程：逐一检索企业公开信息（工商/官网/年报/新闻）→ 区分「已核验事实」与「销售侧推断（标注待确认）」→ 用 openpyxl 生成两表结构 Excel（商机九要素 + 填表说明与数据来源）。

## 安装

把本文件夹整体复制到 WorkBuddy 技能目录：

```bash
cp -r . ~/.workbuddy/skills/business-opportunity-nine-elements        # 用户级
# 或
cp -r . <项目>/.workbuddy/skills/business-opportunity-nine-elements   # 项目级
```

重启/刷新 WorkBuddy 后即可在对话中触发。

## 说明

- 本技能从本地 WorkBuddy 环境导出，**所有真实密钥已脱敏为占位符**，使用前请配置你自己的 API Key。
- 若来自技能市场（文件夹名以 `__skillhub` 结尾），版权归原作者，请遵守其许可证。
