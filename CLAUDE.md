# CLAUDE.md — neo-candy-tela-blue

## Project overview

Standalone repo for the **neo-candy-tela-blue** folder-icon theme — the same folder set as
`erikdubois/surfn-tela-blue` re-based onto the neo-candy-icons fallback.

## Current state

Ships one theme: `usr/share/icons/neo-candy-tela-blue/` — folders only. Packaged as `neo-candy-tela-blue-icons-git`
(recipe in `~/KIRO-PKG-BUILD-ICONS/neo-candy-tela-blue/`), `depends=('neo-candy-icons-git')`.

## Patterns & decisions

- Folders only; everything else inherits neo-candy-icons. `icon-theme.cache` gitignored.
  Payload reused verbatim from the Surfn counterpart; only Name/Inherits/dir name differ.
