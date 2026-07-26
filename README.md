# QuestSpoofer - Discord QuestSpoofer

Discord QuestSpoofer script to complete quests and claim rewards using DOM video acceleration and API timestamp spoofing for video tasks, `RunningGameStore` process ID/executable hooking for desktop games, `ApplicationStreamingStore` metadata injection for streams, and `FluxDispatcher` heartbeat events for activities.

> [!CAUTION]
> As of April 7th, 2026, Discord has expressed their intent to crack down on automating quest completion. Though i have implemented alot of anti-flag bypasses which work very well even though other projects like Completediscordquest by aamia does not use any anti-flag bypasses and is still pretty undetected.
> Using self-scripts is against Discord's Terms of Service and can get your account flagged. Use at your own risk.

> [!NOTE]
> Works fully on **Discord Desktop App**. Web browsers support **Videos**, **Activities**, and **Auto-Claiming**—**Desktop App** is strictly required for **Games** and **Streams**.

Created by **eelaska.sys** (`efnking69`)

---

## Menu Preview

<p align="center">
  <b>Quests Tab</b><br>
  <img src="https://i.ibb.co/nqjJ5GGh/image.png" alt="Quests Tab" width="100%">
  <br><br>
  <b>Settings Tab</b><br>
  <img src="https://i.ibb.co/RGL8XzPT/image.png" alt="Settings Tab" width="100%">
  <br><br>
  <b>Debug Tab</b><br>
  <img src="https://i.ibb.co/ycpHBz4f/image.png" alt="Debug Tab" width="100%">
</p>

---

## How to Run

1. Open the Discord desktop app.
2. Press `Ctrl` + `Shift` + `I` to open DevTools.
3. Select the **Console** tab.
4. Type `allow pasting` and press Enter if prompted.
5. Paste the loader script:

```javascript
fetch('[https://raw.githubusercontent.com/efnking69/DiscordQuestSpoofer/main/script.js').then(r=](https://raw.githubusercontent.com/efnking69/DiscordQuestSpoofer/main/script.js').then(r=)>r.text()).then(eval);
