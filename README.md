# Kopi Order

A phone-friendly web app for taking group orders of Singapore kopitiam drinks
(Kopi, Teh, Cham) and producing a summary to read out to the waiter.

Everything is in one file, `index.html`: no build step, no libraries.
The current order is saved in the browser, so a refresh doesn't lose it.

## Use it

- **On a computer:** double-click `index.html`.
- **Online:** upload `index.html` to any static host (e.g. Cloudflare Pages,
  "Upload assets"), or connect this repository to Cloudflare Pages with no
  build command and the output directory left as `/`.

## Features

- Drink builder: drink, milk (condensed / O / C), strength (Gao / Po / Di Lo),
  sweetness (Siew Dai / Ga Dai / Kosong), Peng, Da Bao, extras (Tarik, Halia, Gu You).
- Names built in kopitiam order, e.g. `Kopi C Di Lo Siew Dai Peng Da Bao`,
  with a plain-English description.
- Kosong is only allowed with O or C.
- Order list with names, quantities, edit and delete.
- Waiter summary grouped by drink (Dine-in and Da Bao separately) or by person,
  with Copy, Share and a big-text "Show to waiter" view.
