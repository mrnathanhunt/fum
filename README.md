# Fuck You Money ($FUM)

Free static launch page with countdown.

Live source: https://github.com/mrnathanhunt/fum
Telegram: https://t.me/+4mJosHGxtcRlN2Q8

## Session archive (1 Sep 2026)

Full Grok chat dump — scripts, captions, Imagine prompts, video list:

- [docs/SESSION_2026-09-01.md](docs/SESSION_2026-09-01.md)
- [docs/IMAGINE_PROMPTS.md](docs/IMAGINE_PROMPTS.md)
- Community landing notes: [community/README.md](community/README.md)

Root `index.html` is still the countdown launch page. Do not replace it with the community landing unless you mean to kill the timer.

## Edit launch time

Open `index.html` and change one line:

```js
const LAUNCH_ISO = "2026-09-04T20:00:00Z";
```

After launch, fill:

```js
const PUMP_URL = "https://pump.fun/coin/...";
const CA = "YourContractAddressHere";
const TELEGRAM = "https://t.me/+4mJosHGxtcRlN2Q8";
```

## Free hosting — GitHub Pages

1. Open https://github.com/mrnathanhunt/fum/settings/pages
2. Source: Deploy from a branch
3. Branch: `main` / folder `/ (root)`
4. Save. Site will be:
   https://mrnathanhunt.github.io/fum/

## Even faster (no settings)

Drag the folder onto https://app.netlify.com/drop
