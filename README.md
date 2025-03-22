# Zen UI: Compact URL + Sidebar

A minimalist UI mod that applies the official Zen color palette, shrinks and centers the URL bar, vertically compresses the sidebar, and removes visual clutter for a cleaner, more focused browsing experience.

---

## 🌟 Features

- 🔳 **Floating, compact URL bar**
- 🧱 **Vertically centered, compact sidebar**
- 🎨 **Applies the official Zen color palette**
- ✂️ **Removes unnecessary labels and buttons for a cleaner interface**
- 🖱️ **Sidebar and toolbar appear on hover for quick access**
- 🚀 **Fully compatible with Zen Browser's Compact Mode**

---

## 🛠 Preferences Setup

This mod **automatically applies** the recommended settings via JSON preferences, so you **don’t need to manually configure anything**.


{
  "zen.urlbar.behavior": "float",
  "zen.view.compact": true,
  "zen.view.compact.show-sidebar-and-toolbar-on-hover": true,
  "zen.view.compact.hide-toolbar": true,
  "zen.view.compact.hide-tabbar": true,
  "zen.view.compact.animate-sidebar": true,
  "zen.view.compact.toolbar-flash-popup": true
}


If certain features don’t work as expected, check your Zen Browser settings under **"Compact Mode" and "Zen URL Bar"** to ensure they align with your preferences.

---

## 💻 Toolbar Customization (macOS & Windows)

### 🪟 Windows:
1. Right-click the sidebar → **Customize Toolbar**
2. Remove all **Flexible Space** items to both the **left and right** of the URL input field.
   - This makes the URL bar's trigger area larger.

### 🍎 macOS:
1. Right-click the sidebar → **Customize Toolbar**
2. Drag **two Flexible Space** items to both the **left and right** of the URL input field.
3. _(Optional)_ For a perfectly symmetrical layout:
   - Move the **Back Arrow** to the **left** of the URL input.
   - Move the **Forward Arrow** to the **right** of the URL input.

**Suggested toolbar layout (left → right):**

[Close] [Minimize] [Maximize] [Reload] [Back] 
[URL Input] 
[Forward] [Any two toolbar items of your choice] [Three-dot Menu]
