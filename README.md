# Email Signup

A minimal landing page with an email signup form, wired directly to Supabase.

## Stack
- Frontend: plain HTML/CSS/JS, Supabase JS client via CDN
- Backend: Supabase Postgres table `subscribers`

## How it works
When someone submits the form, their email is inserted into the `subscribers` table in Supabase project `koctawglvhoqefwnjzhq`.

Row Level Security is enabled with an **insert-only** public policy — anyone can submit an email, but no one can read the list using the public key. View signups in the Supabase dashboard (Table Editor → subscribers).

## Run it
Open `index.html` directly, or it's live via GitHub Pages.
