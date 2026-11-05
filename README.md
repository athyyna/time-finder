# Time Finder

A single-file timezone converter for Singapore, India, UK and US Pacific.
No sign-in, no server, no data leaves your browser.

## Use it

- **GitHub Pages (once enabled):** open the Pages URL, then bookmark it or
  pin the tab in Chrome so it's always one click away while you work in
  Gmail, Calendar or chat.
- **Or locally:** download `index.html` and open it in Chrome, then pin
  the tab or bookmark it.

## What it does

- Live clocks for all four zones.
- Convert a date/time from any of the four zones, with tomorrow/yesterday
  flagged when the date rolls over, and a Daytime / Edge / Night flag
  per zone.
- Best times on that date: the top 3 Singapore-anchored hours, ranked by
  how many zones land in daytime. No hour puts all four in 9–5, because
  Singapore and Pacific are 15–16 hours apart — the winner is usually
  around 5pm Singapore (afternoon India, morning UK, very late night /
  early morning Pacific).
- Copy a paste-ready summary for WhatsApp / email, plus a Discord
  `<t:…:F>` timestamp.
- Pacific is optional: untick "Include US Pacific" to rank just
  SG / India / UK.

UK (GMT ↔ BST) and Pacific (PST ↔ PDT) daylight saving are handled by the
browser's built-in timezone data — there is no hard-coded offset table.
