<p align="center">
  <img src="logo.svg" alt="Omarchy" width="520">
</p>

<h1 align="center">Awesome Omarchy</h1>

<p align="center">
  A curated list of apps that feel at home on
  <a href="https://omarchy.org/">Omarchy</a> — the omakase Arch + Hyprland desktop by DHH.
</p>

<p align="center">
  <a href="https://omarchy.org/">Website</a> ·
  <a href="https://omarchy.org/manual/guis/">App manual</a> ·
  <a href="https://learn.omacom.io/2/the-omarchy-manual">User manual</a> ·
  <a href="https://github.com/basecamp/omarchy">GitHub</a>
</p>

---

Omarchy ships a keyboard-first desktop and a short list of tools that already match its taste: tiling, theming, and as little ceremony as possible. This list collects those first-party apps plus extras you can install from the Omarchy menu (`Super + Alt + Space`) or the AUR.

Want something added? Open a pull request or drop a name in an issue.

## Contents

- [Writing and notes](#writing-and-notes)
- [Files and sharing](#files-and-sharing)
- [Media](#media)
- [Office and utilities](#office-and-utilities)
- [Communication](#communication)
- [Editors and terminals](#editors-and-terminals)
- [Theming](#theming)
- [Gaming](#gaming)
- [Community plugins](#community-plugins)

---

## Writing and notes

### [Obsidian](https://obsidian.md)

A free, extensible notes app that stores everything as Markdown. Omarchy binds it to `Super + Shift + O`. Pick the **Omarchy** theme in settings if you want the vault to follow the system look.

### [Omawrite](https://omarchy.org/manual/guis/#omawrite)

Omarchy’s own dead-simple Markdown writer. No vaults, no plugins — just you and the words. Open it with `Super + Shift + W`.

### [Typora](https://typora.io)

A distraction-free Markdown editor in the same spirit as iA Writer. Better for a single essay than a whole vault. Install it from the Omarchy menu when you want a prettier writing surface than a terminal buffer.

---

## Files and sharing

### [Files (Nautilus)](https://omarchy.org/manual/guis/#files)

The graphical file manager. `Super + Shift + F` opens it; `Super + Shift + Alt + F` opens it in the directory your terminal is already sitting in. Space previews a file, `Ctrl + L` jumps to a path, and removable disks show up in the sidebar on their own.

### [LocalSend](https://localsend.org)

AirDrop-style file transfer that works across Linux, macOS, Windows, Android, and iOS. Omarchy leaves the LocalSend port open and wires it to `Super + Ctrl + S` (or Trigger → Share). You can also run `omarchy share clipboard`, `omarchy share file`, or `omarchy share folder`.

---

## Media

### [mpv](https://mpv.io)

A fast, no-chrome player that will play almost anything. Double-click a video in Files, or launch it from the app menu.

### [OBS Studio](https://obsproject.com)

Record or stream from several inputs at once — screen, camera, mic. This is what the official Omarchy screencasts are made with.

### [Kdenlive](https://kdenlive.org)

A full video editor for the footage that comes out of OBS. Available from the application launcher (`Super + Space`).

### [Omacut](https://omarchy.org/manual/guis/#omacut)

Omarchy’s own dead-simple video trimmer. When you only need to cut the head and tail off a clip, this beats opening a timeline.

### [Pinta](https://www.pinta-project.com)

Basic image editing: crop, resize, layers, magic wand. Not Photoshop — just enough to fix a screenshot.

### [Spotify](https://open.spotify.com)

Music streaming, ready from the Omarchy install menu. Pairs with the desktop media controls.

---

## Office and utilities

### [LibreOffice](https://www.libreoffice.org)

Word processor, spreadsheet, slides, and drawings, with decent Microsoft Office file compatibility. Launch it from `Super + Space` when someone sends you a `.docx`.

### [Omacalc](https://omarchy.org/manual/guis/#omacalc)

Omarchy’s floating calculator. `Super + Ctrl + Q`, or the calculator key if your keyboard has one.

### [1Password](https://1password.com)

Password manager with a first-class Linux app. Install it from the Omarchy menu when you want the vault on this machine too.

---

## Communication

### [Signal](https://signal.org)

End-to-end encrypted messaging that does not run through the usual chat conglomerates. `Super + Shift + G` — first press offers to install it if it is not on the system yet.

### [HEY](https://hey.com)

DHH’s email service, available as an Omarchy web app so it lives next to the rest of the desktop instead of in a random browser tab.

### [Zoom](https://zoom.us)

Video calls, listed in the Omarchy install options so you are not hunting for a Flatpak on meeting day.

---

## Editors and terminals

### [Neovim](https://neovim.io)

The default editor. Omarchy ships a tuned config (`omarchy-nvim`) so you can start working before you have opinions about Lua.

### [VS Code](https://code.visualstudio.com) · [Cursor](https://cursor.com) · [Zed](https://zed.dev) · [Sublime Text](https://www.sublimetext.com) · [Helix](https://helix-editor.com)

Mainstream editors, all installable from **Install → Editor** in the Omarchy menu. Pick one and you can set it as the system-wide default.

### [Foot](https://codeberg.org/dnkl/foot) · [Alacritty](https://alacritty.org) · [Ghostty](https://ghostty.org) · [Kitty](https://sw.kovidgoyal.net/kitty)

Four terminals, one set of shortcuts. Foot is the light default; switch under the Omarchy menu if you want images, splits, or a different rendering stack.

---

## Theming

### [Aether](https://omarchy.org/manual/guis/#aether)

Extract a palette from a wallpaper and turn it into a full Omarchy theme — terminal, bar, notifications, the lot. The fastest way to make the desktop yours without editing color files by hand.

---

## Gaming

### [Steam](https://store.steampowered.com)

The PC library, with Proton, on a desktop that already handled the graphics drivers during install.

### [RetroArch](https://www.retroarch.com)

Classic consoles with a full set of cores and the CRT Royale shader already dialed in.

### [Lutris](https://lutris.net) · [Heroic](https://heroicgameslauncher.com)

Non-Steam stores and launchers, available from the gaming install options.

### [Moonlight](https://moonlight-stream.org)

Stream games from another PC. Xbox Cloud Gaming and GeForce NOW are also a menu away if you would rather not run the title locally.

### [Minecraft](https://www.minecraft.net)

Install it straight from the Omarchy gaming menu when you want a world to sink a weekend into.

---

## Community plugins

These live in the Omarchy plugin ecosystem (bar, widgets, and extra desktop toys). Browse more on [omarchy.org](https://omarchy.org/).

### Radio Atlas

A rotatable globe of live radio stations that play through Omarchy’s media controls.

### Omagotchi

A 1-bit desktop pet in the bar. Feed it, wash it, let it climb your windows. It hatches and evolves if you keep it alive.

### AirPods

Per-pod and case battery, listening mode, adaptive noise, conversation awareness, and ear detection — in the Omarchy bar.

### Omasweeper

Minesweeper drawn like a TUI: character grid, vim motions, 8-bit beeps. Opens as a normal tiled window.

### Time Machine

Scheduled restic backups with a destination picker and a snapshot browser.

### Omarchy Pets

An animated companion in the bar that glances at your cursor and can be pinned to the desktop.

---

## Contributing

Add an app with a **title**, a short **paragraph**, and a **link**. Keep it Omarchy-flavored: Wayland-friendly, keyboard-friendly, or already wired into the Omarchy menu.

```markdown
### [App name](https://example.com)

One or two sentences: what it is, why it belongs on Omarchy, and how you open or install it.
```
