### Planes 

---

This game is a variation of the well known Battleships paper game. Planes inherit from Battleships these two activities:
- Placing the Plane on the paper
- Guessing where the opponent's planes are positioned.

The differences between these two games are the shape of the placed object, where a plane uses more cells to represent itself instead of a line,
each plane can be placed in a given orientation.


In the Planes game you have three different hits:
- **Air** - nothing was hit
- **Hit** - player hits the plane's body but not the cabin
- **Crash** - player hits the plane's cabin, the entire plane crashes

More information is available at: https://avioanele.ro (Romanian language).

---

**How to play:**

When the user starts the application, he has to choose his difficulty between Easy, Normal, Hard and Veteran.
Depending on the chosen difficulty, the board has different sizes. 

Then, the users needs to place his planes by typing in the console the coordinates of the cabin(e.g. A4) and the orientation(N-S-E-W).

This is how to board will look when we place to A4 with the orientation N on normal difficulty:

![Planes board](https://i.postimg.cc/kX4mPXHF/image.png)

This process goes until all planes are placed.

The next step is to guess where is the opponent's planes by typing coordinates where the cabin / body of a plane should be.

If one has all it's planes crashed, he looses the game.


---

**To do:**
- Add a graphical user interface
- Add more 

---

# Requirements
- **Python IDE**
- **Texttable module**

