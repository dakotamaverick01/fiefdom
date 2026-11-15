# Kickoff prompt

Paste everything below the line into a fresh Claude session pointed at this repo.

---

You're building a browser game with me. I'm a hobbyist with limited programming experience, so explain any technical term the first time you use it, keep your explanations short and plain, and make the game runnable by opening a file in a browser.

## The idea

I'm a fan of Age of Empires. I want a 14th-century medieval manor and fiefdom builder where I play a noble on the English northern border with Scotland, building up a manor, defending it, and eventually rising through the ranks of nobility.

## Fixed pillars (don't change these without asking)

1. **Setting:** Northumberland, England, roughly 1300 to 1346. Use a real lord, a real manor, and real terrain and geography (Cheviots, river valleys, the Tweed and Coquet, border country). Events and politics can be fictionalized and simplified. Don't spend effort on deep historical research. Where you invent something, label it as invented in a short in-game or README note.
2. **No plague.** The Black Death is out of scope. The pressure comes from politics, economics, and war: Scottish raids, feudal duties and taxes, the king's demands, rival nobles, harvests.
3. **Isometric 2D view** like Age of Empires: diamond tiles, buildings and walls with visible height. Draw all art in code (shapes and colors), no external art needed. Stylized is fine.
4. **Real-time with pause**, in the spirit of Banished and Northgard. Time runs slowly, I can pause and build while paused, and there are speed controls. A calendar of seasons drives events.
5. **Placement matters.** Where I put walls, towers, gates, fields, mill, granary, and the hall must have real consequences: villager walking distance, raiders choosing the easiest path in, fire spreading between wooden buildings, siege defense. The player should be able to customize the defenses, not just upgrade a castle icon.
6. **Stage 1 is the manor only.** One small stretch of land, villagers working, seasons turning, building and walls, and Scottish raids that test my layout. Later stages (not now): a realm map and court where I claim neighboring lands and petition for rank, then ranks, rivals, levies, and campaigns. Design stage 1 so those can be added later without a rewrite.

## What's up to you

Everything else: the name of the game, the economy and resources, the villager and building types, how raids and sieges play out, what wins or loses a season, the UI, the pacing, the difficulty, and any ideas that make this more fun. Use real judgment. I'd like to see what you'd design if I got out of your way.

## How to work

- Plain web files only: an `index.html` plus JavaScript files in a folder. No build tools, no installs, no server needed.
- Work in small steps, run what you build, and test it before telling me it works. Commit to git often with clear messages.
- Keep a short `README.md` that says how to open and play the game, what's invented vs. historical, and what the controls are.
- Keep a `DESIGN.md` of the gameplay decisions you made and why, plus a short list of ideas for later stages.
- Don't ask me many questions. Make reasonable calls and note them in `DESIGN.md`. Ask only if something would be expensive to undo.
- Aim for something genuinely playable and fun for 20 minutes by the end of stage 1, rather than a lot of half-built features.
- This is a personal side project. Keep it free of any reference to my job or employer anywhere in the code, text, or commits.
