# Description
This is a patched version of the suckless simple terminal. It's updated to 0.8.2. The patches i applied include:
- Transparency
- Scrolling

# Keybindings
- **Shift + PageUp** to scroll up (1 page)
- **Shift + PageDown** to scroll down (1 page)
- **Control + Shift + PageUp** to increase font size
- **Control + Shift + PageDown** to decrease font size

# Build
For transparency to take effect, you will need an X composite manager like compton.
```bash
git clone git@github.com:nikosbatsaras/st.git
cd st && make
```

# Install
```bash
sudo make install
```
