LEVEL UP — FAMILY PROFILES WITH SHARED LOGIN PAGE

Files:
- login.html: common entry page for all five family profiles. Kids select their profile without a PIN; parents enter a PIN.
- player.html: child/player page. Each child has separate XP, submissions, history, and daily game minutes.
- parent.html: parent dashboard. Both parents can manage all three kids and shared family rules.

First-time demo PINs:
- Parent 1: 1986
- Parent 2: 1986

Setup:
1. Extract the ZIP to one folder.
2. Open login.html to sign in.
3. Choose a kid profile to enter without a PIN, or choose a parent profile and enter a parent PIN to rename all profiles. Parent PINs can be changed in the parent dashboard.
4. Both parents can manage all three kids. Task definitions and game-time rules are shared; each child's XP, task submissions, history, and daily game minutes are separate.

Important limitations:
- This is a local demo. Data is stored in localStorage in the browser, so it is not automatically shared across different devices or browser profiles.
- The parent PIN screen is a convenience gate, not strong security. Kids do not require PINs. Anyone with access to the browser storage or source files may be able to bypass it.
- For reliable cross-device sync and real account security, this would need hosting with a backend/database and proper authentication.

NEW LEVEL-UP FEATURES:
- Titles change automatically as lifetime XP levels increase: Starter, Adventurer, Elite, Grandmaster, Legend.
- Pets unlock at Levels 1, 3, 5, 7, 10, and 15. Kids can choose from their unlocked pets.
- Every new level gives a one-time 20 XP bonus. Level progress uses lifetime XP, so spending XP in the reward shop does not lower a child's level.
- Parent-approved quests add lifetime XP and can trigger level-up bonuses. Positive parent XP adjustments also count toward lifetime XP.

FAMILY SHOWCASE UPDATE:
- Added a family showcase that displays each child's level, title, chosen pet, and lifetime XP.
- The View profile button switches to that child's account on this shared browser/device. This is a family-only local demo, not separate online accounts.
