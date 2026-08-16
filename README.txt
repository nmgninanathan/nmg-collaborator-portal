NATHAN MUSIC GROUP (NMG) — CONNECTED COLLABORATOR PORTAL

This portal is configured for the NMG Supabase project.

Included:
- Secure email/password sign-in through Supabase Auth
- Approved-collaborator check
- NMG information editing
- Artist bio/profile-photo editing
- Artist creation
- Release/upcoming-release creation with clickable links
- Gallery photo/video uploads

IMPORTANT:
- The browser uses the Supabase publishable key only.
- Never put a Supabase secret/service-role key or database password in this file.
- Only users in public.collaborators with active=true can edit the protected tables.
- The public website still needs to be connected to the same Supabase tables before portal edits automatically appear there.

HOSTING:
Upload admin.html to the private portal location. A GitHub Pages URL can be used, but GitHub itself does not provide the login; Supabase Auth does.
