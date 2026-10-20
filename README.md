# Motion Patterns

面向 Agent 的平台无关页面转场动效 Skill，涵盖：

- 页面关系与转场模式判断
- 进入、退出、返回和中断行为
- 模态覆盖、共享元素与容器变换
- 手势驱动和可中断转场
- 时长、缓动、时间轴与 reduced motion
- 按当前项目技术栈实现与验证

## 安装

将本仓库克隆到 Cursor 的个人 Skills 目录：

```bash
git clone https://github.com/FFFOOOGGG/motion-patterns.git ~/.cursor/skills/motion-patterns
```

也可以把 `SKILL.md` 放到项目内的 `.cursor/skills/motion-patterns/`。

## 使用

在 Cursor 中提出页面切换、路由跳转、共享元素、手势返回或转场评审需求时使用此 Skill。Agent 会先判断产品语义和页面关系，再结合当前项目的实际技术栈给出规格或实现。

## 说明

此 Skill 不绑定 React、JavaScript、CSS 或特定动画库。只有在用户要求实现时，Agent 才会检查代码库并使用项目现有语言、框架、组件和动效能力。
