# Green Unicorn plugins

Public installation packages for Green Unicorn. Current stage release: **0.1.8**.

## Install in Claude

1. Open **Customize → Plugins → Add → Add marketplace**.
2. Add `https://github.com/pilattao/gu-ai-native-marketplace`.
3. Install **gu-ai-native-stage** and enable **Sync automatically** if available.
4. Connect **gu-core** to `https://stage.ai.greenunicorn.bh/mcp` through corporate OAuth.
5. Start a new conversation and use the personal setup prompt from the corporate portal to verify identity and read access.

Employees need no GitHub account, PAT or manual archive upload. Installation does not grant corporate data access. This is a stage release; native installation and update acceptance are checked separately.

For Claude Code, add this marketplace with `/plugin marketplace add https://github.com/pilattao/gu-ai-native-marketplace.git`, install `gu-ai-native-stage@green-unicorn`, and enable auto-update for this marketplace.

## License and release contents

Copyright 2026 Green Unicorn. Marketplace metadata and GU-owned plugin files are licensed under [Apache-2.0](plugins/gu-ai-native-stage/LICENSE). Third-party material retains its original licenses; see [notices](plugins/gu-ai-native-stage/THIRD_PARTY_NOTICES.md). No upstream endorsement is implied.

The [release receipt](releases/stage.json) binds exact package files and hashes. Development history, internal reports, tests and credentials are maintained separately and are not part of these installation packages.
