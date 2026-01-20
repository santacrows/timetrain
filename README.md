Time Train

Time Train is a minimalist, text-based interval timer designed for high-focus environments. It runs entirely in the browser as a single file.

Features

Text-Based Logic: Define complex timer sequences using simple text strings.

Sets & Loops: Support for repeating groups of timers (e.g., HIIT or Pomodoro cycles).

Audio Cues: distinct beep upon timer completion.

Usage Syntax

The input field accepts a comma-separated list of time durations.

Basic Durations

s for seconds

m for minutes

h for hours

Example: 10s, 1m, 30s

Adding Labels

Add text inside parentheses (...) immediately after the time to label that interval.

Example: 10s (Get Ready), 1m (Focus), 5m (Break)

Sets and Loops

Use square brackets [...] followed by xN to repeat a sequence N times.

Syntax: [timer1, timer2]xCount

Example: [1m (Work), 30s (Rest)]x5

This creates a sequence of Work/Rest that repeats 5 times (10 timers total).

Controls

Update: Parses the text in the input box and generates the timer queue.

Play/Pause: Starts or pauses the current timer.

Reset: Stops the timer and resets the sequence to the beginning.

Presets: Click "Jump Rope" or "Meditation" to load pre-configured sequences.

