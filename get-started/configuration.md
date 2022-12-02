---
description: Spectre offers the following configuration options.
---

# ⚙ Configuration

```js-templates
// server.cfg

set unlWebPort [Int]                  // sets webpanel serving port @default: 3000


set unlUsedInventory [String]         // sets used inventory @default: qb-inventory
set unlQBName [String]                // sets qb-core resource name @default: qb-core
set unlQBObject [String]              // sets QBCore object name @default: QBCore
set unlQBShared [String]              // sets QBCore shared object name @default: QBShared

set unlWebDashInterval [Int]          // sets dashboard refresh interval @default 5000
set unlWebMapInterval [Int]           // sets map refresh interval @default: 1250

set unlDiscordHook [WebhookUrl]       // sets Unlimited Logger Discord-Webhook
set unlGameDiscordHook [WebhookUrl]   // sets Game Logger Discord-Webhook
set unlPlayerDiscordHook [WebhookUrl] // sets Player Logger Discord-Webhook
set unlDevDiscordHook [WebhookUrl]    // sets Dev Logger Discord-Webhook
set unlWebDiscordHook [WebhookUrl]    // sets Web Logger Discord-Webhook


```

