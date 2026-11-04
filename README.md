# KLC Light bar widget for Omarchy

A bar widget for [KLC Light](https://github.com/swald54000/klc-light), the per-key keyboard
lighting editor for MSI laptops (SteelSeries KLC controller). A keyboard icon, dimmed while
the lighting is off, whose tooltip names the applied profile. Click it for the profile list
(a click applies one), right-click to turn the keyboard off, middle-click to turn it back on;
the panel also opens the editor.

Needs KLC Light installed (`yay -S klc-light`, then join the `klc-light` group).

```sh
omarchy plugin add https://github.com/swald54000/omarchy-klc-light.git --enable
```
