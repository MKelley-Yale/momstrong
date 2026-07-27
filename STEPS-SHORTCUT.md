# "Today's Steps" iPhone Shortcut

**Version 1.0 — completed 2026-07-27**

One tap → shows today's step total from Apple Health and copies it to the clipboard, so you can paste it into the Steps box in the workout app.

Apple doesn't allow shortcut files to be shared as plain files, so you build it once yourself — about 2 minutes, 4 actions.

## Build it

1. Open the **Shortcuts** app → **+** (new shortcut).
2. Tap **Add Action**, search **"Find Health Samples"**, pick **Find All Health Samples Where**.
   - Set type to **Steps**.
   - Tap **Add Filter** → **Start Date** → **is in** → **Today**.
   - Leave Sort/Limit off.
3. Add action: search **"Calculate Statistics"** → set operation to **Sum** (input should auto-fill with the Health Samples).
4. Add action: **Copy to Clipboard** (input: the Statistics result).
5. Add action: **Show Result** → type `Steps today:` then insert the **Statistics** variable.
6. Tap the name at top → rename to **Today's Steps**, pick an icon → **Done**.

First run: iOS asks for Health access — allow **Steps**. (If it ever fails silently: Settings → Privacy & Security → Health → Shortcuts → allow read for Steps.)

## Make it one tap away

Pick whichever you'll actually use:

- **Home screen icon**: in Shortcuts, long-press the shortcut → Share → **Add to Home Screen**. Put it next to Documents.
- **Lock screen / home widget**: add a **Shortcuts** widget and point it at Today's Steps.
- **Back Tap**: Settings → Accessibility → Touch → Back Tap → Double Tap → Today's Steps. Double-tap the back of the phone anywhere → steps appear.
- **Siri**: "Hey Siri, Today's Steps."

## Daily flow

1. Tap the shortcut (steps show + copy to clipboard).
2. Open the workout app → tap the **Steps** box in the top strip → paste (long-press → Paste) or just type it.

Best done once in the evening since the number grows all day — whatever you enter last for the day is what's kept.
