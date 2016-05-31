# chris_game
Small program to amuse my toddler son

First thing: Press q+z+p to quit.

Second: Yes, all it does it beep and draw shapes on the screen when you play with the keyboard :-)

The game starts at full-screen (currently hard-coded to 1920x1080, because I don't expect that anyone else will ever actually use this.

Different rows of keys play different notes, C5 - E6, I think (and only the full steps)

- The number keys "1" -> "0" (both numpad and the number row) play a randomized waveform.
- The keys "Q" -> "P" play notes generated by an abs(sine) function. 
- The keys "A" -> ";" play notes generated by the sine function.
- The keys "Z" -> "/" play notes generated as a square wave.

The spacebar plays a random note in a random "instrument" (different one each time you press it)

All the other buttons on the keyboard that SFML recognizes play different notes depending on the keyscan code.

Also, different shapes and stuff pop up, then spin and fade away when you release the key.
