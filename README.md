# VanillaJS Firebase Firestore integration
Dummy integration of Firebase Firestore Database inserts in Vanilla JS. 
Integrate these things into your project by following steps below.
## Scripts on Frontend
Add these scripts from bottom of index.html as follows:
- include **7.1.0/firebase-app.js** and **7.1.0/firebase-firestore.js**,
- put your config into **firebaseConfig** and init,
- script to perform dummy insert with **messagesRef.add({...})**.
## Rights on Backend
Change **Firestore Database** > **Rules** from
```
#5  allow read, write: if false;
```
to
```
#5  allow read, write;
```
to allow performing inserts from public.