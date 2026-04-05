<div align="center">

<img src="https://raw.githubusercontent.com/MohammadYehya/volt-os.github/main/gitassets/VoltOS_nobg.png" alt="VoltOS" width="200"/>

<br/>
<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Orbitron&weight=900&size=42&duration=1&pause=1000&color=58E1FF&center=true&vCenter=true&repeat=false&width=500&height=60&lines=VOLT+OS"/>
  <img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=900&size=42&duration=1&pause=1000&color=58E1FF&center=true&vCenter=true&repeat=false&width=500&height=60&lines=VOLT+OS"/>
</picture>

<sub><sup>L I N U X &nbsp;&nbsp; M A D E &nbsp;&nbsp; F A S T , &nbsp;&nbsp; F L U I D , &nbsp;&nbsp; A N D &nbsp;&nbsp; Y O U R S .</sup></sub>

[![Built on Arch](https://img.shields.io/badge/Built%20on-Arch%20Linux-1793D1?style=flat-square&logo=arch-linux&logoColor=white)](https://archlinux.org/)
&nbsp;
[![Compositor](https://img.shields.io/badge/Compositor-Hyprland-58E1FF?style=flat-square&logo=wayland&logoColor=white)](https://hyprland.org/)
&nbsp;
[![Shell](https://img.shields.io/badge/Shell-QuickShell-A6E3A1?style=flat-square)](https://quickshell.outfoxxed.me/)
&nbsp;
[![Status](https://img.shields.io/badge/Status-Alpha-F9E2AF?style=flat-square)]()
&nbsp;
[![License](https://img.shields.io/badge/License-GPL--3.0-F38BA8?style=flat-square&logo=gnu&logoColor=white)](./LICENSE)

</div>

<br/>

---

<br/>

<div align="center">

## 〔 The Vision 〕

</div>

<br/>

> **VoltOS** is not a reskin. It is a rethinking.
>
> Built on the bare metal of Arch Linux, animated by Hyprland, and fully expressed through QuickShell — VoltOS is a distribution designed around three uncompromising ideas: your system should launch before you blink, move like it has weight, and look exactly the way you want it to.
>
> No bloat inherited. No opinions forced. No ceiling on what you can build with it.

<br/>

---

<br/>

<div align="center">

## 〔 Core Pillars 〕

</div>

<br/>

<table>
<tr>
<td width="33%" valign="top" align="center">

**SPEED**

VoltOS ships nothing it doesn't need. No redundant services, no background noise, no weight you didn't ask for. Arch gives us the leanest possible foundation — we keep it that way. Boot fast. Launch instantly. Stay out of your way.

</td>
<td width="33%" valign="top" align="center">

**FLUID ANIMATIONS**

Every window open, close, move, and workspace transition is deliberate. Hyprland's GPU-accelerated compositor makes spring physics and bezier curves first-class citizens. Nothing snaps. Everything flows.

</td>
<td width="33%" valign="top" align="center">

**CUSTOMIZABILITY**

QuickShell gives you QML — a real language, not a config file. Rewrite the bar. Rebuild the launcher. Redesign the lock screen from scratch. VoltOS hands you every component and says: *make it yours.*

</td>
</tr>
</table>

<br/>

---

<br/>

<div align="center">

## 〔 The Stack 〕

</div>

<br/>

VoltOS is built around a curated set of tools chosen for performance, composability, and long-term hackability. The stack is not final — some decisions are still being evaluated — but the direction is clear.

<br/>

| Layer | Planned Technology | Notes |
|---|---|---|
| Base | Arch Linux | Rolling release, minimal, no hand-holding |
| Compositor | Hyprland | Wayland, tiling, GPU-accelerated animation |
| Desktop Shell | QuickShell | QML-powered, fully scriptable |
| Package Manager | pacman + AUR helper | Full Arch ecosystem access |
| Audio | PipeWire | Low-latency, modern audio stack |
| Network | NetworkManager | Being evaluated |
| Display Manager | TBD | Lightweight, Wayland-native options under review |
| Notifications | TBD | Likely handled natively by QuickShell |
| Lock Screen | TBD | Custom QuickShell implementation or hyprlock |

<br/>

---

<br/>

<div align="center">

## 〔 The Marketplace 〕

</div>

<br/>

VoltOS ships with a curated base of software — everything you need to get started, nothing you didn't ask for. But the real power comes after first boot.

The **VoltOS Marketplace** is the built-in hub for everything beyond the base install. It is not a package manager wrapper. It is a first-class application — designed, integrated, and shipped as part of the desktop.

<br/>

<table>
<tr>
<td width="50%" valign="top">

**Verified Apps**

Software reviewed, tested, and approved by the VoltOS team. Guaranteed to integrate cleanly with the shell and meet a baseline quality standard. Safe to install. No surprises.

</td>
<td width="50%" valign="top">

**Community Apps**

Packages, themes, shell components, and extensions built and published by the community. Clearly marked as community-sourced. Install knowing what you're getting. Rate, flag, and contribute back.

</td>
</tr>
</table>

<br/>

The Marketplace is still in active design. If you have opinions on how it should work, open a [Discussion](https://github.com/MohammadYehya/volt-os.github/discussions).

<br/>

---

<br/>

<div align="center">

## 〔 Installation 〕

</div>

<br/>

> **VoltOS is in active development.** A proper installer and ISO are not yet available. What follows is the anticipated setup path — expect it to change.

<br/>

The planned installation flow:

1. Start from a clean Arch Linux base install
2. Clone the VoltOS configuration repository
3. Run the setup script — it handles packages, configs, fonts, services, and defaults
4. Log out and back in to your new desktop

```bash
# Anticipated — not yet stable
git clone https://github.com/MohammadYehya/volt-os.github.git
cd volt-os.github
./install.sh
```

A bootable ISO with a guided installer is planned for a later milestone. Watch the [Releases](https://github.com/MohammadYehya/volt-os.github/releases) page.

<br/>

---

<br/>

<div align="center">

## 〔 Roadmap 〕

</div>

<br/>

| Status | Milestone |
|---|---|
| Done | Hyprland base configuration |
| Done | QuickShell bar and system tray |
| Done | App launcher |
| Done | Lock screen |
| In Progress | Automated install script |
| In Progress | NVIDIA compatibility |
| Planned | Marketplace — first release |
| Planned | Verified app catalogue |
| Planned | Community submission pipeline |
| Planned | Bootable ISO with guided installer |
| Planned | Custom GRUB theme |
| Planned | VoltOS settings panel |

<br/>

---

<br/>

<div align="center">

## 〔 Contributing 〕

</div>

<br/>

VoltOS is an open project and contributions are welcome at every level — code, design, documentation, bug reports, and feedback all move it forward.

```bash
git clone https://github.com/YOUR_USERNAME/volt-os.github.git
cd volt-os.github
git checkout -b feature/your-idea

git commit -m "feat: describe your change clearly"
git push origin feature/your-idea
# Open a Pull Request
```

If you are not sure where to start, check the open [Issues](https://github.com/MohammadYehya/volt-os.github/issues) or start a [Discussion](https://github.com/MohammadYehya/volt-os.github/discussions).

<br/>

---

<br/>

<div align="center">

## 〔 License 〕

</div>

<br/>

VoltOS is distributed under the **GNU General Public License v3.0**.

Free to use. Free to modify. Free to distribute — as long as it stays open.
See [LICENSE](./LICENSE) for the full terms.

<br/>

---

<br/>

<div align="center">

[![Stars](https://img.shields.io/github/stars/MohammadYehya/volt-os.github?style=flat-square&color=FFD700)](https://github.com/MohammadYehya/volt-os.github/stargazers)
&nbsp;&nbsp;
[![Issues](https://img.shields.io/github/issues/MohammadYehya/volt-os.github?style=flat-square&color=F38BA8)](https://github.com/MohammadYehya/volt-os.github/issues)
&nbsp;&nbsp;
[![Forks](https://img.shields.io/github/forks/MohammadYehya/volt-os.github?style=flat-square&color=A6E3A1)](https://github.com/MohammadYehya/volt-os.github/fork)

<br/>

<sub>Fast. Fluid. Yours.</sub>

</div>
