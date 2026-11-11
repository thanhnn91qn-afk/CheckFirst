# CheckFirst

An agent skill with one rule: **before building anything new, check whether a well-rated one already exists.**

When an agent is asked to create a skill, MCP server, script, CLI, library, or integration, `check-first` makes it:

1. Look at what is already installed
2. Search the right registries (3 to 6 queries, then stop)
3. Qualify candidates on fit, activity, trust, license, and safety
4. Report what it found and recommend **use / adapt / reference / build**

The result: fewer wasted tokens, fewer half-finished clones of tools that already exist.

## Install

Copy the `check-first` folder into your agent's skills directory.

Claude Code:

```bash
git clone https://github.com/thanhnn91qn-afk/CheckFirst.git
cp -r CheckFirst/check-first ~/.claude/skills/
```

It is a plain `SKILL.md` with standard frontmatter, so it works with any agent that supports the Agent Skills format.

## Tiếng Việt

Skill cho agent với nguyên tắc: **nhận yêu cầu làm cái gì mới thì tìm trước xem đã có skill, MCP hay công cụ tương tự được đánh giá cao chưa.** Có thì dùng luôn hoặc tham khảo, không có mới tự làm. Mục tiêu là đỡ tốn token và thời gian.

## License

MIT
