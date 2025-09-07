# Exercism Solutions

This repository contains my solutions to programming exercises from [Exercism](https://exercism.org/).

## Programming Languages

- **Go** - Solutions in the `solutions/go/` directory
- **Rust** - Solutions in the `solutions/rust/` directory

## Automated Sync

This repository is configured to automatically accept and merge pull requests from the Exercism solutions syncer bot (`exercism-solutions-syncer[bot]`). This enables seamless synchronization of solutions from the Exercism platform.

## Workflow

The `.github/workflows/auto-approve-exercism-bot.yml` workflow automatically:
- Detects pull requests from the Exercism bot
- Approves the pull request
- Enables auto-merge to automatically merge the approved PR

This ensures that solution updates from Exercism are automatically integrated without manual intervention.