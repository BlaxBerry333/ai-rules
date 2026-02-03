# Claude Code Role Commands

Custom commands for Claude Code that simulate a dev team with three roles: Project Manager, Developer, and QA Engineer.

## Roles

| Command     | Role            | What it does                                               |
| ----------- | --------------- | ---------------------------------------------------------- |
| `/项目经理` | Project Manager | Requirements analysis, architecture design, task breakdown |
| `/程序员`   | Developer       | Code implementation based on design docs                   |
| `/测试员`   | QA Engineer     | Code review and quality control                            |

## Usage

```bash
# Copy to your project
cp -r .claude/ /path/to/your/project/

# Verify commands are loaded
claude /项目经理
```

Then in Claude Code:

1. `/项目经理` - describe your requirements
2. `/程序员` - implement the design
3. `/测试员` - review the code

## Note

Commands and docs are in Chinese. Fork and translate if needed.

## License

MIT
