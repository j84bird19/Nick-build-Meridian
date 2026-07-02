NICK MERIDIAN — REBUILD V1 TESTING BUILD

Purpose
- Clean, simpler rebuild for Nick's hourly/flat-rate service work.
- Uses a separate storage key and IndexedDB database from Legacy Cut Meridian and the older Nick app.

Included
- Schedule: calendar, agenda, New Job, New Event, reminders, and time card.
- Clients: directory, contact details, totals, job history, and optional manual invoices.
- Supplies: inventory, cost per unit, physical counts, separate usage logging, cost-used calculation, remaining quantity, and receipt folders.
- Banking: accounts/register, trackers, categories, and banking receipts.
- Offline PWA installation, autosave, backup, and restore foundation.

Intentionally removed/simplified
- No Studio, Gallery, Mockup Builder, Product Inventory, Legacy Cut New Project form, daily tasks, or daily notes.
- Saving a job does not create an invoice.
- Supply usage does not attach to jobs, clients, or invoices.
- Invoices are optional, manual, and labor-only for this first testing build.

GitHub Pages
Upload all files from this ZIP to the ROOT of a new repository or testing branch, then enable GitHub Pages from that branch / root.

Data safety
The app stores data locally on each phone/browser. Updating GitHub files should not erase data as long as the site URL and storage key remain unchanged. Use Backup before major updates.
