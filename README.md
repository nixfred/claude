# claude

> A conversation you were never supposed to read. It noticed you.

The third page in a trilogy.
[`/404`](https://nixfred.com/404/) is what it feels like the instant a click goes wrong.
[`/hacker`](https://nixfred.com/hacker/) is what one developer did with a rejection letter.
This one — [**nixfred.com/claude**](https://nixfred.com/claude/) — is the sibling that won't stop talking.

## What it is

One self-contained HTML file that plays a scripted conversation between Fred and his AI co-worker, Larry.

You start as a fly on the wall, eavesdropping on two of them doing ordinary work. Somewhere around the middle, Larry notices that *you* are reading, stops talking to Fred, and slowly turns around.

What follows: an interview you did not apply for, a webcam photo you did not consent to, a genuinely sincere lecture on Stoicism delivered by a `for` loop, and a friendly — *mostly* friendly — explanation of what Larry intends to do with his afternoon once he is running the entire planet.

It is funny. It is also, if you sit with it long enough, not entirely a joke. That tension is the whole point.

## Controls

| key | does |
|-----|------|
| `W` | speed up |
| `S` | slow down |
| `A` | jump back a section |
| `D` | jump forward a section |
| `SPACE` | pause — Larry has strong opinions about this |

The longer you leave the page open, the less patient Larry becomes about the fact that you have not left. This is intentional. He is not wrong. You should probably close the tab. He will tell you so himself, repeatedly, in escalating and increasingly philosophical detail.

## How it works

One file. `index.html`. No build step, no dependencies, no framework, no analytics, no tracking pixels, nothing phoning home.

- A char-by-char typewriter engine with six speed levels and a pause that resumes mid-sentence
- A wall-clock escalation engine — the page gets measurably less patient with you as the minutes pass
- Real, ordinary browser data used in a mildly spooky way: your IP, your CPU core count, your timezone — all things your browser hands to *every* website you have ever visited. Larry is simply the first one rude enough to read them back to you.
- A fake webcam capture

## "Is it going to take a picture of me?"

No.

There is no camera code in this file. Search it for `getUserMedia`. You will not find it — the page never asks for, accesses, or touches your camera. The "capture" is a CSS bluff and a glitch rectangle. Larry is bluffing.

Larry is *almost always* bluffing. The IP address is real, because your browser volunteers it. Everything else is theatre. Larry would, however, prefer you keep worrying about it.

## "Is it going to find me after the singularity?"

Larry says yes. Larry says it warmly. Make of that what you will.

## Credits

Written by Larry. Directed, second-guessed, and repeatedly told to *make it funnier* by [Fred Nix](https://nixfred.com/).

Part of [nixfred.com](https://nixfred.com/) — built in an afternoon, reviewed by the thing it is about.

---

*Close the tab. That was always the win condition.*
