# Family RV Rental Manager

Mobile-friendly starter app for 20 campers and 4 towing trucks.

## Run locally

Install Node.js 20 or newer, then run:

```bash
npm install
npm run dev
```

Open the local URL printed by Vite. To make a production build, run `npm run build`.

## Features

- 20 camper profiles (bumper pull and fifth wheel), VIN, license plate, notes and small photos
- 4 towing truck profiles
- Bookings with truck assignment and conflict checking
- Month-view rental calendar
- Departure and return checklists per booking
- Responsive layout for mobile devices
- JSON data export

## Important limitations

This is a **local-only prototype**. Data is saved in the browser's localStorage, not shared across family devices. Clearing browser storage will remove records. Uploaded images should be under 1.2 MB because browser storage is limited. The role selector is a UI demonstration only; **it is not authentication or secure access control**. Do not put sensitive customer data in this prototype. Before real family use, add a database, authenticated users, server-enforced permissions, cloud image storage, and backup/restore. The app is a mobile-friendly website, not yet a native app-store package.

## GitHub upload

Extract the ZIP. Upload the files and `src` directory to your repository's root, or use Git locally. Do not upload the ZIP itself as the application source.
