---
title: The Eccentric Ways of iOS Safari with the Keyboard
published: true
permalink: the%20eccentric%20ways%20of%20ios%20safari%20with%20the%20keyboard
---

## Why this is challenging
### The amount of the page pushed offscreen varies
### You can’t tell that you’re in this semi-offscreen state
### You don’t know if the keyboard is showing, nor its height
### The standard DOM scrollIntoView method doesn’t know
### You don’t know if the user has a physical keyboard
### You cannot open the soft keyboard programmatically
## IOS的挑战有哪些？
### The iOS Simulator sometimes differs from physical devices
### Safari’s behavior differs between OS releases
### iPhone and iPad have different behavior
### iPad Safari’s behavior differs based on its width
> specifically, in the “Split View” mode where two apps are on screen simultaneously. Safari has three different layouts depending on its width, and those cause differences for your page layout.
### iOS Safari differs from iOS Chrome
### The “vh” unit gives different results
### Your page is always scrollable when the keyboard is visible