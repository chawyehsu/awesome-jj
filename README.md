# Awesome JJ

> A comprehensive list of awesome Jujutsu VCS resources.

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

[Jujutsu](https://www.jj-vcs.dev) (also known as jj) is a Git-compatible version control system.

## Table of Contents

- [Official Resources](#official-resources)
- [Articles](#articles)
- [Books](#books)
- [Videos](#videos)
- [Tools](#tools)
  - [GUI](#gui)
  - [TUI](#tui)
  - [Editor Integration](#editor-integration)
  - [Diff and Merge Drivers](#diff-and-merge-drivers)
  - [Workflows](#workflows)
  - [Misc Tools](#misc-tools)
- [Forges](#forges)
- [Miscellaneous](#miscellaneous)
- [Community](#community)
- [License](#license)

## Official Resources

- [Jujutsu homepage](https://www.jj-vcs.dev)
- [GitHub repository](https://github.com/jj-vcs/jj)
- [Official tutorial](https://docs.jj-vcs.dev/latest/tutorial)
- [Official documentation](https://docs.jj-vcs.dev/latest)
- [Frequently Asked Questions](https://docs.jj-vcs.dev/latest/FAQ/)

## Articles

- 07/2023 [jj init](https://v5.chriskrycho.com/essays/jj-init/) by Chris Krycho
- 01/2024 [Jujutsu: a new, Git-compatible version control system](https://lwn.net/Articles/958468/) by Daroc Alden
- 04/2024 [A Better Merge Workflow with Jujutsu](https://ofcr.se/jujutsu-merge-workflow) by Benjamin Tan
- 05/2024 [Jujutsu Strategies](https://reasonablypolymorphic.com/blog/jj-strategy/) by Sandy Maguire
- 06/2024 [Basic jj workflows](https://blog.chay.dev/basic-jj-workflows/) by Chay Choong
- 08/2024 [Understanding Revsets for a Better JJ Log Output](https://willhbr.net/2024/08/18/understanding-revsets-for-a-better-jj-log-output/) by Will Richardson
- 11/2024 [Jujutsu: A Haven for Mercurial Users at Mozilla](https://ahal.ca/blog/2024/jujutsu-mercurial-haven/) by Andrew Halberstadt
- 12/2024 [Jujutsu Megamerges and `jj absorb`](https://v5.chriskrycho.com/journal/jujutsu-megamerges-and-jj-absorb/) by Chris Krycho
- 01/2025 [Jujutsu VCS Introduction and Patterns](https://kubamartin.com/posts/introduction-to-the-jujutsu-vcs/) by Kuba Martin
- 02/2025 [Why are Jujutsu's ID Prefixes So Short?](https://jonathan-frere.com/posts/jujutsu-shortest-ids/) by Jonathan Frere
- 05/2025 [jj tips and tricks](https://zerowidth.com/2025/jj-tips-and-tricks/) by Nathan Witmer
- 05/2025 [Overengineering PR create with jj](https://crespo.business/posts/overeng-pr-create-jj/) by David Crespo
- 05/2025 [Configuring Jujutsu](https://oppi.li/posts/configuring_jujutsu/) by Akshay
- 06/2025 [Jujutsu on Tangled](https://blog.tangled.org/stacking/) by Akshay
- 07/2025 [Jujutsu For Busy Devs](https://maddie.wtf/posts/2025-07-21-jujutsu-for-busy-devs) by Madeleine Mortensen
- 08/2025 [Jujutsu with Radicle](https://radicle.dev/2025/08/14/jujutsu-with-radicle) by Fintan Halpenny
- 08/2025 [Understanding Jujutsu bookmarks](https://neugierig.org/software/blog/2025/08/jj-bookmarks.html) by Evan Martin
- 10/2025 [Switch to Jujutsu already: a tutorial](https://www.stavros.io/posts/switch-to-jujutsu-already-a-tutorial/) by Stavros
- 10/2025 [I see a future in jj](https://steveklabnik.com/writing/i-see-a-future-in-jj/) by Steve Klabnik
- 11/2025 [More Commands in the JJ Toolbox](https://willhbr.net/2025/11/22/more-commands-in-the-jj-toolbox/) by Will Richardson
- 12/2025 [why i think jj-vcs is worth your time](https://schpet.com/note/why-i-think-jj-vcs-is-worth-your-time) by Peter Schilling
- 01/2026 [How I use Jujutsu](https://abhinavsarkar.net/posts/jj-usage/) by Abhinav Sarkar
- 02/2026 [Jujutsu: Managing workspaces](https://pksunkara.com/tech-notes/jujutsu-managing-workspaces/) by Pavan Sunkara
- 03/2026 [Reviewing large changes with Jujutsu](https://ben.gesoff.uk/posts/reviewing-large-changes-with-jj/) by Ben Gesoff
- 04/2026 [Jujutsu megamerges for fun and profit](https://isaaccorbrey.com/notes/jujutsu-megamerges-for-fun-and-profit) by Isaac Corbrey
- 06/2026 [Jujutsu: The Git Upgrade You Didn't Know You Needed](https://www.git-tower.com/blog/jujutsu) by Bruno Brito

## Books

- [Jujutsu for Everyone](https://jj-for-everyone.github.io/) by Remo Senekowitsch
- [Steve's Jujutsu tutorial](https://steveklabnik.github.io/jujutsu-tutorial/) by Steve Klabnik
- [Evan's Jujutsu Tutorial](https://evmar.github.io/jjtut/) by Evan Martin
- [Ju! Ju! Tsu!](https://arialdo.codeberg.page/ju-ju-tsu/) by Arialdo Martini
- [Juju-chu! — Starting Your Jujutsu × AI Workflow with `jj new`](https://leanpub.com/juju-chu) by Yuka Ooka

## Videos

- 10/2022 [Jujutsu: A Git-Compatible VCS - Git Merge 2022](https://www.youtube.com/watch?v=bx_LGilOuE4)
- 03/2024 [What if version control was AWESOME?](https://www.youtube.com/watch?v=2otjrTzRfVk)
- 10/2024 [Jujutsu - A Git-compatible VCS - Martin von Zweigbergk | GitMerge 2024](https://www.youtube.com/watch?v=LV0JzI8IcCY)
- 11/2024 [Jujutsu | Ep. 5 Bits and Booze](https://www.youtube.com/watch?v=dwyMlLYIrPk)
- 06/2025 [JJ With Git is My New Favorite Workflow](https://www.youtube.com/watch?v=ou4ZNRFXkO0)
- 10/2025 [How Jujutsu Uses Git - Martin von Zweigbergk](https://www.youtube.com/watch?v=XPtvvfGX3UQ)
- 10/2025 [Solving Git's Pain Points with Jujutsu (with Martin von Zweigbergk)](https://www.youtube.com/watch?v=ulJ_Pw8qqsE)
- 10/2025 [JJ Con 2025](https://www.youtube.com/playlist?list=PLOU2XLYxmsILM5cRwAK6yKdtKnCK6Y4Oh) (playlist)
- 10/2025 [JJ and How to Evolve an Open Source Ecosystem](https://www.youtube.com/watch?v=JGAszo6Ud-U)
- 11/2025 [Goodbye Git? Why JJ Might Be the Future of Version Control](https://www.youtube.com/watch?v=J2f3Pj58wTg)
- 12/2025 [Jujutsu Megamerges & Git History Preview | Ep. 23 Bits and Booze](https://www.youtube.com/watch?v=PsiXflgIC8Q)
- 12/2025 [Stacked Diffs with Git and Jujutsu](https://www.youtube.com/watch?v=Er3dqH-lloY)
- 01/2026 [Hands-on Introduction to jujutsu (jj) | Rawkode Live](https://www.youtube.com/watch?v=bECcod9ZMl0)
- 01/2026 [Jujutsu Version Control Explained](https://www.youtube.com/watch?v=mM4nrhDenC8)
- 02/2026 [Make code changes without committing. Better than Git?](https://www.youtube.com/watch?v=ZiqFGZASSKs)
- 05/2026 [TokioConf 2026 - jj: Simpler and More Powerful Than Git by Steve Klabnik](https://www.youtube.com/watch?v=n8KzCUyId_Y)
- 07/2026 [JJ Version Control System | Simpler Git Alternative](https://www.youtube.com/watch?v=LPQJEyr4El8)

## Tools

### GUI

- https://github.com/gulbanana/gg - Gui for JJ
- https://github.com/hewigovens/jayjay - A native macOS GUI for Jujutsu (jj)
- https://checksimsoftware.com/jjewel - A native Mac client for the Jujutsu version control system
- https://github.com/chronologos/lightjj - A fast, powerful, single-binary Jujutsu client

### TUI

- https://github.com/tim-janik/jj-fzf - Text UI for Jujutsu based on fzf
- https://github.com/joshka/jk - A jj-native terminal UI for Jujutsu
- https://github.com/idursun/jjui - TUI designed for interacting with the Jujutsu version control system
- https://github.com/faldor20/jj_tui - A TUI for the Jujutsu version control system
- https://github.com/Cretezy/lazyjj - TUI for Jujutsu/jj, built in Rust with Ratatui

### Editor Integration

- [jiejie.nvim](https://github.com/jceb/jiejie.nvim) - Neovim frontend for Jujutsu in the style of vim-fugitive
- [jj-idea](https://github.com/kkkev/jj-idea) - Jujutsu VCS Plugin for IntelliJ IDEA
- [jj-mode.el](https://github.com/bolivier/jj-mode.el) - Jujutsu version control mode for Emacs inspired by Magit
- [jj.nvim](https://github.com/NicolasGB/jj.nvim) - Drive Jujutsu (jj) VCS from Neovim
- [JJ View](https://github.com/brychanrobot/jj-view) - Integrates Jujutsu (jj) version control into VS Code
- [Jujutsu Kaizen](https://github.com/keanemind/jjk) (jjk) - Jujutsu (jj) VCS support for VS Code
- [Majutsu](https://github.com/0WD0/majutsu) - Magit-inspired Emacs interface for the Jujutsu
- [Selvejj](https://selvejj.com/) - JetBrains IDEs plugin for integrating Jujutsu as a first-class VCS
- [VisualJJ](https://www.visualjj.com/) - Visual interface for Jujutsu and Git inside VS Code

### Diff and Merge Drivers

- [diffedit3](https://github.com/ilyagr/diffedit3) - Edit diffs in a 3-pane view
- [hunk.nvim](https://github.com/julienvincent/hunk.nvim) - A tool for splitting diffs in Neovim
- [jj-diffconflicts](https://github.com/rafikdraoui/jj-diffconflicts) - A conflict resolution merge tool for Jujutsu VCS that runs in Neovim
- [scm-record](https://github.com/arxanas/scm-record) - The built-in diff editor for Jujutsu
- [Meld](https://meldmerge.org/) - Visual diff and merge tool
- [Mergiraf](https://mergiraf.org/) - A syntax-aware merge driver
- [Oyui](https://github.com/emilien-jegou/oyui) - A modern TUI merge tool and staging interface for Jujutsu and Git
- [Weave](https://github.com/Ataraxy-Labs/weave) - Entity-level semantic merge driver

### Workflows

- https://github.com/dmmulroy/jj-ryu - Stacked PRs for Jujutsu. Push bookmark stacks to GitHub and GitLab as chained pull requests
- https://github.com/jennings/jj-spr - Super Pull Requests (SPR) is the power tool for Jujutsu + GitHub workflows
- https://github.com/keanemind/jj-stack - Stacked PRs on GitHub for Jujutsu
- https://codeberg.org/abrenneke/jj-vine - A tool for submitting stacked Pull/Merge Requests from Jujutsu bookmarks
- https://github.com/eersnington/jj-navi - Workspace navigation and management for Jujutsu
- https://github.com/mrjones2014/jj-gh - jj tools for working with GitHub PRs from your terminal
- https://github.com/glennib/stakk - A tool that bridges Jujutsu bookmarks to GitHub stacked pull requests

### Misc Tools

- https://github.com/junglerobba/diffsoup - A Gerrit-style patchset diff viewer for pull requests, using jujutsu
- https://github.com/modem-dev/hunk - A review-first terminal diff viewer for agent-authored changesets
- https://github.com/laulauland/jj-hunk - Programmatic hunk selection for Jujutsu
- https://github.com/acarapetis/jj-pre-push - Run pre-commit before `jj git push`
- https://github.com/neongreen/mono/tree/main/jj-run - A tool to execute shell commands across multiple repository changes in isolated workspaces using jj
- https://github.com/dmmulroy/jj-starship - Unified Starship prompt module for Git and Jujutsu
- https://github.com/jnsahaj/lumen - A diff viewer and code review TUI and CLI to generate commit messages with AI
- https://github.com/anthrofract/majjit - A TUI to manipulate the Jujutsu DAG
- https://github.com/hugoh/hrd - Multi-repo manager (TUI & CLI) for git and jj with parallel dispatch and live status
- https://github.com/hugoh/jj-trim - Clean up merged bookmarks and abandoned anonymous commits in a jj repository

## Forges

While Jujutsu works with Git compatible forges like GitHub, there are also some new forges/platforms worth mentioning, and some of them are exploring/offering a better integration and support for Jujutsu.

- [ERSC](https://ersc.io/) - Source control that scales as you grow ([Early Access](https://ersc.io/blog/ersc-availability))
- [Jujubi](https://juju.bi/) - Modern code forge built for speed (Early Access)
- [Radicle](https://radicle.dev/) - The sovereign forge
- [Revset](https://www.revset.dev/) - Commit First Code Forge (Early Access)
- [Tangled](https://tangled.org/) - The next-generation social coding platform

### Miscellaneous

- [JJ Cheat Sheet](https://justinpombrio.net/2025/02/11/jj-cheat-sheet.html)

## Community

- [Bluesky](https://bsky.app/profile/jj-vcs.dev)
- [Discord] [![discord-badge]][Discord]
- [GitHub Discussions](https://github.com/jj-vcs/jj/discussions)
- [Libera Chat] [![irc-badge]][Libera Chat]
- [Reddit](https://www.reddit.com/r/jjvcs/)

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the authors have waived all copyright and related or neighboring rights to this work.

[Discord]: https://discord.gg/dkmfj3aGQN
[discord-badge]: https://img.shields.io/discord/968932220549103686.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2
[Libera Chat]: https://web.libera.chat/?channel=#jujutsu
[irc-badge]: https://img.shields.io/badge/irc-%23jujutsu-blue.svg
