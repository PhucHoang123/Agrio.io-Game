# Agario

## Overview
Agario is a multiplayer game where players control a cell and grow by consuming food and other players. This project was developed as part of CS 3500 at the University of Utah, implementing core game mechanics and a minimalistic yet effective user interface.

## Authors
- **Phuc Hoang**
- **Chanphone Visathip**

## Repository Information
- **GitHub Repository:** [Agario Repository](https://github.com/uofu-cs3500-spring24/assignment-eight-agario-v_tekkkkk)
- **Commit Date:** April 21, 2024, 11:25 PM

## Features
- **Player Mechanics:** Players can consume food and other players to grow.
- **Mass Management:** Ability to spit mass when reaching a specific threshold.
- **Game World Rendering:** Dynamic viewport ensures the player remains at the center of the screen.
- **Minimalist UI Design:** Clean and simple interface for a smooth gameplay experience.

## User Interface and Game Design Decisions
- The welcome page features a clean and simple GUI for ease of use.
- The viewport dynamically adjusts to keep the player's cell at the center.

## Implementation Details
- **Drawing the Scene:**
  - One of the major challenges was rendering the game scene efficiently.
  - The solution involved calculating a boundary based on the player’s position to determine visible elements.
- **Data Handling:**
  - `World` class manages all entities (players, food, etc.).
  - `MainPage.xaml.cs` handles UI rendering and interactions.

## Testing Strategy
- Designed, implemented, and tested each function iteratively.
- Conducted structured testing sessions at the end of each coding session.
- Debugging sessions focused on ensuring new features didn’t break existing functionality.

## Time Expenditures
- **Predicted Time:** 35 hours
- **Actual Time:** 27 hours (excluding tutorial steps)
- Pair Programming: 21 hours
- Debugging: 3 hours

## Consulted Peers
- Discussions with Trenton, Ted, and Shadrach helped resolve implementation challenges.

## Good Software Practices (GSP)
1. **Well-named, Commented, and Short Methods**
   - Used clear method names and inline comments for readability.
2. **Single Responsibility Principle**
   - GUI handling is separated in `MainPage.xaml.cs`, while data management resides in `World` class.

## References
1. Piazza Posts
2. ChatGPT - [ChatGPT](https://chat.openai.com/)
3. Lab 12
4. [Color.FromArgb Method](https://learn.microsoft.com/en-us/dotnet/api/system.drawing.color.fromargb?view=net-8.0)
5. [GraphicsView](https://learn.microsoft.com/en-us/dotnet/maui/user-interface/controls/graphicsview?view=net-maui-8.0)
6. [DrawString](https://learn.microsoft.com/en-us/dotnet/api/system.drawing.graphics.drawstring?view=dotnet-plat-ext-8.0)

## License
This project is copyrighted by CS 3500, Phuc Hoang, and Chanphone Visathip. It may not be copied for use in academic coursework.

