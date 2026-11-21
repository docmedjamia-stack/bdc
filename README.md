# Tableau de bord · Assistant IA (AI BDC)

Dealer dashboard for the AI sales assistant: clients to call back, appointments, conversations and results.

- Live: https://docmedjamia-stack.github.io/bdc/
- Single static page (`index.html`), hosted on GitHub Pages.
- Data comes from Supabase (`ai-bdc-quebec`). The key in the page is the public "publishable" key; every row is protected by login and row-level security, so a visitor without an account linked to a dealer sees nothing.
- Do not commit secrets (service-role keys, API keys, passwords) to this repository: it is public.
