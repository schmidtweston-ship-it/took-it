# Took It

One big tap when you take your pill. Optionally snap a photo. Family (or you) can open **Today** and see that it was taken. Private — everything stays in this browser’s localStorage. No accounts, no cloud.

## Use

1. Open `index.html` (or the GitHub Pages URL) on the phone that tracks the dose.
2. Tap **Took it**.
3. **Snap** a quick photo of the bottle/hand, pick from **Photo library**, or **Save without photo**.
4. Optional short note (e.g. “morning”).
5. Later, tap **Today** to confirm it was logged.

## Notes

- Photos are compressed before save. If storage is tight, older photos are dropped first; times still remain.
- Clear entries older than 30 days from **All days** if the list grows.
- Data never leaves the device. Clearing site data in the browser will erase the log.

## Local

```bash
npx --yes serve .
```

Equal always.
