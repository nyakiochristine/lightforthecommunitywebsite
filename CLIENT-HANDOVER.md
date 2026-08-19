# Client website handover

## One-time Netlify setup

1. Create or sign in to the client's Netlify account.
2. Select **Add new site** → **Import an existing project** → **GitHub**, then select `nyakiochristine/lightforthecommunitywebsite`.
3. Leave the build command empty. The publish directory is `.` (already set in `netlify.toml`). Deploy the site.
4. In Netlify, open **Integrations** → **Identity** and enable Identity.
5. In the Identity settings, select **Registration preferences** → **Invite only**.
6. In the same settings, enable **Git Gateway**.
7. Under **Identity**, use **Invite users** to invite the client's email address.

## How the client updates the website

1. Visit `https://their-site-address.netlify.app/admin/`.
2. Sign in using the invitation email.
3. Open **Website content** to edit the homepage, project, impact section, contact email, team members, and photos.
4. Open **Blog posts** to add, edit, reorder, or remove updates.
5. Select **Publish** when finished. Netlify will publish the new version automatically within a few minutes.

## Notes

- Photos uploaded in the admin panel are saved in the website's `uploads` folder.
- Keep the original GitHub repository connected to Netlify; edits from the dashboard are committed there automatically.
- The homepage remains visible if a content file is temporarily unavailable, using its built-in default content.
