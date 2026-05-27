# Rubik's Cube Notation & Anatomy Reference

Learning to solve or speedcube requires speaking the "language" of the cube. This guide breaks down the anatomy of a standard 3x3x3 Rubik's cube, piece naming conventions, and the official Singmaster notation used for algorithms.

---

## 1. Anatomy & Naming of Pieces

A standard 3x3 cube is made of 26 external pieces held together by an internal core. Pieces are named purely by the **faces they sit on**, using the face letters: **U** (Up), **D** (Down), **F** (Front), **B** (Back), **L** (Left), and **R** (Right).

| Piece Type | Quantity | Stickers/Colors | Naming Convention & Examples |
| --- | --- | --- | --- |
| **Center** | 6 | 1 | Named by a **single letter** representing its face.<br>

<br>• *Example:* The **U piece** is the center piece on top. |
| **Edge** | 12 | 2 | Named by a **two-letter combination** representing the two faces it touches.<br>

<br>• *Example:* The **UF piece** sits between the Up and Front faces. |
| **Corner** | 8 | 3 | Named by a **three-letter combination** representing the three faces it touches.<br>

<br>• *Example:* The **UFR piece** sits at the intersection of Up, Front, and Right. |

> **Note on Core Mechanics:** Centers are fixed to the core. They **never move** relative to each other and define the final color of that face. Edges only travel to other edge slots; corners only travel to other corner slots.

---

## 2. Naming Specific Faces vs. Specific Pieces: The Order Matters

When referencing a specific sticker or a specific angle of a piece during an algorithm or tutorial, the **order of the letters** is highly precise.

### Piece vs. Face (Sticker)

* When you name a **piece**, the order of letters doesn't matter technically (the UF piece, the FU piece, and the Front-Up piece all mean the exact same physical chunk of plastic).
* When you name a **face of a piece** (a specific sticker), the **first letter tells you which face you are looking at**.

### Deep Dive: FU Face vs. UF Face

Imagine the edge piece that sits right between the Top (Up) and Front faces of your cube. It has two stickers: a top sticker and a front sticker.

* **The UF Face (or UF sticker):** This refers to the **Up** sticker *on the Up-Front piece*. If you are looking down at the top layer, this is the edge sticker facing the ceiling.
* **The FU Face (or FU sticker):** This refers to the **Front** sticker *on the Front-Up piece*. If you are looking straight at the front layer, this is the edge sticker facing directly at you.

Similarly, for a corner piece like **UFR**:

* The **UFR face** is the top sticker.
* The **FUR face** is the front sticker.
* The **RUF face** is the right-side sticker.

---

## 3. The 6 Outer Faces

When executing an algorithm, hold the cube in a fixed orientation. The faces are named relative to how you are looking at the cube at that exact moment:

* **U** (Up): The top face.
* **D** (Down): The bottom face.
* **F** (Front): The face facing you.
* **B** (Back): The face facing away from you.
* **L** (Left): The left face.
* **R** (Right): The right face.

---

## 4. Move Notation (Singmaster Notation)

Moves are written as single letters. The direction of the turn is always determined by **looking directly at that specific face**.

### Standard Outer Layer Moves

* **Letter Alone (e.g., R, U, F):** Turn that face **90 degrees clockwise**.
* **Letter with an Apostrophe / Prime (e.g., R', U', F'):** Turn that face **90 degrees counter-clockwise** (pronounced "Right Prime", "Up Prime", etc.).
* **Letter with a '2' (e.g., R2, U2, F2):** Turn that face **180 degrees** (the direction does not matter, though clockwise is standard).

### Execution Guide

| Notation | Face | Direction (When Looking Directly At It) |
| --- | --- | --- |
| **U** | Up / Top | Clockwise (Leftwards from front view) |
| **U'** | Up / Top | Counter-Clockwise (Rightwards from front view) |
| **D** | Down / Bottom | Clockwise (Rightwards from front view) |
| **D'** | Down / Bottom | Counter-Clockwise (Leftwards from front view) |
| **R** | Right | Clockwise (Upwards from front view) |
| **R'** | Right | Counter-Clockwise (Downwards from front view) |
| **L** | Left | Clockwise (Downwards from front view) |
| **L'** | Left | Counter-Clockwise (Upwards from front view) |
| **F** | Front | Clockwise |
| **F'** | Front | Counter-Clockwise |
| **B** | Back | Clockwise (Leftwards from top view) |
| **B'** | Back | Counter-Clockwise (Rightwards from top view) |

---

## 5. Advanced Notation (Slices & Double Layers)

As you progress past beginner methods, you will encounter inner layer slices and double-layer turns.

### Slice Moves (Middle Layers)

These affect only the inner 3x1x3 slices of the cube.

* **M (Middle):** The vertical slice between L and R. **Follows the direction of L.** (M moves top-to-bottom on the front face).
* **E (Equator):** The horizontal slice between U and D. **Follows the direction of D.** (E moves left-to-right on the front face).
* **S (Standing):** The vertical slice between F and B. **Follows the direction of F.**

### Double-Layer Moves (Wide Moves)

Turning two layers at once (the outer face plus its adjacent middle slice). Written either with a lowercase letter or followed by a 'w'.

* **u** or **Uw:** Turn the Up face and the Middle horizontal layer together clockwise.
* **r** or **Rw:** Turn the Right face and the Middle vertical layer together clockwise.
* **f** or **Fw:** Turn the Front face and the Middle standing layer together clockwise.

---

## 6. Cube Rotations (Re-orienting)

Sometimes an algorithm tells you to turn the *entire cube* in your hands without moving any individual layers. These follow the axes of a standard 3D graph ($x, y, z$):

* **x / x':** Rotate the entire cube on its **R axis** (look up to the top face / look down to the bottom face).
* **y / y':** Rotate the entire cube on its **U axis** (spin the cube horizontally left or right).
* **z / z':** Rotate the entire cube on its **F axis** (tilt the cube sideways clockwise or counter-clockwise).

---

> **Pro-Tip for Beginners:** The muscle memory trigger for the most common 4-move sequence in speedcubing (often called the "Sexy Move") is written as: **`R U R' U'`**. Try repeating it 6 times on a solved cube — it will return the cube exactly back to its solved state!

## 7. top layer OLL notation

We can present the top layer like below.
N is just a place holder to keep the formating.
Y is yellow sticker, and G is grey sticker, i.e. sticket not matter
The middle 3 x 3 is the top face color.
the first row is the back face of the top layer
the last row is the front face of the top layer
the first and last column are the left and right face of the top layer respectively.

N Y G G N
G G Y G Y
G Y Y Y G
G Y Y G G
N G G Y N
