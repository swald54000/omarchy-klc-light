# KLC Light bar widget for Omarchy

A bar widget for [KLC Light](https://github.com/swald54000/klc-light), the per-key keyboard
lighting editor for MSI laptops (SteelSeries KLC controller). A keyboard icon, dimmed while
the lighting is off, whose tooltip names the applied profile. Click it for the profile list
(a click applies one), right-click to turn the keyboard off, middle-click to turn it back on;
the panel also opens the editor.

Needs [KLC Light](https://github.com/swald54000/klc-light) installed (see its README:
build it with the PKGBUILD in `aur/`, or install the package attached to its latest
release), and your user in the `klc-light` group.

```sh
omarchy plugin add https://github.com/swald54000/omarchy-klc-light.git --enable
```

To remove it:

```sh
omarchy plugin remove swald.klc-light
```

It only runs the `klc-light` command line (`list`, `apply`, `off`) and reads
`~/.config/klc-light/state.json`; it changes no configuration. MIT license.
