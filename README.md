# Just Play Jam, 2023

A mini prototype for Banned Together, developed for the [Just Play Jam](https://www.justplayjam.com/) in 2023  

Built using [Bitsy Color 3D (v7.2)](https://aurysystem.github.io/bitsy-forks/bitsy-color-3d/index.html) & [Bitsy Savior](https://aloelazoe.itch.io/bitsy-savior)  

## Experiments

### Elana

- **Empty template:** A large, empty space with a front door, windows, and a roof over your head. Includes convenient tiles for bookshelves (with and without books), an elevator, and alternate floor & ceiling styles. What more could you need? 🤷🏻‍♀️

- **Basic library:** A two-floor structure built using the elements provided in the empty template. It provides some simple narrative interaction, in the form of a thought bubble, a love letter, and a missing book that can be discovered.

- **Staircases:** Similar to the basic library, but explores using staircases, instead of an elevator, to travel up & down among three floors.

- **Infinite hallway:** A first test of using invisible exits to create seamless transitions between spaces, resulting in impossible geometries and surreal gameplay. Unfortunately, I had trouble making these transitions truly seamless in this context. You can fake it with a dialog, but otherwise there's a small hickup when teleporting during linear motion. (Relatedly, this was also my first test of invisible items as dialog triggers for internal thoughts!)

- **Impossible corner:** It turns out that impossible corners (ie turns with more than four 90° angles) work much better! Since forward movement stops briefly when turning, the transitions are actually seamless. For this simple setup, I only provided one-directional movement, so things will break a little bit if you try backtracking.

- **Impossible courtyard:** Building on the impossible corner experiment, this setup supports bidirectional movement around a central courtyard, which "magically" changes appearance to match the color of the floor you were last walking on. I think this could help drive some powerful effects for our game (eg time travel mechanics)!

- **Lost Woods:** The culmination of my experiments, this complete, playable puzzle uses corner transitions to create an impossible space akin to the "Lost Woods" from the Zelda series! I had to tweak some settings to smooth the transition effect when using multiple rooms, but I think it worked out alright in the end. (I also took inspiration from Nat's Dewey Decimal idea, providing clues through wall signs 😉) Whether or not we use this mechanic, the file also includes some improved, 16x16 bit textures, which I'm pretty pleased with and would consider reusing! 🎨

### Nat ###

- **Large library**

- **Storytelling with the Dewey Decimal System**