---
layout: "single"
---

# Alacritty

{{< unsupported >}}

Open issue: https://github.com/alacritty/alacritty/issues/910

Related PR: https://github.com/alacritty/alacritty/pull/4763

---

# Black Box

{{< unsupported >}}

Relies on upstream VTE support: https://gitlab.gnome.org/GNOME/vte/-/issues/253

---

# Bobcat

{{< supported >}}

[Natively supports sixel](https://github.com/ismail-yilmaz/Bobcat#Features).

---

# ConEmu

{{< unsupported >}}

Open issue: https://github.com/Maximus5/ConEmu/issues/807

---

# Contour

{{< supported >}}

Natively Supports Sixel. Sixel is available in any version.

---

# ctx terminal

{{< supported >}}

From commit [1c51989b16e](https://ctx.graphics/commit/1c51989b16edf01f5debd21c7453d4de4a8d27f3.html) onwards.

---

# Darktile

{{< supported >}}

From commit [978d506](https://github.com/liamg/darktile/commit/978d5067f6e4cd428953602e492c9ca17ad8458b) onwards.

---

# DomTerm

{{< supported >}}

From version 2.0 (September 2019): https://domterm.org/Features.html.

---

# Eat

{{< supported >}}

From [version 0.9](https://codeberg.org/akib/emacs-eat/commit/38ba9a99b0983ecce4be4c2b7d69632d0666648e) onwards.

---

# Elementary Terminal

{{< unsupported >}}

Open issue: https://github.com/elementary/terminal/issues/717

Which references VTE upstream: https://gitlab.gnome.org/GNOME/vte/-/issues/253

---

# foot

{{< supported >}}

From version 1.2.0: https://codeberg.org/dnkl/foot/releases/tag/1.2.0.

---

# GNOME Terminal

{{< unsupported >}}

Open issue: https://gitlab.gnome.org/GNOME/vte/-/issues/253

---

# guake

{{< unsupported >}}

Open issue: https://github.com/Guake/guake/issues/1806

Which references VTE upstream: https://gitlab.gnome.org/GNOME/vte/-/issues/253

---

# iTerm2

{{< supported >}}

From version 3.3.0: https://iterm2.com/downloads.html.

---

# kitty

{{< unsupported >}}

See reasoning here: https://github.com/kovidgoyal/kitty/issues/2511#issuecomment-609543803

Kitty instead provides a **Terminal Graphics Protocol**: https://sw.kovidgoyal.net/kitty/graphics-protocol/

---

# konsole

{{< supported >}}

Support landed in version 22.04: https://bugs.kde.org/show_bug.cgi?id=391781.

---

# LaTerminal

{{< supported >}}

Supported since September 2022, uses the SwiftTerm engine.

---

# MacTerm

{{< supported >}}

Supported since version 20171210: https://www.macterm.net/updates/changelog-2017.html.

--- 
# mintty

{{< supported >}}

From version 2.6.0: https://github.com/mintty/mintty/releases/tag/2.6.0.

---

# mlterm

{{< supported >}}

Fully supported from version 3.1.9: https://github.com/arakiken/mlterm/blob/deb5aad490f/doc/en/ReleaseNote#L830.

---

# MobaXterm

{{< unsupported >}}

Could not find any sixel references in release notes.

---
# PuTTY

{{< unsupported >}}

Could not find any sixel references in source code, mailing list archives, or release notes.

---

# Rio terminal

{{< unsupported >}}

Open issue: https://github.com/raphamorim/rio/issues/38

---

# Rlogin

{{< supported >}}

[Rlogin](https://github.com/kmiya-culti/RLogin) Windows

---

# sixel-tmux

{{< supported >}}

[sixel-tmux](https://github.com/csdvrx/sixel-tmux) is a tmux fork that intercepts sixel sequences
and renders them with the best technique available for the terminal.

**Note**: [tmux](/#tmux) now has official support for SIXEL.

---

# suckless st

{{< alert >}}

Unofficial patch to add support: https://gist.github.com/saitoha/70e0fdf22e3e8f63ce937c7f7da71809

[st-flexipatch#30](https://github.com/bakkeby/st-flexipatch/issues/30) will provide a simple way
to use a current st version with SIXEL support.

---

# SwiftTerm

{{< supported >}}

From release 1.0.4: https://github.com/migueldeicaza/SwiftTerm/commit/3f7bed2243b.

---

# SyncTERM

{{< supported >}}

From release 1.1.

---

# TeraTerm

{{< unsupported >}}

Mentioned as feature "which may be supported in very far future" in https://ttssh2.osdn.jp/manual/4/en/about/requests.html.

---

# Terminal.app

{{< unsupported >}}

Could not find any sixel references in documentation.

---

# Terminology

{{< unsupported >}}

However Terminology has [extended escapes](https://man.archlinux.org/man/terminology.1.en#EXTENDED_ESCAPES_FOR_TERMINOLOGY:)
which allows one to render images.

---

# termux

{{< unsupported >}}

Open issue: https://github.com/termux/termux-app/issues/142

Related PR: https://github.com/termux/termux-app/pull/2973

There is a fork of termux which supports it: https://github.com/KitsunedFox/termux-monet

---

# Tilix

{{< unsupported >}}

Related issue: https://github.com/gnunn1/tilix/issues/1631

Which references VTE upstream: https://gitlab.gnome.org/GNOME/vte/-/issues/253

---

# tmux

{{< supported >}}

From commit [dfbc6b1](https://github.com/tmux/tmux/commit/dfbc6b1888c110cf0ade66f20188c57757ee1298) onwards.

tmux officially supports sixel when compiled with `./configure --enable-sixel`.

---

# toyterm

{{< supported >}}

From commit [692ee23](https://github.com/algon-320/toyterm/commit/692ee23c780945e76a1610cc45950df2e259c07a) onwards.

---

# URxvt

{{< unsupported >}}

There is an old fork (from 2018) that supports sixel: https://github.com/saitoha/rxvt-unicode-sixel

Exoterm is a more up-to-date fork with sixel support, among other things: https://github.com/tomas/exoterm

---

# U++

{{< supported >}}

[U++ Terminal Package](https://github.com/ismail-yilmaz/upp-components/tree/master/CtrlLib/Terminal)

---

# Visual Studio Code

{{< supported >}}

Must be enabled with `"terminal.integrated.enableImages": true`.

Uses xterm.js with xterm-addon-image, related PR: https://github.com/microsoft/vscode/pull/182442

From release 1.80: https://code.visualstudio.com/updates/v1_80#_image-support

---

# Warp

{{< unsupported >}}

Issue: https://github.com/warpdotdev/Warp/issues/26

---

# wezterm

{{< supported >}}

From release 20200620-160318-e00b076c: https://github.com/wez/wezterm/releases/tag/20200620-160318-e00b076c.

---

# Windows Console

{{< unsupported >}}

Could not find any sixel references in source code.

---

# Windows Terminal

{{< unsupported >}}

Open issue: https://github.com/microsoft/terminal/issues/448.

---

# xfce-terminal

{{< supported >}}

From commit [493a7a5](https://gitlab.xfce.org/apps/xfce4-terminal/-/commit/493a7a54b437df9419847b29fe94eae671816c09) onwards.

---

# xterm

{{< supported >}}

Enabled by default since [patch #359](https://invisible-island.net/xterm/xterm.log.html#xterm_359).

---

# xterm.js

{{< supported >}}

Requires https://github.com/jerch/xterm-addon-image

---

# yaft

{{< supported >}}

Framebuffer terminal

---

# Yakuake

{{< supported >}}

Depends on SIXEL support in konsole.

---

# Zellij

{{< supported >}}

From release 0.31.0: https://zellij.dev/news/sixel-search-statusbar/
