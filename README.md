# ⚽ Bruno 8 — A Penalty Shooter

A single-file HTML penalty shootout game starring Bruno Fernandes. A bouncing
horizontal meter decides the direction of your shot — click when the indicator
is in the goal and hope the keeper guesses wrong.

## 🎮 How to Play

1. Click **PLAY** on the title screen
2. Watch the **SHOT DIRECTION** meter sweep left and right
3. Click while the indicator is inside the goal to take the penalty
4. Click again to reset and take the next one
5. Score as many penalties as you can — the keeper is getting better at guessing

## 🏆 Scoring

- **GOAL!** — the keeper went the other way
- **SAVED!** — the keeper guessed right (50/50 on anything down the middle)
- **MISS!** — you missed the goal completely
- **★ STREAK** — consecutive goals, with a best-streak counter

## 👕 Secret

There is a **8** on Bruno's shirt. If you click it... things get interesting.
Click it three times and see what happens. Then keep clicking.

## 🌐 Play Online

👉 **[https://nimblecozmo.github.io/penalty-fc/](https://nimblecozmo.github.io/penalty-fc/)**

## 📁 Local Play

No build step, no dependencies — it is one HTML file:

```bash
# just open it
xdg-open index.html

# or serve it
python3 -m http.server 8000
# then visit http://localhost:8000
```

## 🛠️ Built With

Plain HTML, CSS and JavaScript in a single `index.html`. Canvas 2D rendering,
procedurally generated sound effects (no audio files), no external assets.
