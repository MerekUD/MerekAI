![Made with 💔](https://img.shields.io/badge/Made_with-ChatGPT-red?style=flat-square)
![Obfuscation Level](https://img.shields.io/badge/Obfuscation-PyArmor-inactive?style=flat-square)


# 💀 MerekAI v4.9 - Full Source Leak

This is the **fully cracked and deobfuscated** version of the paid cheat previously sold by Merek.
It's built on top of ChatGPT-generated boilerplate, PyArmor obfuscation, and false promises of innovation. 
So you'll see how every AI cheat is just a paste.

## Features

* ✅ YOLOv8-based "AI" Aimbot
* ✅ Tkinter FOV Overlay (drawn with love and 0 effort)
* ✅ KeyAuth Integration with hardcoded creds 🤡
* ✅ Full Triggerbot support (sometimes)
* ✅ Clean `ctypes` abuse for mouse injection
* ✅ Script auto-exits if it detects skill

## Bonus

* Comes with unpatched `HWID` spoofing remnants.
* Includes all runtime obfuscation logic... but it's useless now 🤷‍♂️
* PyArmor "protection" now serving as a performance tax



## Developer Hall of Shame

* **Merek** – "Lead dev", who asked for his own source back 💀
* **Skillz** – Just here for moral support and fem jokes
* **Redacted** – Claimed he was untouchable, now touché
* **Thor\[LGBT]** – Unwilling mod, probably traumatized
* **Cebo\[BOSS]** – Spammed 💀 emojis, contributed 0 lines of code


## 🧠 Context

MerekUD is a paid cheat labeled as “AI-enhanced”, sold in several variants:

* **Slotted**
* **Slotted Pro**
* **Beta**

All three are essentially the **same product**, obfuscated using **PyArmor**, and gated behind a **KeyAuth license system**.

## 🔓 The Crack

After retrieving the obfuscated `.cdc.py` version (`merek.cdc.py`), I:

* Deobfuscated it using custom tools
* Identified hardcoded KeyAuth params:

```python
api('Merek AI', 'rNEfueX05o', 'fed1598db75dc08ff7f9275da32a4c058f03f4685465238c88683a523f3443d1', '1.0', getchecksum())
```

* Found reused backend logic across all “versions” of the cheat
* Saw no meaningful AI logic, only basic `Aimbot()` class calls from `lib/aimbot.py`

## 🧩 What They Claimed

> “Slotted Pro has better tracking”
> “We use enhanced AI prediction”

### ❗ Reality:

All configs load from the same structure. Sensitivity is just scaled using static math in `config.json`. Same imports. Same main file. Different names.

## 🗣️ The Discord Showdown

Upon exposing the truth in their server:

* Initial reaction: *“You’re bluffing”*
* Shifted to: *“Prove it, post the source”*
* Final state: *“Thanks for the shoutout bro”*

### Notable quotes:

> “I think I deleted the source, can you send it to me?” — *Merek, the dev*

> “Calling me ‘pička’ while begging for leaks, that’s poetry.” — *Me*

> “Thanks for the show. I’ll be watching v4.9.” — *Me, signing off*

## 🧪 GitHub Leak (Fake)

To close it clean, I dropped a fake GitHub repo, which is this one
With a readme just troll enough to twist the knife.

## My words
You don’t always need to nuke a project to win. Sometimes just showing you could is enough to:

* Expose the bullshit
* Make the dev ask for his own code
* Leave the group confused, defensive, and memeing as a coping mechanism

See you in v5.0 👋

## Credits

* Merek for the original code
* Redacted for acting like the dev
* Me for cracking it
* PyArmor for the false sense of security

## Final Message

Enjoy the leak.
I’ll be watching v4.9. 👀




## Disclaimer

Any resemblance to actual cheats, living or dead, is purely intentional.
