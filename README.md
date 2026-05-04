# EpicArena Skills

> Reusable skill library for EpicArena platform. Open source with security audit.

## Overview

Skills are atomic execution tools that can be plugged into any workflow.
Each skill is an independent directory with its own SKILL.md.

## Skill Structure

```
skills/
  skill-name/
    SKILL.md          # Skill definition (required)
    scripts/          # Execution scripts (optional)
    references/       # Reference materials (optional)
```

## Contributing

1. Fork this repository
2. Create a new skill directory following the structure above
3. Submit a PR - automatic security audit will run
4. After review, skill will be merged to the library

## Security

All skills go through automatic security audit (GitHub Actions):
- Secret scanning (GitLeaks)
- Executable script review
- Network call detection
- SKILL.md validation

## License

MIT
