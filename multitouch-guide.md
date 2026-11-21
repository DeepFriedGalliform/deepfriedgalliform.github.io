# MultiTouch guide

MultiTouch (version 1.1) turns a small round Waveshare touch board into a pocket set of tools, scorers, games, puzzles, party games and, on the AMOLED boards, music makers. Two AMOLED boards can also play together (see Two boards). Everything is played on the round screen with taps, swipes, drags round the rim, tilting, shaking and knocking.

![The home menu](multitouch/screens/home.png)

Pictures of more screens are in [multitouch/screens](multitouch/screens/). They are drawn on a computer from the device's own screen layouts. The real screen looks the same, except that its lettering is a slightly different font.

## Controls

### Moving between modes
- **Home menu:** the modes are in groups round the ring (Tools, Score, Arcade, Games, Puzzles, Party, and Music on the AMOLED boards), with **Setup** among them. Tap a group's icon to open it, then tap a mode's icon to start it.
- **Big groups:** a group with more than 12 modes turned on gets a second page. Tap **>** at the end of the ring to go to it, and **<** to come back.
- **Choosing modes:** you can turn modes off and change their order on the web page (see Settings below).

### Settings
- **A mode's options:** hold your finger on the screen to open them. Every mode's options include its own settings, **?** (a short "how to play"), **Start again** and **Exit**.
  - **Music modes:** a long press doesn't open the options. Tap the mode's own icon in the arc at the top instead. **Go back** takes the place of Start again.
- **Changing a value:** drag round the rim, or use the **-** and **+** buttons.
- **Sound** (AMOLED boards): Off, Low, Medium, High or **Max**, the loudest for the small on-board speaker. It's in the options of the timers, Beat swipe and the music modes, and on the web page.
- **Setup** (on the home menu) has:
  - brightness
  - sleep and deep-sleep times
  - travel mode
  - screen rotation
  - tilt sensitivity and tilt direction
  - clearing best scores
  - reset
  - **Web setup**
- **Web setup:**
  1. Go to Setup > Web setup > Start. The device makes its own Wi-Fi network and shows a QR code.
  2. Scan the code with a phone. The phone joins the network and the setup page opens (or open http://192.168.4.1).
  3. Press Stop when you're done. It also stops by itself after 10 minutes without use.
  - The page has these tabs:
    - **Settings:** every setting.
    - **Menus:** hide modes, or change their order.
    - **Words:** your own Charades lists.
    - **Scores:** best scores.
    - **Backup:** save everything, or restore it.
    - **Device:** battery and other details.
    - **Music** (AMOLED boards only): pads' sounds as WAV files.
- **Tilt games:** the first time you play one, it asks you to lay the device flat on a table and tap. That calibrates the motion sensor. You can do it again later with **Calibrate** in the game's options.

### Going back
- **In the menus:** tap the centre button or swipe right.
- **In a mode:** swipe right to leave it. In a game this only works while the game is paused. You can also hold for the options and choose **Exit**.
- **In the music modes:** a swipe right goes back a page. Pages such as Song, FX and Kits have a back button at the top.

### Sleep and wake
- **Going to sleep:** on the home menu, the centre button puts the device to sleep. It also sleeps by itself after the **Sleep after** time.
- **Waking up:** a touch or picking it up (movement) wakes it.
- **Travel mode:** only a double tap wakes it, so it doesn't wake up in a bag.
- **Deep sleep:** after the **Deep sleep** time asleep, it goes into a deeper sleep to save the battery. A touch still wakes it (and movement, unless travel mode is on). It doesn't deep-sleep while charging or while a timer runs.
- **Timers:** a running Pomodoro or Timer wakes the device when it ends.
- **The music:** while the music plays, the device stays awake.

## The modes

### Tools
| Mode | What it does and how to use it |
|---|---|
| Pomodoro | A work and break timer. Tap to start or pause, and swipe left to skip to the next phase. It wakes the device when a phase ends. |
| Game clock | A two-player chess-style clock. Tap your half of the screen when you've moved. You can add time to each move. |
| Decide | Flip a coin (tap or shake), or flick a wheel of 2 to 8 segments. |
| Level | A spirit level. Tap to freeze the reading, and use "Zero here" in its options. |
| Oracle | Ask a yes or no question, then shake for the answer. |
| Timer | A countdown (drag round the rim to set it; it wakes the device when it ends) or a stopwatch with laps. |

### Score
| Mode | What it does and how to use it |
|---|---|
| Snooker | Tap each ball as it's potted (only the balls you can play are lit). It shows the break, the points left and any snookers needed. A swipe ends a visit, and a swipe down undoes. |
| Darts | Pick single, double or treble, then tap the number on the rim. It plays 501 or 301 with checkout hints, Cricket, Round the clock and Points. |
| Points | A two-player counter. Tap a side to score, with a target and "win by two" if you want them. |
| Cards | Running totals for 2 to 6 players. Tap a player, set the points on the rim, then tick. |
| Five dice | The five-dice scorecard game for 1 or 2 players. You get three rolls a turn, and tap dice to hold them. |

### Arcade
| Mode | What it does and how to use it |
|---|---|
| Snake | Tilt (or swipe) to steer the snake to its food. Rocks appear as it grows. |
| Maze | Tilt to roll the ball to the green exit before time runs out. Each maze is new and each level bigger. |
| Glide | Touch to flap up through the gaps. |
| Ring Pong | Drag the paddle round the rim to bounce the ball into the blocks. Tap the middle to pause. |
| Reflex | Wait for green, then tap as fast as you can. Five goes, then your average. |
| Orbit | Your ship circles on two tracks. Tap (or knock, if you turn that on) to hop between them and dodge the rocks. |
| Stack | Tap to drop each sliding slab on the tower. Whatever overhangs is cut off. |
| Whack | Tap the moles before they duck down, for 30 seconds. |
| Tilt marble | Tilt to roll the marble over every gem without falling in a hole. You have three lives. |
| Rim defender | Drag (or tilt) the shield round the rim to block rocks drifting out from the middle. |
| Balance | Tilt to keep the ball on a tipping beam. The beam gets shorter every 10 seconds. |
| Beat swipe | Swipe the way each arrow points as it reaches the middle, on the beat of a tune. There are three tracks. You only hear the tune on the AMOLED boards. |

### Games
| Mode | What it does and how to use it |
|---|---|
| Echo | A colour-pattern memory game. Watch, then repeat it. |
| X & O | Noughts and crosses against the device (easy, fair or perfect) or a friend. |
| Dice | Roll 1 to 5 dice, from d4 to d20. Tap or shake to roll. |
| Gems | Match three: swap neighbouring gems to make lines, with 30 moves a game. |
| Merge | The 2048-style sliding number game, played with swipes. |
| Mines | Clear the round minefield. Tap to open a cell, and hold to flag it. |
| Pairs | Find the eight pairs in as few moves as you can. |
| Quick maths | As many sums as you can in 60 seconds. |
| Colour clash | Tap the colour of the ink, not the colour the word says. |
| Four in a row | Tap a column to drop a disc, and get four in a line. Play the device or a friend. |
| Mancala | The traditional six-pit sowing game, round the ring. Play the device or a friend. |
| Higher or lower | Guess whether the next card is higher (tap the top half) or lower (the bottom half). |
| Carrooka | Snooker with flicked pieces on a round board with six pockets. Flick the striker into the pieces (or, with Shoot by in the options, pull it back and let go; the further, the harder). While the striker is on the break line, drag it round the line or tap a spot on it; otherwise you shoot from where it stopped. Game (in the options): full Carrooka (pot a red, tap a colour to call it, pot that; after the reds, the colours in order; a foul scores nothing and gives the other player a bonus shot, and if the foul leaves them Carrooka'd they choose Break line, Free counter or Skip), UK pool, US pool (numbered spots and stripes) or 9-ball (numbered). Play the device (easy, fair or hard) or a friend. The best is how many times you have beaten the device on hard. |

### Puzzles
| Mode | What it does and how to use it |
|---|---|
| Lights Out | Turn every light off. Each tap flips a light and its neighbours. |
| Slide | The 3x3 or 4x4 sliding-tile puzzle. |
| Code breaker | Find the hidden code of four in ten guesses. |
| Pegs | Peg solitaire on the cross-shaped board. |
| Tower | Move the stack to the right-hand peg, never putting a bigger disc on a smaller one. |
| Number order | Remember where the numbers were, then tap them in order. |
| Flood | Tap colours on the rim to grow your blob from the corner, and fill the board before the moves run out. |
| Pipes | Turn the tiles until every pipe joins the source in the middle with no open ends. |
| Mini sudoku | 4x4 or 6x6 sudoku. Tap a square, then a number. |
| Binary grid | Fill the grid with gold and blue: no three in a line, and the same number of each in every row and column. |
| Bridges | Join the numbered islands with that many bridges each. |
| Light paths | Turn the mirrors to steer a laser through every target. |

### Party
| Mode | What it does and how to use it |
|---|---|
| Reaction duel | Two players, one half each. The first to touch on green wins the round. |
| Charades | Hold it to your forehead while friends give clues. Tip it down for correct, or up to pass. You can use your own word lists. |
| Hot potato | Tap to light a hidden fuse, then pass it round until it goes off. |
| Tap race | Two players, one half each. Most taps in 10 seconds wins. |
| Shake-off | 2 to 6 players take turns. Most shakes in 10 seconds wins. |
| Steady hand | 2 to 6 players take turns keeping a bubble in a shrinking circle. |
| Spin the bottle | Tap, shake or flick to spin, with numbered seats round the rim if you want them. |
| Guess the time | 2 to 6 players take turns. Start a hidden clock, then stop it when you think the target time is up. |

### Music (AMOLED boards only)
All five share one layout:
- **Top arc:** the five music modes. Tap one to switch, and the music keeps playing. Tap the one you're in for its options.
- **Middle panel:** the mode's own controls.
- **Bottom arc:** **REC**, **play / pause** and the pattern.

| Mode | What it does and how to use it |
|---|---|
| Pads | 16 sounds on pads round the rim, played the moment your finger lands. Choose a built-in kit or one of your own. With REC on, your hits are recorded into the pattern. |
| Sequencer | One bar of 16 steps round the ring. Tap steps to place the sound you last played, slide from a step to change its note, chain patterns into a Song, and hold FX for loops, filters and more. |
| Synth | Touch notes round the rim and slide to glide between them; two fingers play two notes at once. Change the sound, octave and scale in the middle. Tap the sound's name for its pages: Filter (an X/Y pad), Waves, Envelope (a chart you drag), Filter env and Arpeggio (held notes played one at a time, up, down or at random, in time with the tempo; Chord turns one note into its chord). Each page has a Reset, lit when you've changed something. |
| Motion | Play by moving the device: tilt for the note and its tone, and shake or knock to play drums. |
| Sampler (1.75C only) | Record up to 30 seconds with the built-in microphones; each recording is raised to full level when it stops. Trim it (drag the handles; ▶ plays it), chop it (‹ count › and an Even / Hits switch), then put the slices on pads. The ‹ at the top goes back a step, the green button on. |

## Two boards (AMOLED boards only)

Two AMOLED boards running MultiTouch link up directly by radio, a few metres apart. No Wi-Fi network or router is needed. The 1.28" board can't link.

- **Pair them once:** open **Duo > Pair** on both, then knock them together edge to edge, or tap the other board's name in the list. They stay paired after a restart. Pair shows whether the other board is in reach, and has **Ping it** (the other board beeps), **Turn the gate** (the mark on the rim that points at the other board: turn it a quarter if the knock got the side wrong) and **Unpair** (tap twice).
- **Start a game:** open a Duo game, or choose **Two boards** in a mode's options. The other board opens the same thing and shows "wants to play": tap to join, hold for no thanks. **One board**, in the same place in the options, goes back to playing alone.
- **Who's in charge:** the board that asked is the host, and its settings are used.
- **Out of reach:** the game shows "Lost them" and waits. After 8 seconds both boards give up. Leaving the mode, Exit or standby tells the other board.

### The Duo group

| Mode | How it works |
|---|---|
| Quick Draw | Wait for DRAW!, then flick your wrist. The first flick wins the round; a flick before DRAW! loses it. First to 3. |
| Blind Maze | One board rolls an orb through a maze it can't see; the other sees the whole maze and talks the roller to the middle. Four levels, swapping roles. |
| Star Feeder | One board swipes stars out through the gate; the other tilts a basket to catch them. Catch the gold, dodge the red. Two rounds, swapping roles. |
| Defuse Duo | One board has the bomb (wires, symbols, a button, lights), the other has the rules. Talk it through before the 3 minutes run out. |

### Two boards in other modes

| Kind | Modes |
|---|---|
| A player each | Game clock (a clock each: tap anywhere when you have moved), X & O, Four in a row, Mancala (your own side at the bottom on each board), Carrooka (each board shows the table from its own side), Five dice, Reaction duel, Tap race, and Hot potato (hold it a moment until the ring fills, then tap or swipe to throw it to the other board; whoever has it when it goes off is out). |
| Races | Higher or lower (the same deck), Quick maths (the same sums), Colour clash, Echo (the same pattern), Shake-off, Steady hand and Guess the time (both clocks start together). A tap on either board starts both; each plays on its own board, and the scores are compared at the end. |
| One scoreboard | Points, Snooker, Darts and Cards show the same score on both boards. Either can score, and undo works on either. |

## The three boards

| | ESP32-S3-Touch-AMOLED-1.75C | ESP32-S3-Touch-AMOLED-1.75 | ESP32-S3-Touch-LCD-1.28 |
|---|---|---|---|
| Screen | 1.75" round AMOLED, 466 x 466 | 1.75" round AMOLED, 466 x 466 | 1.28" round LCD, 240 x 240 |
| Sound | Speaker on the board | A speaker plugs into its socket | None: alerts flash on the screen |
| Microphones | Two (the Sampler works) | None known (the Sampler says "No mic") | None |
| Modes | All 66, music and the Duo group included | All but a working Sampler | 56: every mode but Music and Duo |
| Two boards | Yes, with another AMOLED board | Yes, with another AMOLED board | No |
| Game and alarm sounds | Yes (Sound: Off to Max) | Yes, with a speaker fitted | No |
| File space | 24 MB (room for many recordings) | 1 MB | 1 MB |
| Battery | Battery and charging chip (AXP2101) | Battery and charging chip (AXP2101) | Battery level read by the board |
| Install | Its own build: pick "1.75C" | Pick "1.75" | Pick "1.28" |

All three run the same modes in the same layout. The AMOLED boards just draw everything sharper at the larger size. Install the build that matches your board: the 1.75C and the 1.75 use different pins for sound, the screen's reset and touch, so the other board's build won't work properly (on a 1.75C, the 1.75 build gives no sound). On the 1.75C, left and right tilt are mirrored in software (its motion sensor sits the other way round), so if you used it with an older version, calibrate tilt again.
