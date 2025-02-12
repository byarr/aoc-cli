# Contribution Guidelines

First off, thank you for considering contributing to this project.

If your contribution is not straightforward, please first discuss the change you
wish to make by creating a new issue before making the change.

When submitting pull requests, please write your commit message following the
guidelines in [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).
In particular, the commit message should start with one of the following types:

- **feat**: A new feature
- **fix**: A bug fix
- **refactor**: A code change that neither fixes a bug nor adds a feature
- **perf**: A code change that improves performance
- **test**: Adding missing tests or correcting existing tests
- **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
- **docs**: Documentation only changes
- **build**: Changes that affect the build system or external dependencies
- **ci**: Changes to CI or release configuration files and scripts

# Ideas

- Add a configuration file (in home or `.config` directory) that can store
  options like:
  - year
  - day
  - session-file
  - width
  - input-filename
  - description-filename

- Warn user if session file permissions allow reading by others.

- Add option to wait until the next puzzle unlocks with a countdown timer (for
  read and download commands).

- Commands:
  - `[c]alendar` - show progress calendar (stars collected each day).
  - `[d]ownload` - already implemented!
  - `[g]lobal-leaderboard` - show [global leaderboard](https://adventofcode.com/2022/leaderboard).
  - `[i]nit` - prompt for each configurable option (offering sensible defaults)
    and create a configuration file.
  - `[l]ogin` - prompt for session cookie and save it in a user-protected file.
  - `[pe]rsonal-stats` - show [personal stats](https://adventofcode.com/2022/leaderboard/self).
  - `[pr]ivate-leaderboard` - show [private leaderboards](https://adventofcode.com/2022/leaderboard/private).
  - `[r]ead` - already implemented!
  - `[se]t-config` - make changes to configuration file (e.g. `aoc set-config year 2015`).
  - `[st]ats` - show [event stats](https://adventofcode.com/2022/stats).
  - `[su]bmit` - already implemented!
  - `[u]nset-config` - restore default settings in configuratio file
    (e.g. `aoc unset-config year`).

- Add tests!!!