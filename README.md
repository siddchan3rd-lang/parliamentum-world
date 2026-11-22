# Parliamentum: Seats of Power

Static HTML political strategy game. Multiplayer uses the configured Supabase project.

## Deploy on Vercel

1. Go to [vercel.com/new](https://vercel.com/new)
2. Import this GitHub repository: `siddchan3rd-lang/parliamentum-world`
3. Framework Preset: **Other** (or leave blank)
4. Build Command: leave empty
5. Output Directory: leave empty (or `.`)
6. Install Command: leave empty
7. Deploy

The site is pure static files (`index.html`). No build step required.

## Local play

Open `index.html` in a browser, or serve the folder with any static server.

## Supabase

The game already points at:

`https://wbyjqdwmmtznlobsfhck.supabase.co`

For username/password signup with synthetic `@parliamentum.invalid` emails, disable **Confirm email** under Authentication → Providers → Email in the Supabase dashboard.
