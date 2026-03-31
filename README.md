# Number Tap Guessing Game

A simple **SwiftUI** game for iOS/iPadOS where the player tries to reach a hidden target number by tapping a button. The game includes a timer, a start/reset feature, and multiple screens like leaderboard and credits.  

---

## Features

- **Tap-to-score gameplay**: Each tap adds 1 to your score.  
- **Hidden target number**: Try to match or get close to the target number.  
- **Timer pressure**: Complete the challenge before the timer runs out.  
- **Start / Reset button**: Start the game or reset it mid-game.  
- **Leaderboard and credits screens**: Navigate easily between screens.  
- **Fully built in SwiftUI**: Works on iPads and iPhones.  

---

## Screens

1. **Menu Screen**
   - Shows the game title and instructions.  
   - Buttons to start the game, view leaderboard, or credits.  

2. **Game Screen**
   - Shows current score, timer, and message feedback.  
   - Tap button to increment score.  
   - Start/Reset button allows starting or restarting the game.  
   - Finish button ends the game immediately.  

3. **Leaderboard Screen**
   - Placeholder leaderboard showing high scores (currently empty).  

4. **Credits Screen**
   - Displays `Made by @mightbeivan`.  

---

## How to Play

1. Open the app.  
2. Tap **Start Game** to begin.  
3. Tap the **"Tap Me!"** button repeatedly to try to reach the hidden target number.  
4. Watch the timer! You must reach the target before time runs out.  
5. Finish the game manually or wait for the timer.  
6. See feedback on your score and try again.  

---

## Installation / Run

1. Open **Xcode** on your Mac or iPad (with Swift Playgrounds / Xcode Cloud).  
2. Create a new **SwiftUI project**.  
3. Copy the `ContentView.swift` code into your project.  
4. Run on **iPad** or **iPhone simulator**.  

---

## Code Highlights

- `@State` variables manage the game logic: `score`, `timeLeft`, `gameActive`, `targetNumber`.  
- Timer updates the game every second and ends the game when time reaches 0.  
- **Start / Reset button** toggles game state.  
- Multiple screens implemented using `switch currentScreen`.  

---

## Links

- [GitHub](https://github.com/MightbeIvan)  
- [Instagram](https://www.instagram.com/mightbeivan?igsh=OXFkeWxodGc5bm5o&utm_source=qr-insta)  
- [TikTok](https://www.tiktok.com/@mightbeivan0?_t=ZT-90kSet3oo6x&_r=1)  

---

## License

This project is free to use and modify.  
Made by [@mightbeivan](https://github.com/MightbeIvan-).  
