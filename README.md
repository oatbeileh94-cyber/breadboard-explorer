# Breadboard Explorer

An interactive circuits-lab tool for teaching how a solderless breadboard works, plus Ohm's law and the resistor color code.

Everything is one static page (`index.html`) with no build step or dependencies. It only loads fonts from Google Fonts.

## What's inside

**Connections**
- Point at (or tap) any hole to highlight every hole it's connected to.
- Pin one hole and compare it with another, with a plain-language reason.
- "See inside the board" shows the metal strips under the plastic.
- "Split power rails" shows the kind of board whose rails break partway along.

**Circuits**
- Six example LED circuits on a 9 V battery:
  - Three that work: an LED with a switch, series LEDs and parallel LEDs.
  - Three common mistakes, each with a "Show the fix" button.
- A small DC solver drives LED brightness, a virtual voltmeter, part currents and animated current flow.

**Ohm's law & color code** (worksheet style)
- **Part A:** a V = I × R solver with a live circuit diagram and step-by-step working, plus a water picture of the same circuit: tank height is like voltage, the tap is like resistance and the flow is like current. Students can drag the water level and the tap.
- **Part B:** a clickable 4- and 5-band resistor that works in both directions (bands to value, and value to bands).
- **Part C:** a practice quiz whose wrong answers are real student mistakes.

It works on a projector, laptops and phones, in light and dark themes, and can be used with the keyboard.

## Running it locally

Open `index.html` in any modern browser.
