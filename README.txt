THE TABLETOP LEAGUE — SHARED VERSION

This site is connected to your Supabase project and uses its public publishable key.
The publishable key is intended for browser use. Never put a Supabase secret/service_role key in this folder.

To publish with Vercel:
1. Create a GitHub repository (for example, tabletop-league).
2. Upload index.html to the repository root.
3. In Vercel, choose Add New -> Project and import that repository.
4. Keep the default framework preset as Other and the root directory as ./ .
5. Deploy. Vercel will provide a public website URL to share.

This build assumes the Supabase tables and anonymous-access policies from the setup steps already exist, and that Realtime publication includes games, matches, and match_scores.

IMPORTANT: The current database policies allow anyone with the site URL and public key to read, insert, update, or delete league records. This is intentionally open as requested, but anyone who discovers the link can alter the data. Keep regular JSON backups.
