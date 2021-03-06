---
title: Vim Substituting 
tags: [vim]
keywords: vim 
last_updated: January 29, 2017
summary: "A crib of Vim tips and tricks."
sidebar: notes_sidebar
permalink: vim_substituting.html
folder: vim 
---

## Change

A change is a "chord" that deletes and switches to INSERT mode.

Key | Action
--- | ------
`cl` | Delete letter & INSERT mode.
`ch` | Delete back one letter & INSERT mode.
`cw` / `cW` | Delete word/WORD & INSERT mode.
`cb` / `cB` | Delete previous word/WORD & INSERT mode.
`c$` / `C` | Delete to end of line & INSERT mode.
`dt.` | Delete to end of line and period.
`c^` | Delete to beginning of line & INSERT mode.

##  Substituting Cases

Key | Action
--- | ------
`g~<motion>` | Swap case.
`gu<motion>` | Make lowercase.
`gU<motion>` | Make uppercase.
`3~` | Toggle case of next three characters.
`gUiw` | Make entire word uppercase. (If `i` is excluded, from current position to end of the word only.)
`gUiW` | Make entire WORD uppercase.
`gU3w` | Make next three words uppercase.
`gU0` | Make uppercase to beginning of line.
`gU$` | Make uppercase to end of line.

