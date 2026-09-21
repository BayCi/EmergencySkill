# EmergencySkill — 安全生产法知识技能

Agent skill generated from 《中华人民共和国安全生产法（2021年修订版）》 with [book-to-skill](https://github.com/virgiliojr94/book-to-skill).

本技能将《安全生产法》（2021年第三次修正，119条/7章）提炼为结构化、可重复调用的知识库：核心框架、逐章深度总结、术语表、制度模式与速查表，适用于安全生产合规审查、企业主体责任核查、事故责任与罚款计算、监管执法权限查询、从业人员权利义务咨询等场景。

## Install

在任何 Agent Skills 主机上安装：

```bash
npx skills add https://github.com/BayCi/EmergencySkill --skill safety-production-law-2021
```

或手动安装：将 `safety-production-law-2021/` 目录放入技能的 skills 根目录（如 `~/.agents/skills/`、`~/.claude/skills/` 或 `~/.doubao/agent_mode/workspace/.user_skills/`）。

## Usage

- 问「safety-production-law-2021」→ 加载核心框架
- 问「双重预防机制」「安责险」「第97条」→ 定位对应章节或条文
- 问「ch05」→ 深入事故应急与调查处理一章

## File Inventory

```
SKILL.md                    核心框架（14个）+ 章节/主题双索引
chapters/ch01-general-provisions.md   总则（第1-19条）
chapters/ch02-enterprise-obligations.md  生产经营单位的安全生产保障（第20-51条）
chapters/ch03-worker-rights.md   从业人员的安全生产权利义务（第52-61条）
chapters/ch04-supervision.md     安全生产的监督管理（第62-78条）
chapters/ch05-emergency-response.md  事故应急救援与调查处理（第79-89条）
chapters/ch06-legal-liability.md 法律责任（第90-116条）
chapters/ch07-supplementary.md   附则（第117-119条）
glossary.md                  术语表（约60个术语）
patterns.md                  制度模式与操作清单（12个）
cheatsheet.md                速查表（罚款分级、机构配置、时限、条款定位）
```

## License & Copyright Note

内容为对《中华人民共和国安全生产法（2021年修订版）》（全国人大常委会公布的公开官方立法文件）的结构化合成摘要，非原文拷贝。法律、法规等官方文件依《中华人民共和国著作权法》第五条不适用著作权法保护。
