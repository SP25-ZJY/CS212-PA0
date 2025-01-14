# Design

My adventure game is inspired by **Alice in the Wonderland** and **Game of Thrones**.

1. Output the prologue of the game:  
   `"You have just tumbled through the Rabbit Hole into Westerland,`<br>` a chaotic kingdom ruled by Cersei the Mad Queen...."`

2. Ask the player to input their name.

3. Ask them how tall they are.

4. Assign the player to a house based on their height:
    - If their height is over 5.8:  
      a. Assign them to **House Targaryen**.
    - Otherwise:  
      a. Assign them to **House Stark**.

5. Output their name and their house name.

6. Present the first scenario:  
   `"You wake up in a forest, and there are 2 paths in front of you: `<br>` 
    1: Head towards the Red Keep to confront the Mad Queen.  `<br>`
    2: Brave the twisted woods in search of allies against the Queen. `<br>` 
   Which one would you choose?"`

7. If Path 1 is chosen:
    - Output: `"You walk for a few minutes, and a knight in red armor appears and confronts you."`
    - Present options:
        1. Lie: `"I’m a traveler, finding a place to rest."`
        2. Fight: `"Attack the knight."`
        3. Run away.
    - If option 1 (Lie) is chosen:
        - Output: `"The knight is suspicious and attacks you with his sword and you die."`
    - Otherwise, if option 2 (Fight) is chosen:
        - Output: `"You put up a good fight. But at the end, you are captured by the knight."`
    - Otherwise:
        - Output: `"You run away and get lost in the woods."`

8. Otherwise, if Path 2 is chosen:
    - Output: `"You cross a river and you see 2 dragons. You have 2 options:
        1. Approach one of the dragons.
        2. Run away."`
    - If option 1 is chosen:
        - Ask: `"Which dragon do you want to approach: Red or Blue?"`
        - If the choice is Red:
            - Output: `"You ride the Red dragon to King's Landing, fight the Mad Queen, and win and liberate the city."`
        - Otherwise:
            - Output: `"The dragon breathes fire on you and you die."`
    - Otherwise:
        - Output: `"You run away and get lost in the woods."`

9. Thank the player:  
   `"Thank you for playing the game!"`