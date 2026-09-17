# NoteShareHub — Vercel + Firebase

Vercel hosts the website. Firebase provides Authentication, Firestore and Storage.

## Deploy
1. Upload this folder to GitHub.
2. Import the GitHub repository into Vercel.
3. Use Framework Preset: Other.
4. Deploy.

## Firebase setup
1. Create a Firebase project.
2. Enable Authentication > Email/Password.
3. Create Firestore Database.
4. Create/enable Firebase Storage.
5. Add a Firebase Web App.
6. Copy its config into `public/app.js`, replacing the `YOUR_...` placeholders.
7. Deploy the rules with Firebase CLI:
   firebase login
   firebase use YOUR_PROJECT_ID
   firebase deploy --only firestore:rules,storage

No Netlify or Supabase code is included.
