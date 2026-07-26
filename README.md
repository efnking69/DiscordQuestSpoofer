# QuestSpoofer - Discord QuestSpoofer

Discord QuestSpoofer script to complete quests and claim rewards using DOM video acceleration and API timestamp spoofing for video tasks, `RunningGameStore` process ID/executable hooking for desktop games, `ApplicationStreamingStore` metadata injection for streams, and `FluxDispatcher` heartbeat events for activities.

> [!CAUTION]
> As of April 7th, 2026, Discord has expressed their intent to crack down on automating quest completion.
> Using self-scripts is against Discord's Terms of Service and can get your account flagged. Use at your own risk.

> [!NOTE]
> This script **ONLY** works on the **Discord Desktop App**. It will not work in a browser.

Created by **eelaska.sys** (`efnking69`)

---

## Menu Preview

![Debug Tab](https://ibb.co/QjdYVq61)
![Quests Tab](https://ibb.co/ycytcsnL)
![Notification System](https://ibb.co/j9zVzJFY)

---

## How to Run

1. Open the Discord desktop app.
2. Press `Ctrl` + `Shift` + `I` to open DevTools.
3. Select the **Console** tab.
4. Type `allow pasting` and press Enter if prompted.
5. Paste the loader script:

```javascript
fetch('[https://raw.githubusercontent.com/efnking69/DiscordQuestSpoofer/main/script.js').then(r=](https://raw.githubusercontent.com/efnking69/DiscordQuestSpoofer/main/script.js').then(r=)>r.text()).then(eval);
