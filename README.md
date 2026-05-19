# 🐦 Flappy Bird — Power Edition

A feature-rich Flappy Bird game built with vanilla HTML5 Canvas and JavaScript.

**Features:**
- ❤️ 3 Lives system
- 🔥 Smash Power — destroys pipes for 10 seconds
- 🛡️ Guard Shield — absorbs one hit without losing a life
- ⚔️ Duel Mode — two players on one screen!

---

## 🚀 How to Deploy

Since this is a single HTML file (no server needed), deployment is extremely simple. Pick one:

### Option 1: GitHub Pages (Free, Easiest)

1. Go to **[github.com](https://github.com)** and create a free account
2. Click **New Repository** → name it `flappybird`
3. Upload the `index.html` file to the repository
4. Go to **Settings → Pages**
5. Under "Source", select **main** branch and click **Save**
6. Your game is live at: `https://yourusername.github.io/flappybird/`

### Option 2: Netlify (Free, Drag & Drop)

1. Go to **[netlify.com](https://netlify.com)** and sign up
2. Drag the entire `flappybird` folder onto the Netlify dashboard
3. Done! You'll get a URL like `https://something.netlify.app`

### Option 3: Vercel (Free)

1. Go to **[vercel.com](https://vercel.com)** and sign up
2. Click **New Project** → Upload the `flappybird` folder
3. Deploy → you'll get a URL like `https://flappybird.vercel.app`

### Option 4: Replit (Free, Browser-based)

1. Go to **[replit.com](https://replit.com)** and create an account
2. Click **Create Repl** → Choose "HTML, CSS, JS"
3. Paste the contents of `index.html`
4. Click **Run** — it's live immediately with a shareable URL

### Option 5: Run Locally (No Internet Needed)

Just double-click `index.html` in File Explorer. Chrome/Firefox/Edge will open it directly.

---

## 🎮 Controls

| Mode | Player | Keyboard | Mobile |
|------|--------|----------|--------|
| Single | You | Space / W / ↑ / ↓ / Click | Tap anywhere |
| Duel | P1 (red) | W or Space | Tap left half |
| Duel | P2 (blue) | ↑ Arrow | Tap right half |

---

## ⚙️ Customization

Open `index.html` in any text editor. Near the top you'll find:

```js
const GRAVITY=0.32, FLAP_V=-6.8, PIPE_W=58, PIPE_GAP=205, PIPE_SPEED=1.8;
```

- **GRAVITY** — lower = floatier (try 0.25 for easy mode)
- **PIPE_GAP** — higher = more room (try 230 for easy mode)
- **PIPE_SPEED** — lower = slower pipes (try 1.5 for easy mode)
