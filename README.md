# NEONVERSE AI

Responsive AI character chat starter (Next.js App Router, Supabase, server-side AI endpoint).

## Deploy from iPad
1. Download and unzip this project.
2. Create a GitHub repository in Safari.
3. Upload the project files/folders from the ZIP to GitHub (or use GitHub's web upload).
4. Import the repository in Vercel.
5. In Vercel Settings → Environment Variables, add:
   - `AI_API_KEY` — your provider key
   - `AI_BASE_URL` — optional OpenAI-compatible endpoint (defaults to OpenAI)
   - `AI_MODEL` — optional model name (defaults to `gpt-4o-mini`)
   - `NEXT_PUBLIC_SUPABASE_URL`
   - `NEXT_PUBLIC_SUPABASE_ANON_KEY`
   - `SUPABASE_SERVICE_ROLE_KEY` — server only, never expose
6. Run the SQL in `supabase/schema.sql` in the Supabase SQL editor.
7. Deploy.

The UI has no age-verification gate. The mature-content preference is a character/chat setting, but the server prompt does not permit explicit sexual content; use appropriate safeguards for any production adult-content implementation.

## Local setup
`npm install` then `npm run dev`.
