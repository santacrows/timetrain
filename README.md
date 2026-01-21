TIME TRAIN

Time Train is a minimalist, text-based interval timer designed for high-focus environments. It runs entirely in the browser as a single file and persists in the background on mobile devices.

FEATURES

Text-Based Logic: Define complex timer sequences using simple text strings.
Sets & Loops: Support for repeating groups of timers.
Randomization: Generate random durations for unpredictable sessions.
Background Support: Audio engine keeps timers running when screen is locked.
Keep Awake: Prevents device screen from dimming during use.

SYNTAX

The input field accepts a comma-separated list of time durations or the 'random' keyword:
s for seconds
m for minutes
h for hours
random for a random duration

Example: 10s, 1m, random

LABELS

Add text inside parentheses (...) immediately after the time to label that interval.
Example: 10s (Get Ready), 1m (Focus), 5m (Break)

SETS

Use square brackets [...] followed by xN to repeat a sequence N times.
Syntax: [timer1, timer2]xCount
Example: [1m (Work), 30s (Rest)]x5
This creates a sequence of Work/Rest that repeats 5 times.

RANDOM MODE

Use the keyword 'random' anywhere in your sequence.
Example: [random, 30s (Rest)]x3
This generates 3 unique random intervals separated by rest.

SETTINGS KEYWORDS

Control app settings directly within the text string:
count+ / count- : Enable or disable the 5s countdown chirp.
awake+ / awake- : Enable or disable the Keep Awake screen lock.

Example: 10m (Meditation), count-, awake-

CONTROLS

Update: Parses the text in the input box and generates the timer queue.
Play/Pause: Starts or pauses the current timer.
Reset: Stops the timer and resets the sequence to the beginning.
Presets: Quick load sequences like "Jump Rope", "Meditation", or "Random".
