# rosa
A modern and minimalistic theme for [Clover Bootloader](https://sourceforge.net/projects/cloverefiboot/).

![main](/screenshots/main.png)

![mac-alt](/screenshots/mac-alt.png)

![about](/screenshots/about.png)

#### Installation

Put theme folder (rosa) in EFI/Clover/themes.

#### Optional

By default the **label** element (Boot macOS from XXXX) is disabled. If you're using the timeout option in Clover config, I'd recommend enabling it to see the counter.

Change
```html
<key>Label</key>
<false/>
```
to
```html
<key>Label</key>
<true/>
```
in theme.plist.
