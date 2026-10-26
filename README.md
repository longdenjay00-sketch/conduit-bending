# Conduit bending class

Instructor scripts for the hand-bender lab. Cold EMT on a bench. Students learn the marks on the shoe, then the stub, the offset, the three-point saddle, the back-to-back, the four-point saddle, and the bend budget.

The lab technician stages the bench. The academic coordinator owns the sequence.

## Order

| Script | Lab | Time |
| --- | --- | --- |
| [01-the-bender.md](01-the-bender.md) | Shoe, marks, shop rules | 45 min |
| [02-stub-up.md](02-stub-up.md) | 90° stub, take-up | 70 min |
| [03-offset.md](03-offset.md) | Two-bend offset, multiplier, shrink | 75 min |
| [04-three-point-saddle.md](04-three-point-saddle.md) | 45° center, 22.5° wings | 75 min |
| [05-back-to-back-and-four-point.md](05-back-to-back-and-four-point.md) | Star on a U, then two offsets | 90 min |
| [06-kick-and-the-bend-budget.md](06-kick-and-the-bend-budget.md) | One kick, then count degrees | 45 min |

[chart.md](chart.md) is the one-page card. Tape it to the bench before lesson 2.

[aids/index.html](aids/index.html) is the poster set: the bender, the marks on the shoe, the stub, the offset, and the saddle. The tool drawings are illustrations. The words and the arithmetic are the class chart. Open the HTML in a browser, or print [aids/bending-aids.pdf](aids/bending-aids.pdf).

Read the script once before class. The spoken parts are the paragraphs. The tables are for the board.

## What the class treats as settled

These are shop layout numbers, the same chart Milwaukee prints for its hand benders and the same take-up stamps Klein publishes for 1/2 in., 3/4 in., and 1 in. EMT shoes. They are not a Chapter 9 table.

| Mark on the shoe | Use it for |
| --- | --- |
| Arrow | Stub-ups and both bends of an offset |
| Star | Back of a 90, so back-to-back bends |
| Rim notch or teardrop | Center bend of a three-point saddle |
| Degree lines | Stop the pull at 10°, 22.5°, 30°, 45°, or 60° |

Field chart the lessons use:

| Angle | Distance between offset marks | Shrink per inch of depth |
| --- | --- | --- |
| 10° | depth × 6 | 1/16 in. |
| 22.5° | depth × 2.6 | 3/16 in. |
| 30° | depth × 2 | 1/4 in. |
| 45° | depth × 1.4 | 3/8 in. |
| 60° | depth × 1.2 | 1/2 in. |

Take-up the lessons assume, until you read the shoe: 5 in. on 1/2 in. EMT, 6 in. on 3/4 in., 8 in. on 1 in. The stamp on the shoe in the room wins. Write that stamp on the board and use it in every answer key for the day. If the stamp is 5 in. and a student subtracts 6 in., the stub comes out short.

Three-point saddle, the chart these lessons teach: center at 45° on the teardrop, wings at 22.5° on the arrow, wings spaced 2-1/2 in. from the center mark for each inch of depth, center mark moved ahead by 3/16 in. per inch of depth. If the card in the bender box prints a different saddle multiplier, teach the card.

## One measurement rule

Say this in lessons 3, 4, and 5.

The tape starts at the end of the stick that stands in for the box. Measure to the place the bend has to finish: the near edge of a flat obstruction, or the center of a round one. Add shrink to that number. That sum is the far mark on the straight pipe. Step back toward the box for the other marks.

Take-up is a different operation. On a stub you subtract it. Shrink is added because the pipe travels a diagonal and the far side comes up short.

## Code the instructor reads from the book

Have the adopted NEC on the bench, open.

- **358.24** — how a bend is made. The tube stays round. The radius stays at or above Chapter 9, Table 2. Read Table 2 before quoting a radius.
- **358.26** — number of bends in one run. Mike Holt's May 25, 2023 EC&M answer states the limit as 360° between pull points, and states that offsets count. Read the sentence in the book on the bench before you quote it. A conduit body or a box resets the count. Factory elbows count.
- **358.28** — trimming. Ream a cut end before it is coupled. Read the section before you assign a subsection letter.
- **358.30** — securing and supporting. Read the distances and the exceptions from the book. Week one does not teach exceptions from memory.

The same 360° limit appears for RMC, IMC, and PVC in 344.26, 342.26, and 352.26. This course bends EMT only.

## Bench

- Safety glasses for every person in the room, including you.
- One 1/2 in. EMT hand bender for each pair. One 3/4 in. shoe and one 1 in. shoe on the demo bench.
- 1/2 in. EMT, full sticks. Plan on two sticks ruined per student across the six labs. Straight offcuts longer than 24 in. go back into the stub bin.
- A tape for each student. A marker. Marks go all the way around the pipe.
- A torpedo level and a combination square.
- A cutter and a reamer, for lesson 6. Bending lessons can run on full sticks.
- A round obstacle about 2 in. high, clamped, for the three-point demo.
- A block 4 in. high and 8 in. along the bench, for the four-point demo.
- The bender card that shipped with the shoe, if you still have it.
- Scrap only. Students do not bend conduit that is already installed. They do not open a panel. They do not heat EMT to make it bend.

## Tolerance and scrap

A stub is right when the back of the bend measures within 1/8 in. of the target. An offset is right when the rise matches the target within 1/8 in., the two legs sight parallel, and both bends sit in one plane.

A dog leg is scrap. Bending a stick back and forth to chase a mistake splits the seam. Cut the bad bend off or drop the whole stick in the short bin.

## Changes

`main` takes work through a pull request. A commit may include every file that belongs to that change.

## Sources the numbers come from

Layout steps and the rounded multiplier chart match the trade method printed in hand-bender instructions and written up the same way by VoltageLab (offsets, saddles, Klein take-up stamps of 5 in., 6 in., and 8 in.) and by the Panda Taps bending notes (the 60 in. / 6 in. / 30° worked offset). The 360° rule is the limit Mike Holt stated for 358.26 in EC&M on May 25, 2023. Confirm every code sentence against the book adopted for this class before you treat a subsection as fixed.
