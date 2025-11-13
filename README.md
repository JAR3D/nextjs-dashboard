
## Next.js Dashboard — Learning Project

A small, component-driven dashboard application built while following the Next.js App Router learning path. The project demonstrates:

- App Router structure (`app/`) with layouts and nested routes
- Client and server components (including interactive UI in `app/ui/`)
- Tailwind CSS for styling
- Google fonts loaded via `next/font/google`
- Basic example pages for a dashboard, invoices, and customers

Good for experimenting with Next.js conventions and practicing layout patterns.

Getting started
---------------

Install dependencies (this repository uses `pnpm` in the course, but `npm` or `yarn` will also work):

```bash
cd nextjs-dashboard
pnpm install
```

Run the development server:

```bash
pnpm dev
# open http://localhost:3000
```

Helpful commands
----------------

- `pnpm dev`: run Dev server
- `pnpm build`: build for production
- `pnpm start`: start built app

Project structure (high level)
------------------------------

- `app/` — App Router pages and layouts
	- `app/page.tsx` — Landing page
	- `app/dashboard/` — Dashboard area with nested pages
- `app/ui/` — Reusable UI components (logo, nav, buttons, etc.)
- `app/lib/` — small helpers and placeholder data

Contributing
------------

This repository is intended as an educational resource. Feel free to:

- Add small feature demos (charts, forms, authentication stubs)
- Improve components and accessibility
- Open an issue or create a PR with suggested changes

License
-------

This project is a personal/learning project derived from the Next.js learn examples. Use it freely for learning and experimentation.
