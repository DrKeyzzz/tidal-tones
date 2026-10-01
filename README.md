# Tidal Tones

A note-reading and interval game. Boats sail toward the rocks; name the note (or interval) on each one and the lighthouse guides it home.

**Play:** https://drkeyzzz.github.io/tidal-tones/

- **Welcome screen:** first name, last initial and class code (or "I'm not in a class"), or **Play as guest** (nothing is saved). One sign-in works for the Rhythm Trainer, Scale Quest and Tidal Tones on the same device.
- **Leaderboards:** the student's class and the World board, filtered by mode, difficulty, clef and answer style. Scores are saved in the shared Firebase project (`tidal_scores`).
- **Rules:** [`firestore.rules`](firestore.rules) covers all the games and is identical in every repo. Paste it into Firebase → Firestore Database → Rules → **Publish** whenever it changes.
- To remove a score for now: Firebase console → Firestore Database → `tidal_scores`.
