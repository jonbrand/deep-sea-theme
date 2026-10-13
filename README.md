# Ocean Green — tema para Omarchy

Tema para o [Omarchy](https://omarchy.org) 4 baseado no tema
[Ocean Green](https://github.com/datyin/theme-ocean-green) para VS Code, de Jove Jonovski.

## Instalação

```bash
ln -s "$PWD" ~/.config/omarchy/themes/ocean-green
omarchy theme set ocean-green
```

Ou publique este diretório em um repositório git e use `omarchy theme install <url>`.

## Conteúdo

| Arquivo | Função |
|---|---|
| `colors.toml` | Paleta. O Omarchy gera a partir dela os configs de terminal, Hyprland, btop, barra, Neovim etc. |
| `vscode.json` | Instala e ativa a extensão original `jovejonovski.ocean-green` no VS Code |
| `icons.theme` | Tema de ícones `Yaru-sage-dark` |
| `backgrounds/` | Dois wallpapers 2560×1440 gerados com ImageMagick na paleta do tema |

## Paleta

Valores extraídos de `themes/dark-color-theme.json` do tema original:

| Papel | Cor | Origem no VS Code |
|---|---|---|
| background | `#111d1e` | `editor.background` |
| dark_background | `#0e1819` | `sideBar.background` / `terminal.background` |
| foreground | `#639caa` | `foreground` |
| accent | `#19d08a` | `focusBorder` / `editorCursor.foreground` |
| selection | `#14402f` | `badge.background` |
| ANSI | `#bb6666` `#66bb66` `#bbb466` `#2a99b5` `#aa6eb8` `#34bbbb` | `terminal.ansi*` |

A borda ativa das janelas no Hyprland é um gradiente do verde de destaque (`#19d08a`) para o azul (`#2a99b5`).

## Créditos

Cores originais © 2022 Jove Jonovski, licença MIT (ver `LICENSE`).
