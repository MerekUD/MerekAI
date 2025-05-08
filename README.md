# MerekAI
# Cracking MerekUD: A Deobfuscation Walkthrough & Discord Meltdown

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

## 💡 Final Words
You don’t always need to nuke a project to win. Sometimes just showing you could is enough to:

* Expose the bullshit
* Make the dev ask for his own code
* Leave the group confused, defensive, and memeing as a coping mechanism

See you in v5.0 👋

## Disclaimer

Any resemblance to actual cheats, living or dead, is purely intentional.

Thanks to Merek for the source, and to Skillz for emotional support.  
Special shoutout to "Redacted™" for... something, I guess.
