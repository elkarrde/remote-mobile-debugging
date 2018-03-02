# Outline

## 1. Introduction

### What problems it solves?

Remote mobile debugging is debugging running directly on mobile devices.

- debug web directly off the phone,
- see what happend on small screen, with address bar and virtual keyboard,
- DevTools for the small screen

### Built-in mobile simulators

Good, but not 1:1

### Requirements

- phone - Android or iOS;
- browser - Chrome, Firefox, Vivaldi or Safari;
- cable, maybe for Firefox,
- `weinre`, maybe.

---

## 2. Supported browsers and systems

### Android

- Chrome
- Firefox
- Vivaldi

### iOS

- Safari

### Windows Phone

Over `weinre`

---

## 3. Chrome

All devices running Blink, no iOS

- Android settings - Developer options - Enable USB debugging
- DevTools - Main menu - More tools - Remote devices
- DevTools - Settings - Discover USB devices

Remote devices tab - open & inspect

---

## 4. Firefox

All devices running Gecko, no iOS

- Android settings - Developer options - Enable USB debugging
- Settings - Advanced - Remote debugging via USB/Wi-Fi
- Tools - Web Developer - WebIDE

For debugging via Wi-Fi, scan the QR code provided by WebIDE.

---

## 5. Vivaldi

Already covered, Vivaldi uses Blink rendering engine from Chromium project, everything is exactly the same as in Chromium/Chrome.

---

## 6. Safari

All iOS devices running iOS 6+ and Safari

- Settings - Safari - Advanced - Web Inspector
- Preferences - Advanced - Show Develop in menu bar
- Safari - Develop - Phone

Works with Xcode phone simulator as well.

---

## 7. More tools

- `weinre` - WEb INspector REmote ([link](https://people.apache.org/~pmuellr/weinre/docs/latest/Home.html))
- Valence - Firefox Tools Adapter ([link](https://developer.mozilla.org/en-US/docs/Tools/Valence))

---

## 8. That's all, folks!

Well written guide: [A concise guide to remote debugging](https://developer.telerik.com/featured/a-concise-guide-to-remote-debugging-on-ios-android-and-windows-phone)
