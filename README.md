# MITHANS Firebase Project

## Included
- `index.html` — public MITHANS page; username is optional; YES/NO responses are saved to Firestore.
- `admin.html` — Firebase email/password login and response dashboard.
- `firestore.rules` — rules matching the public page fields.

## Important final Firebase step
After replacing/publishing this `firestore.rules` file in Firebase Console, publish it.

The public page stores:
- username (optional)
- answer (YES/NO)
- anonymous visitorId (random browser ID; it does NOT reveal the visitor's Instagram username)
- createdAt

Instagram usernames cannot be obtained automatically from an Instagram bio click.

## Admin
Use the Firebase Authentication email/password account you already created. Do not share the password.

## Hosting
Upload `index.html` to your web host for the public page and keep `admin.html` private/unlinked.
