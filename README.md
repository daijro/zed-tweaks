# Zed Tweaks

Opinionated patches I use for Zed to help me migrate from VSCode.

![image](https://i.imgur.com/qEWiOL5.png)

---

### Changes

- No rounded corners on the window border or context menus
- Ctrl + scroll wheel increases/decreases the font size
- Menubar is merged into 1 compact row, and buttons will activate on click rather than on hover when `titlebar.show_menus` is true
- The split panel button splits to the right by default on click. Right click the button to show the original menu to split right/left/up/down
- Reduced the height of the breadcrumb bar to match the tabs height
- The editor buffer does not render under the minimap & scrollbar anymore
- Indent guidelines are shown on the first column like in VSCode
- Adds an X button to close the agent panel


---

### Instructions

```bash
git clone https://github.com/zed-industries/zed.git
cd zed
git checkout 6034961499c180c56c41e9647f8f5950b2a808ef
git apply /path/to/aio.patch
cargo build --release
```
