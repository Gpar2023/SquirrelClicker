# Squirrel Clicker

An addictive, high-performance incremental game where you build a squirrel empire, recruit powerful soldiers, and ascend to god-like status.

![Game Header](readmeImg/Screenshot%202026-05-02%20122904.png)

## About the Game
Squirrel Clicker is more than just a clicking game. It features a deep progression system, visual army management, and high-performance Canvas rendering that allows you to see hundreds of your recruits orbiting your central squirrel in real-time.

### Key Features:
*   **Active & Passive Income:** Click the central squirrel for tokens or recruit soldiers to do the work for you.
*   **Visual Army System:** Watch your army grow! The right sidebar (Armies) displays your soldiers on dynamic, scrollable canvases.
*   **Leveling Mechanics:** Don't just buy more; make them better. Upgrade your **Chronisters** and **Chumtoads** to increase their individual TPS (Tokens Per Second).
*   **Golden Squirrel Frenzy:** Catch the rare Golden Squirrel to trigger a **77-second Frenzy** with 7x production!
*   **Ascension System:** Reach the 1 Trillion token milestone to reset for **Golden Acorns**, providing permanent prestige boosts and unlocking the Ascension Shop.
*   **Offline Earnings:** Buy upgrades in the Ascension Shop to keep earning tokens even when the game is closed.
*   **Achievements:** 10+ unique achievements to hunt for, from "Token Novice" to the elusive "Hyperactive" clicking challenge.

---

## How to Play
1.  **Click the Squirrel:** Earn your first few tokens manually.
2.  **Visit the Shop:** Buy your first **Chronister** to start earning tokens automatically.
3.  **Manage your Army:** Open the Army tab on the right to see your recruits. Click on a soldier in the army list to **Level them up**.
4.  **Boost:** Use your tokens to buy temporary x2 or x5 multipliers.
5.  **Ascend:** Once you become a trillionaire, use the **✨ Ascend** button in the shop to gain Golden Acorns and start over with a massive permanent boost.

---

## Controls
*   **Left Click:** Interact with everything.
*   **Mouse Wheel:** Zoom in/out on the main game view.
*   **Click & Drag (Army Bar):** Scroll through your massive lines of soldiers.
*   **Right Click:** (Disabled to prevent accidental menus during fast clicking).

---

## Technical Details
*   **Engine:** Pure Vanilla JavaScript / HTML5 Canvas.
*   **Persistence:** Your progress is automatically saved to `localStorage` every 5 seconds.
*   **Performance:** Uses a custom LoD (Level of Detail) and "Snapped Rendering" system to maintain 60FPS even with hundreds of entities on screen.
