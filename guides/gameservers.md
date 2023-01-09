---
description: >-
  If you run your FiveM Server via a gameserver provider like zap or rocketnode,
  check this!
---

# 🎮 Gameservers

Mostly gameservers dont offer the additonal port, spectre needs. Check the following guides to use our webpanel on your gameserver.

## ZAP-Hosting

You need to navigate to your gameserver settings in the zap webpanel. At the bottom of the settings you will find following part.

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption><p>ZAP Gameserver settings (example)</p></figcaption></figure>

Check the "Additional Port" sections. Choose one free port.

Inside our config.json now adjust your settings:

```
"port": "30432"
```

Your webpanel is now accessable on your `http:://serverip:30432` (replace 30432 with your Additional Port).
