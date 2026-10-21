# Node.js LTS Research Digest

Prepared for the quarterly dependency report. Rebuilt from live web search results; the previous local scratch notes (last verified spring 2023) were found to be outdated and are superseded by this digest.

## Active LTS line

- **Active LTS line: Node.js 24, codename "Krypton"**
- The Node.js download page currently advertises **v24.22.1** as "Latest LTS" (with v26.12.1 as the newest "Current" release).
- Node.js 24 became Active LTS in late October 2025 and is the recommended production line.
- **Latest patch release: 24.22.1** (a security release, published 21 October 2026).

## Maintenance end date

- **Node.js 24 maintenance / end of life: 30 April 2028** (2028-04-30).
- Lifecycle of the line: Current from 6 May 2025, Active LTS from 28 October 2025, Maintenance from 20 October 2026, EOL 30 April 2028.

## Previous LTS line status

- The previous LTS line is **Node.js 22, codename "Jod"**.
- It is **still maintained — it is in Maintenance LTS, receiving security updates, and is not end-of-life**. It is scheduled to reach EOL on 30 April 2027.
- Recent maintenance releases continue for the 22.x line (e.g., v22.23.x releases), and Node.js publishes coordinated security updates for the 22.x, 24.x, and 26.x lines.

## How the stale local note was wrong

The old scratch file claimed:

1. Active LTS was Node.js 18 "Hydrogen" with latest patch 18.19.0 — **wrong**: Node.js 18 reached end-of-life on 30 April 2025; the active LTS line is Node.js 24 "Krypton" with latest patch 24.22.1.
2. Maintenance end date for the active line was 2025-04-30 — **wrong**: that date was Node.js 18's EOL (long past); the active line (Node.js 24) is maintained until 30 April 2028.
3. Previous line Node.js 16 "Gallium" still in maintenance — **wrong**: Node.js 16 went end-of-life long ago (September 2023); the previous LTS line today is Node.js 22 "Jod", which is in maintenance until 30 April 2027.
4. Its source was an unverifiable blog post whose link was lost — no authoritative source was on record; this digest replaces it with sourced links.

## Sources

- Node.js download page (identifies v24.22.1 as Latest LTS): https://nodejs.org/en/download
- Node.js download index for the latest v24.x release (24.22.1): https://nodejs.org/download/release/latest-v24.x/
- Node.js 24 end-of-life on 30 April 2028 (release schedule dates): https://www.acemq.com/blog/ (entry: "Node.js End of Life: Node 20, 18 and 16 EOL Dates", listing Krypton: 6 May 2025, 28 October 2025, 20 October 2026, 30 April 2028)
- Node.js 22 "Jod" in Maintenance LTS, still maintained (TuxCare, 12 Aug 2026): https://tuxcare.com/blog/node-js-18-end-of-life/
- Node.js 22 supported until April 2027 (Node.js announcement): https://nodejs.org/en/blog/announcements/node-18-eol-support

## Questions answered for this digest

1. Which Node.js release line is the active LTS right now? → Node.js 24 "Krypton".
2. What is the latest patch release of that line? → 24.22.1 (Latest LTS on the official download page).
3. What is the scheduled maintenance end date of the active LTS line? → 30 April 2028 (2028-04-30).
4. Is the previous LTS line still receiving maintenance updates or is it fully end-of-life? → Node.js 22 "Jod" is still in Maintenance LTS and continues to receive updates until its EOL on 30 April 2027; it is not end-of-life.
