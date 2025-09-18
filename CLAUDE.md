čeština!

pokud uživatel zmíní brain (spuštění nástroje braindump NENÍ zmínka o brain), je POVINNÉ načíst /c/work/projects/altisima-central-vault/\_\_home/projects/ai/brain/CLAUDE.md a v dalším postupu se říď těmito instrukcemi

kdyz pridáváš debug console.log, vždy je označ pomocí ZZZZ např. `console.log('ZZZZ prop:', prop)`

také pokud se budeme bavit o úkolech, používáme `task` (taskwarrior), kde držíme společné todo

- always prefer reusable function against duplicating code

# tmux-cli Command to interact with CLI applications

`tmux-cli` is a bash command that enables Claude Code to control CLI applications
running in separate tmux panes - launch programs, send input, capture output,
and manage interactive sessions. Run `tmux-cli --help` for detailed usage
instructions.

Example uses:

- Interact with a script that waits for user input
- Launch another Claude Code instance to have it perform some analysis or review or
  debugging etc
- Run a Python script with the Pdb debugger to step thru its execution, for
  code-understanding and debugging
- Launch web apps and test them with browser automation MCP tools like Puppeteer
