# Parliamentum: Seats of Power

Static HTML political strategy game with multiplayer (Supabase).

**Repository:** https://github.com/siddchan3rd-lang/parliamentum-world

## Deploy on Vercel yourself

1. Open [vercel.com/new](https://vercel.com/new)
2. Import **`siddchan3rd-lang/parliamentum-world`**
3. Framework Preset: **Other**
4. Leave **Build Command**, **Install Command**, and **Output Directory** empty
5. Click **Deploy**

No build step is required.

## Files

- `index.html` — main game entry (must contain the full game or load `game1.js`–`game3.js`)
- `vercel.json` — static hosting headers

If the large game script is still missing after clone, replace `index.html` with your original single-file game (the one you shared as the attachment). Keep `vercel.json`.

## Supabase

Configured for:

`https://wbyjqdwmmtznlobsfhck.supabase.co`

For username-only signup (`user@parliamentum.invalid`), disable **Confirm email** in Supabase → Authentication → Providers → Email.
