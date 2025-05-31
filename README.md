# 《程序员的三十六计》The-36-Stratagems-for-Programmers
![36_front_cover](https://github.com/user-attachments/assets/16c3af1f-e972-445e-a8d6-33015d458094)


## The 36 Stratagems for Programmers 《程序员的三十六计》

### 📝 Preface 前言

Programmers are not soldiers, yet we fight silent battles every day.
程序员不是士兵，却每日征战在看不见的战场。

From architectural debates to deployment pressure, from team politics to tech stack migration—these are all forms of modern-day warfare.
从架构博弈到部署压力，从团队协作到技术选型迁移，处处皆为战局。

This book is not meant to teach you to manipulate, but to help you see clearly, plan wisely, and act with intention.
本书并非教你“算计”，而是助你洞察大局、巧施谋略、智慧应对。

By combining ancient Eastern wisdom with modern programming, we offer 36 strategic mindsets for developers.
我们将东方兵法与现代开发实践结合，提炼出 36 计技术谋略，赋予开发者更多维度的思考力。

May this book become your strategic companion in code.
愿此书成为你代码世界中的谋略之友。

— Xing Wang & Allen Wang
—— 王星 / 王阳
Spring 2025 · 春·2025

---

### 👨‍💻 About the Authors 关于作者

### 👨‍💻 Xing Wang
<img src="https://github.com/user-attachments/assets/9575460d-ff93-4dd8-8816-b401ce3e4715" width="200" alt="Resized Xing Image">

**Xing Wang** is a senior software architect with over 15 years of experience in enterprise systems, microservice architecture, DevOps engineering, and applied AI.
**Xing Wang** 是一位拥有 15 年以上经验的资深软件架构师，专注于企业系统、微服务架构、DevOps 工程与人工智能应用。

As a strategic thinker, he is passionate about blending classical Chinese military wisdom with software design.
作为一位具备战略思维的工程师，他热衷于将中国古代兵法智慧融入现代软件设计。

He advocates for “strategic coding”—writing code not only for functionality, but for long-term maintainability, resilience, and influence.
他提出“战略性编码”理念，强调代码不仅要能运行，还应具备可维护性、韧性与技术影响力。

His writings combine technology, philosophy, and visual thinking to help engineers gain clarity in complexity.
他的写作融合技术、哲学与图形思维，致力于帮助开发者在复杂中洞察本质。


### 🤝 Allen Wang
<img src="https://github.com/user-attachments/assets/8b9e3d28-9ee4-4007-9fb8-89e07ad0232d" width="200" alt="Allen" />

**Allen Wang** is a senior software architect and full-stack developer with deep expertise in system observability, domain-driven design, and cross-team engineering workflows.
**Allen Wang** 是一位资深软件架构师与全栈开发者，专长于系统可观测性、领域建模以及跨团队协作流程设计。

He plays a vital role in transforming abstract ideas into tangible diagrams, stories, and architectural maps.
他擅长将抽象概念具象化，通过图表、类比与技术叙事形式，提升团队的技术共识与执行力。

He contributed to the structure, voice, and visual narrative of this book, refining both the English and Chinese versions.
他为本书中英双语内容的架构、语气与图示表达设计提供了关键支持。

Outside of coding, he is passionate about teaching, diagram-based learning, and building developer education tools.
在编码之外，他热衷于教学、图解学习法以及开发者学习体验工具的设计。

His philosophy: **“If it can’t be explained simply, it hasn’t been understood deeply.”**
他的理念是：“解释不清楚的东西，自己也没理解透。”

---


| No. | Stratagem Title (English)                                | 计名（中文） |
| --- | -------------------------------------------------------- | ------ |
| 01  | Deceive the Sky to Cross the Ocean                       | [瞒天过海](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E4%B8%80%E8%AE%A1%EF%BC%9A%E7%9E%92%E5%A4%A9%E8%BF%87%E6%B5%B7%20Deceive%20the%20Sky%20to%20Cross%20the%20Ocean.md)   |
| 02  | Surround Wei to Save Zhao                                | [围魏救赵](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E4%BA%8C%E8%AE%A1%EF%BC%9A%E5%9B%B4%E9%AD%8F%E6%95%91%E8%B5%B5%20Besiege%20Wei%20to%20Rescue%20Zhao.md)   |
| 03  | Kill with a Borrowed Knife                               | [借刀杀人](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E4%B8%89%E8%AE%A1%EF%BC%9A%E5%80%9F%E5%88%80%E6%9D%80%E4%BA%BA%20Kill%20with%20a%20Borrowed%20Knife.md)   |
| 04  | Wait at Leisure for the Exhausted Enemy                  | [以逸待劳](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E5%9B%9B%E8%AE%A1%EF%BC%9A%E4%BB%A5%E9%80%B8%E5%BE%85%E5%8A%B3%20Wait%20at%20Leisure%20for%20the%20Exhausted%20Enemy.md)   |
| 05  | Loot a Burning House                                     | [趁火打劫](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E4%BA%94%E8%AE%A1%EF%BC%9A%E8%B6%81%E7%81%AB%E6%89%93%E5%8A%AB%20Loot%20a%20Burning%20House.md)   |
| 06  | Make a Feint to the East While Attacking in the West     | [声东击西](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E5%85%AD%E8%AE%A1%EF%BC%9A%E5%A3%B0%E4%B8%9C%E5%87%BB%E8%A5%BF%20Make%20a%20Feint%20to%20the%20East%20While%20Attacking%20in%20the%20West.md)   |
| 07  | Create Something from Nothing                            | [无中生有](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E4%B8%83%E8%AE%A1%EF%BC%9A%E6%97%A0%E4%B8%AD%E7%94%9F%E6%9C%89%20Create%20Something%20from%20Nothing.md)   |
| 08  | Secretly Take the Route of Chencang                      | [暗渡陈仓](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E5%85%AB%E8%AE%A1%EF%BC%9A%E6%9A%97%E6%B8%A1%E9%99%88%E4%BB%93%20Secretly%20Take%20the%20Route%20of%20Chencang.md)   |
| 09  | Watch the Fire from the Other Side of the River          | [隔岸观火](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E4%B9%9D%E8%AE%A1%EF%BC%9A%E9%9A%94%E5%B2%B8%E8%A7%82%E7%81%AB%20Watch%20the%20Fire%20from%20the%20Other%20Side%20of%20the%20River.md)   |
| 10  | Hide a Dagger Behind a Smile                             | [笑里藏刀](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E5%8D%81%E8%AE%A1%EF%BC%9A%E7%AC%91%E9%87%8C%E8%97%8F%E5%88%80%20Hide%20a%20Dagger%20Behind%20a%20Smile.md)  |
| 11  | Sacrifice the Plum Tree to Save the Peach Tree           | [李代桃僵](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E5%8D%81%E4%B8%80%E8%AE%A1%EF%BC%9A%E6%9D%8E%E4%BB%A3%E6%A1%83%E5%83%B5%20Sacrifice%20the%20Plum%20Tree%20to%20Save%20the%20Peach%20Tree.md)   |
| 12  | Take the Opportunity to Steal a Goat                     | [顺手牵羊](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E5%8D%81%E4%BA%8C%E8%AE%A1%EF%BC%9A%E9%A1%BA%E6%89%8B%E7%89%B5%E7%BE%8A%20Take%20the%20Opportunity%20to%20Steal%20a%20Goat.md)   |
| 13  | Beat the Grass to Startle the Snake                      | [打草惊蛇](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E5%8D%81%E4%B8%89%E8%AE%A1%EF%BC%9A%E6%89%93%E8%8D%89%E6%83%8A%E8%9B%87%20Beat%20the%20Grass%20to%20Startle%20the%20Snake.md)   |
| 14  | Borrow a Corpse to Resurrect the Soul                    | [借尸还魂](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E5%8D%81%E5%9B%9B%E8%AE%A1%EF%BC%9A%E5%80%9F%E5%B0%B8%E8%BF%98%E9%AD%82%20Borrow%20a%20Corpse%20to%20Resurrect%20the%20Soul.md)   |
| 15  | Lure the Tiger out of the Mountain                       | [调虎离山](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E5%8D%81%E4%BA%94%E8%AE%A1%EF%BC%9A%E8%B0%83%E8%99%8E%E7%A6%BB%E5%B1%B1%20Lure%20the%20Tiger%20Out%20of%20the%20Mountain.md)   |
| 16  | Let the Enemy Tire Themselves Out                        | [欲擒故纵](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E5%8D%81%E5%85%AD%E8%AE%A1%EF%BC%9A%E6%AC%B2%E6%93%92%E6%95%85%E7%BA%B5%20Let%20the%20Enemy%20Go%20to%20Catch%20Them%20Later.md)   |
| 17  | Toss Out a Brick to Get a Jade                           | [抛砖引玉](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E5%8D%81%E4%B8%83%E8%AE%A1%EF%BC%9A%E6%8A%9B%E7%A0%96%E5%BC%95%E7%8E%89%20Toss%20Out%20a%20Brick%20to%20Attract%20Jade.md)   |
| 18  | Capture the Thief First to Capture the King              | [擒贼擒王](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E5%8D%81%E5%85%AB%E8%AE%A1%EF%BC%9A%E6%93%92%E8%B4%BC%E6%93%92%E7%8E%8B%20Capture%20the%20Thief%20First%20to%20Capture%20the%20King.md)   |
| 19  | Remove the Firewood from Under the Pot                   | [釜底抽薪](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E5%8D%81%E4%B9%9D%E8%AE%A1%EF%BC%9A%E9%87%9C%E5%BA%95%E6%8A%BD%E8%96%AA%20Remove%20the%20Firewood%20from%20Under%20the%20Pot.md)   |
| 20  | Fish in Troubled Waters                                  | [混水摸鱼](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E4%BA%8C%E5%8D%81%E8%AE%A1%EF%BC%9A%E6%B7%B7%E6%B0%B4%E6%91%B8%E9%B1%BC%20Fish%20in%20Troubled%20Waters.md)   |
| 21  | The Cicada Sheds Its Shell                               | [金蝉脱壳](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E4%BA%8C%E5%8D%81%E4%B8%80%E8%AE%A1%EF%BC%9A%E9%87%91%E8%9D%89%E8%84%B1%E5%A3%B3%20The%20Cicada%20Sheds%20Its%20Shell.md)   |
| 22  | Shut the Door and Catch the Thief                        | [关门捉贼](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E4%BA%8C%E5%8D%81%E4%BA%8C%E8%AE%A1%EF%BC%9A%E5%85%B3%E9%97%A8%E6%8D%89%E8%B4%BC%20Shut%20the%20Door%20and%20Catch%20the%20Thief.md)  |
| 23  | Befriend a Distant State While Attacking a Neighbor      | [远交近攻](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E4%BA%8C%E5%8D%81%E4%B8%89%E8%AE%A1%EF%BC%9A%E8%BF%9C%E4%BA%A4%E8%BF%91%E6%94%BB%20Befriend%20Distant%20States%20While%20Attacking%20Nearby%20Ones.md)   |
| 24  | Obtain Safe Passage to Conquer the Kingdom               | [假道伐虢](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E4%BA%8C%E5%8D%81%E5%9B%9B%E8%AE%A1%EF%BC%9A%E5%81%87%E9%81%93%E4%BC%90%E8%99%A2%20Obtain%20Safe%20Passage%20to%20Conquer%20the%20Kingdom.md)   |
| 25  | Replace the Beams with Rotten Timbers                    | [偷梁换柱](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E4%BA%8C%E5%8D%81%E4%BA%94%E8%AE%A1%EF%BC%9A%E5%81%B7%E6%A2%81%E6%8D%A2%E6%9F%B1%20Replace%20the%20Beams%20with%20Rotten%20Timbers.md)   |
| 26  | Point at the Mulberry Tree While Cursing the Locust Tree | [指桑骂槐](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E4%BA%8C%E5%8D%81%E5%85%AD%E8%AE%A1%EF%BC%9A%E6%8C%87%E6%A1%91%E9%AA%82%E6%A7%90%20Point%20at%20the%20Mulberry%20Tree%20While%20Cursing%20the%20Locust%20Tree.md)   |
| 27  | Feign Madness But Keep Your Balance                      | [假痴不癫](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E4%BA%8C%E5%8D%81%E4%B8%83%E8%AE%A1%EF%BC%9A%E5%81%87%E7%97%B4%E4%B8%8D%E7%99%AB%20Feign%20Madness%20But%20Keep%20Your%20Balance.md)   |
| 28  | Remove the Ladder When the Enemy Has Ascended            | [上屋抽梯](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E4%BA%8C%E5%8D%81%E5%85%AB%E8%AE%A1%EF%BC%9A%E4%B8%8A%E5%B1%8B%E6%8A%BD%E6%A2%AF%20Remove%20the%20Ladder%20When%20the%20Enemy%20Has%20Ascended.md)   |
| 29  | Decorate the Tree with Fake Blossoms                     | [树上开花](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E4%BA%8C%E5%8D%81%E4%B9%9D%E8%AE%A1%EF%BC%9A%E6%A0%91%E4%B8%8A%E5%BC%80%E8%8A%B1%20Decorate%20the%20Tree%20with%20Fake%20Blossoms.md)   |
| 30  | Turn the Guest into the Host                             | [反客为主](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E4%B8%89%E5%8D%81%E8%AE%A1%EF%BC%9A%E5%8F%8D%E5%AE%A2%E4%B8%BA%E4%B8%BB%20Turn%20the%20Guest%20into%20the%20Host.md)   |
| 31  | Use a Beauty Trap                                        | [美人计](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E4%B8%89%E5%8D%81%E4%B8%80%E8%AE%A1%EF%BC%9A%E7%BE%8E%E4%BA%BA%E8%AE%A1%20Use%20a%20Beauty%20Trap.md)    |
| 32  | Use an Empty City Stratagem                              | [空城计](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E4%B8%89%E5%8D%81%E4%BA%8C%E8%AE%A1%EF%BC%9A%E7%A9%BA%E5%9F%8E%E8%AE%A1%20Use%20an%20Empty%20City%20Stratagem.md)    |
| 33  | Let the Enemy's Spies Sow Discord                        | [反间计](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E4%B8%89%E5%8D%81%E4%B8%89%E8%AE%A1%EF%BC%9A%E5%8F%8D%E9%97%B4%E8%AE%A1%20Let%20the%20Enemy's%20Spies%20Sow%20Discord.md)    |
| 34  | Inflict Injury on Yourself to Gain Trust                 | [苦肉计](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E4%B8%89%E5%8D%81%E5%9B%9B%E8%AE%A1%EF%BC%9A%E8%8B%A6%E8%82%89%E8%AE%A1%20Inflict%20Injury%20on%20Yourself%20to%20Gain%20Trust.md)    |
| 35  | Chain Stratagems                                         | [连环计](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E4%B8%89%E5%8D%81%E4%BA%94%E8%AE%A1%EF%BC%9A%E8%BF%9E%E7%8E%AF%E8%AE%A1%20Chain%20Stratagems.md)    |
| 36  | If All Else Fails, Retreat                               | [走为上计](https://github.com/uwspstar/The-36-Stratagems-for-Programmers/blob/main/%E7%AC%AC%E4%B8%89%E5%8D%81%E5%85%AD%E8%AE%A1%EF%BC%9A%E8%B5%B0%E4%B8%BA%E4%B8%8A%E8%AE%A1%20Retreat%20Is%20the%20Best%20Option.md)   |

---

### 📚 Chapter Structure 正文结构

Each stratagem includes: 每一计均包含：

* Original Explanation 原文解读
* Programmer's Interpretation 程序员翻译
* Practical Scenarios 应用场景
* C# Sample Code 示例代码
* Mermaid Flow Diagram Mermaid 流程图
* Tactical Maxim 战略格言（中英）

---

### 📎 Appendix 附录结构

**A. Strategy Index / 策略索引**
Map real-world dev problems to stratagems 将开发难题与三十六计对应映射

**B. Diagram Atlas / 图表总览**
All Mermaid charts in one place 集中展示所有 Mermaid 图

**C. Strategic Thinking Models / 策略思维模型**
From code to architecture to organization 从代码到架构到组织的策略思考路径

**D. Recommended Reading / 推荐阅读**
Eastern classics + developer books 东方典籍与程序员经典书籍推荐

**E. Contact & Updates / 联系作者 & 获取更新**
GitHub, website, QR pages GitHub、官网、扫码页

![36back_cover](https://github.com/user-attachments/assets/a0ba4c38-a977-4f85-8ade-5f3cd3001588)

