# Dotfiles

Personal dotfiles and small command-line shortcuts.

## Shell aliases

`.aliases` groups shortcuts for OpenCode, Docker Compose, and Terraform. To use
them, source the file from your shell startup file (for example, `~/.bashrc` or
`~/.zshrc`):

```sh
source /path/to/dotfiles/.aliases
```

Replace `/path/to/dotfiles` with the location of this repository. Start a new
shell or source your startup file again to load changes.

| Alias | Command |
| --- | --- |
| `noc` | Launch OpenCode with the `nolabs-ai/opencode` nono profile |
| `nocp` | Launch OpenCode with the `opencode-personal` nono profile |
| `dc` | `docker compose` |
| `tf` | `terraform` |

The corresponding tools (`nono`, OpenCode, Docker Compose, and Terraform) must
be installed and available on your `PATH` to use their aliases.
