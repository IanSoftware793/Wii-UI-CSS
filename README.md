# Wii UI CSS

A Wii-inspired HTML/CSS UI framework for creating web interfaces with the look and feel of the Nintendo Wii Menu.

## ✨ Features

* 🎮 Wii-style channel buttons
* 🖼️ Channel artwork using images and GIFs
* ✨ Wii-inspired hover glow effects
* 🖱️ Custom Wii pointer/cursor
* 💬 Wii-style dialogs
* 🔘 Wii-style buttons
* ◀️▶️ Wii-style navigation buttons
* ⚙️ Settings channel
* 🏠 Wii-style footer
* 🕐 Date and clock support
* 📱 Responsive layout
* 🎨 Pure HTML + CSS
* ⚡ No CSS framework required
* 🔧 Easy to customize

## 📁 Project Structure

```text
Wii-UI-CSS/
│
├── index.html
├── wii.css
└── README.md
```

## 🚀 Getting Started

Download or clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/Wii-UI-CSS.git
```

Then open:

```text
index.html
```

in your web browser.

No build tools or installation are required.

## 🎮 Creating a Wii Channel

Add a channel to your HTML:

```html
<button class="wii-channel"
        onclick="openChannel('My Channel')">

    <div class="channel-image">

        <img src="my-channel.gif"
             alt="My Channel">

    </div>

    <div class="channel-title">
        My Channel
    </div>

</button>
```

The `wii.css` stylesheet automatically provides the Wii-style channel appearance.

## 🖼️ Using a GIF URL

You can also use an online image or GIF:

```html
<img
    src="https://example.com/channel.gif"
    alt="My Channel">
```

For example:

```html
<div class="channel-image">

    <img
        src="https://example.com/my-wii-channel.gif"
        alt="My Wii Channel">

</div>
```

Make sure the image host allows external embedding.

## 🔘 Wii Button

Create a Wii-style button with:

```html
<button class="wii-button"
        onclick="alert('Hello Wii!')">
    Start
</button>
```

## 💬 Wii Dialog

The project includes a Wii-inspired dialog system.

Example:

```html
<button class="wii-button"
        onclick="openDialog()">
    Open Dialog
</button>
```

JavaScript:

```javascript
function openDialog() {
    document
        .getElementById("dialog")
        .classList.add("show");
}

function closeDialog() {
    document
        .getElementById("dialog")
        .classList.remove("show");
}
```

## 🖱️ Wii Pointer

The interface can use a custom Wii-style cursor:

```css
body {
    cursor:
        url("https://www.rw-designer.com/cursor-view/23165.png")
        0 0,
        auto;
}
```

The cursor can also be applied to individual buttons:

```css
.wii-button {
    cursor:
        url("https://www.rw-designer.com/cursor-view/23165.png")
        0 0,
        pointer;
}
```

## 🏠 Wii Footer

The Wii footer can be created with:

```html
<footer class="wii-footer">

    <button class="wii-footer-button">
        ◀
    </button>

    <button class="wii-wii-button">
        Wii
    </button>

    <button class="wii-footer-button">
        ▶
    </button>

</footer>
```

## 🎨 Available CSS Classes

### Channels

```text
.wii-channel
.channel-image
.channel-title
.wii-channel-grid
.wii-empty
```

### Buttons

```text
.wii-button
.wii-footer-button
.wii-wii-button
```

### Dialogs

```text
.wii-dialog-overlay
.wii-dialog
.wii-dialog-title
.wii-dialog-content
.wii-dialog-icon
.wii-dialog-buttons
```

### Menu

```text
.wii-screen
.wii-top
.wii-top-left
.wii-top-right
.wii-menu
.wii-footer
```

### Special Components

```text
.wii-settings-channel
.settings-icon
.empty-channel-animation
```

## 🛠️ Customization

You can edit `wii.css` to change:

* Channel sizes
* Channel spacing
* Backgrounds
* Borders
* Shadows
* Hover effects
* Dialog sizes
* Footer appearance
* Button appearance
* Animations
* Cursor
* Responsive behavior

For example:

```css
.wii-channel {
    height: 190px;
    border-radius: 13px;
}
```

Change it to:

```css
.wii-channel {
    height: 220px;
    border-radius: 18px;
}
```

## 🌐 Browser Support

The project is designed for modern browsers supporting standard HTML5 and CSS3 features.

Recommended:

* Firefox
* Chrome
* Chromium
* Brave
* Microsoft Edge

## ⚠️ Disclaimer

This is a **Wii-inspired web UI project** and is not the official Wii Menu or official Nintendo software.

Nintendo and Wii are trademarks of Nintendo.

This project is intended as a web-development recreation/inspiration project.

## 📜 License

You can choose and add a license for your repository, such as the MIT License.

No license created. if you’re an part of us on github, Ask our guestbook: https://iansoftware.atabook.org/

## ⭐ Contributing

Contributions are welcome!

You can contribute by:

1. Forking the repository.
2. Creating a new branch.
3. Adding or improving Wii-style UI components.
4. Testing your changes.
5. Opening a pull request.

## 💡 Ideas

Possible future components:

* Wii Home Menu
* Wii Settings UI
* Wii Message Board
* Wii Shop-style interface
* Wii Remote pointer effects
* Channel installation animation
* Wii-style loading screen
* Wii-style keyboard
* Wii-style confirmation dialogs
* Wii-style system notifications
* Multiple Wii Menu pages

## 📸 Demo

Open `index.html` locally to try the interface.

---

**Wii UI CSS — HTML/CSS Wii-inspired interface components.**
Source: https://ian-software.neocities.org/CSS/Wii/source
