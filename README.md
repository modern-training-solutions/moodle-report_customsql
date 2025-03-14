# moodle-report_customsql fork

✋ Hello! This is the fork of [moodleou/moodle-report_customsql](https://github.com/moodleou/moodle-report_customsql) maintained by Modern Training Solutions.

We intend this fork to be temporary until our PRs are accepted upstream. But we are building in the open.

## Branches

- [`README`](https://github.com/modern-training-solutions/moodle-report_customsql/tree/README) - It only has this note.
- Our [feat- and fix- branches](https://github.com/modern-training-solutions/moodle-report_customsql/branches) - These are based on [upstream/main](https://github.com/moodleou/moodle-report_customsql/tree/main) (rebased after any change upstream)
- [`production`](https://github.com/modern-training-solutions/moodle-report_customsql/tree/production) - The code we run in production. It is reproducibly built exactly like this:
  - Start with [upstream/main](https://github.com/moodleou/moodle-report_customsql/tree/main)
  - List any of our PRs we merge (in order)...
  - List any external PRs we merge (in order)...
  - List any additional specific commits we make (in order)... (so you can cherry pick if rebasing this branch)

## References

- We use production fork git flow [Will: link to blog post], until GitHub allows to add highly visible notes on a repo without checking in code to the default branch.
