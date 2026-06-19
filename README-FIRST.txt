Bags League Test Lab

Purpose
- This is a separate testing copy of the Bags League app.
- It uses the Firestore document leagues/bags-league-test-lab.
- It uses separate phone backup keys beginning with bags_test_lab.
- It does not read or write the live leagues/bags-league-2026 record.

Recommended publishing
1. Create a separate GitHub repository named Bags-League-Test.
2. Upload all files from this folder.
3. Enable GitHub Pages from the main branch and /root folder.
4. Open the test URL with ?admin=score and sign in with the existing administrator account.

Testing playoffs
1. Sign in and open Page 2: Admin Tools.
2. Under Playoff Setup, select Load Demo Standings + Playoffs.
3. Confirm the warning.
4. The app returns to Page 1 and opens the Playoffs tab.
5. Experiment freely; only the Test Lab scores and brackets are changed.

Safety
- The purple TEST LAB banner must always be visible in this version.
- Never overwrite the live Bags-League repository with this test build.
- The live app remains in the separate stable-v1 snapshot.
