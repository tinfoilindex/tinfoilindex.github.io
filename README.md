# Tinfoil Index

How paranoid is the internet today? One number a day, from 0 to 100. 50 is a normal day.

**The page: https://tinfoilindex.github.io**

Daily readings: [Telegram, English](https://t.me/tinfoilindex), [Telegram, Russian](https://t.me/indexfolgi), [X](https://x.com/tinfoilindex).

## How the number is made

1. Every day we count how many people read Wikipedia's articles on 26 conspiracy theories. English and Russian Wikipedia each have their own basket and their own index.
2. A theory's readers are taken as a share of all Wikipedia reading that day, and compared with that theory's own past year. A theory whose article moved to a new title keeps the readers of the old ones.
3. Each day is set against what is usual for that day of the week.
4. The index is the same comparison for the whole basket. 50 is a normal day, 73 is unusual, 88 is rare.

It measures attention, not belief. Reading about lizard people does not make you one.

## What is in this repository

- `index.html`: the page.
- `assets/fonts/`: the page's typeface, JetBrains Mono, with its licence.
- `out/latest.json`: the latest reading, with every theory's own reading.
- `out/history_en.csv` and `out/history_ru.csv`: every daily reading since December 2015.

The files are updated automatically after each reading. A reading appears here once it has been posted to its Telegram channel.

Data: Wikimedia pageviews, CC0. Parody. Not financial advice.
