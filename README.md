# Persona Roundtable · 朋友圈顾问团

> 42 位公众人物蒸馏成五层人格库，按三角路由（最懂 + 反对 + 跨界）自动选 3 人发言。
> 对标 [nuwa-skill](https://github.com/alchaincyf/nuwa-skill)，全部 A 级（≥85 分）。

## 这是什么

你提一个问题，它不是自己回答，而是**从 42 个虚拟朋友里选 3 个最合适的，让他们用自己的口吻发言**：

- **最懂**：这个领域最有发言权的人
- **反对者**：立场相反、敢唱反调的人
- **跨界**：从完全不同领域给启发的人

每人不超过 3 句，像真的在群里聊天。

## 56 人顾问团

| 领域 | 人数 | 代表 |
|---|---|---|
| 投资创业技术 | 7 | 李笑来、马云、王石、Jack Dorsey、李想、杨植麟、影视飓风 TIM |
| 内容创作 | 10 | 韩寒、李健、松浦弥太郎、董宇辉、余华、李叔同、费勇、梁冬、刘震云、坂本龙一 |
| 哲学思想 | 8 | 尼采、王阳明、梁启超、曾国藩、苏轼、庄子、李白、林光华 |
| 体育 | 5 | Messi、欧文、武磊、苏炳添、库里 |
| 娱乐 | 6 | 王一博、易烊千玺、古天乐、王嘉尔、Harry Styles、刘耀文 |
| 健康跨界 | 6 | 陶勇、王昱珩、宫本茂、冯时、Dan Koe、董路 |
| **本地合计** | **42** | |
| 官方复用 | 4 | Elon Musk、乔布斯、纳瓦尔、张雪峰 |
| 同组参考 | 10 | 时代少年团其他 6 人、one direction 其他 4 人 |

## 五层蒸馏法

每个人格文件按五层结构：

1. **表达 DNA**：语气、节奏、用词偏好、典型句式
2. **心智模型**：他看世界的核心模型（三重验证：跨域出现 / 有预测力 / 有排他性）
3. **决策启发式**：遇到问题他会问自己哪几个问题
4. **反模式**：他明确不做的事
5. **诚实边界**：他的局限、矛盾、人设包装

## 安装

把整个目录放到豆包 skill 目录：

```bash
git clone https://github.com/IYABAO/persona-roundtable.git
# 放到 .user_skills/persona-roundtable/
```

## 触发方式

- "帮我问问大家"
- "多几个角度看看"
- "找几个人聊聊"
- "开个圆桌会"
- "叫上 XX"
- "加个朋友"

## 项目结构

```
persona-roundtable/
├── SKILL.md               # 运行时指令
├── README.md              # 本文件
├── CONTRIBUTING.md        # 怎么加新人
├── CHANGELOG.md           # 版本历史
├── LICENSE                # MIT
├── references/
│   ├── persona-template.md # 五层蒸馏模板
│   └── FIDELITY.md         # 保真度评分卡
├── examples/
│   └── roundtable-samples.md  # 输出示例
└── members/
    ├── INDEX.md           # 56人索引
    ├── _gap-log.template.md    # 缺口记录模板
    ├── _voting-log.template.md # 投票记录模板
    └── *.md               # 42份人格文件
```

## 评分

按 5 维度打分（满分 100）：

| 维度 | 权重 |
|---|---|
| 立场一致性 | 25 |
| 风格辨识度 | 25 |
| 边缘诚实度 | 20 |
| 来源透明度 | 15 |
| 结构完整度 | 15 |

全部 42 人 A 级（≥85），加权平均约 86.8 分。详见 [references/FIDELITY.md](references/FIDELITY.md)。

## 贡献

想加新朋友？看 [CONTRIBUTING.md](CONTRIBUTING.md)。

## License

MIT
