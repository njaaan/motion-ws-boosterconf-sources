# Where to find the prefers-reduced-motion settings
## Reduce Motion settings in different Operating Systems
We try to document where to find the settings that tell the OS that you `prefer(s)-reduced-motion`. The OS will then tell most apps that care about this setting (including the browsers) about this preference.

Unfortunately the naming and location of the respective settings seems to get changed a lot during updates, so this guide might be outdated. PRs and issues are highly appreciated.

When in doubt, use the search function in your OS settings and look for `reduce` or `animation`.

### Windows
#### Windows 11
Start > Settings > Accessibility > Visual Effects > **Animation effects**
(We could not test yet if this is also communicated to the browser as it is the default in other OS.)

#### Windows 10
Settings > Ease of Access > Display > **Show animations**
(We could not test yet if this is also communicated to the browser as it is the default in other OS.)

### Apple's OS
#### macOS 15.5
Settings > Accessibility > Display > **Reduce motion**
#### iOS 18.5
Settings > General > Accessibility > **Reduce Motion**

### Android
#### Android 9+
Settings > Accessibility > **Remove animations**

### Linux
#### Plasma/KDE
System Settings > Workspace Behavior -> General Behavior > **Animation speed** is set all the way to right to "Instant" 
(Not sure if this also works in browsers besides Firefox)

#### GTK/GNOME (Ubuntu)
Settings > Accessibility > Seeing > **Reduced animation**

#### Older versions of GNOME
GNOME Tweaks > General tab (or Appearance, depending on version) > **Animations**

Alternatively, add `gtk-enable-animations = false` to the `[Settings]` block of the [GTK 3 configuration file](https://wiki.archlinux.org/title/GTK#Configuration).


## Reduce-motion directly in the browser
### Firefox
In `about:config`: `ui.prefersReducedMotion`. `1` enables the "prefers reduced motion" meaning you will see less animations. `0` does the opposite (which is the default).


## Sources
- [MDN: prefers-reduced-motion](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-reduced-motion#user_preferences) (unfortunately only considers Firefox so you might need different settings for other browsers)
- [Stack Overflow: "How do I change the `prefers-reduced-motion` setting in browsers?"](https://stackoverflow.com/questions/59708960/how-do-i-change-the-prefers-reduced-motion-setting-in-browsers)