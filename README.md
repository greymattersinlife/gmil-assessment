# GMIL Leadership Assessment — GitHub Pages + Supabase

Production frontend for the Entrepreneurial Leadership & Independent Career Readiness Profile.

- `/` — participant assessment
- `/admin/` — assessor/admin console
- Frontend: GitHub Pages
- Backend/data/scoring/admin APIs: Supabase Edge Functions + PostgreSQL

The participant frontend does not include assessor interpretation content. Assessor-only interpretation is returned only from the protected Supabase admin API after login.


## Production links
- Assessee: https://greymattersinlife.github.io/gmil-assessment/
- Assessor/Admin: https://greymattersinlife.github.io/gmil-assessment/admin/
- Direct admin fallback: https://greymattersinlife.github.io/gmil-assessment/admin.html
