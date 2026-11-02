# Singer 99K Knee Controller Case

The purpose of this project is to fully document an example of Singer's
portable base with a built-in knee controller, together with its dome top
and the Singer 99K it came with.

![The Singer 99K in its knee-controller base, as received. The round
fitting on the front of the base, at the right, is the socket for the knee
lever.](photos/as-received-front.jpg)

## The example

- **The machine:** a Singer 99K, serial AM477136. Its number falls in a
  batch of 30,000 that Singer allocated in April 1956; the next batch in
  that series was allocated in September. It has the final form of the
  99's reverse-stitch lever, with a locking mechanism.
- **The base:** a wooden portable base with the knee controller built in,
  and its dome top. The knee lever plugs into the round socket on the front
  of the base at the right.
- **Its condition:** the original wiring is complete and intact. It needs
  replacing before the machine is run, but it shows exactly how Singer
  wired these bases. The bent-steel knee lever is missing; originals are
  scarce.
- **Where it came from:** a sewing-machine rescue group gave it to Bob
  Drzyzgula in October 2026.

Bases like this are mostly known from photographs, and usually of examples
that no longer work. This one is complete apart from the lever, which makes
it worth recording in full before anything is changed.

## Workplan

1. **Record it as found.** Photograph everything before anything is
   disturbed, with a scale in the frame: the base, the dome top, the
   machine in place, and every fastener, terminal and wire run. Take views
   square to each main face as well as angled views.
2. **Measure.**
   - The base and the dome top: outside dimensions, wall and floor
     thicknesses, the bed seat, the hinges, the latches and the handle.
   - The knee lever socket: its bore, depth and any key or flat, its
     position on the front face, and its angle.
   - The mechanism inside: pivots, linkages, springs and stops, and how the
     lever's movement reaches the controller.
   - The controller: its type (carbon pile, resistor stack or rheostat),
     maker and part number, mounting and enclosure.
3. **Characterize it,** without mains power: the controller's resistance
   from rest through the point where the motor would start to full travel,
   the lever's travel, and the force it takes. This gives a measured curve
   to set beside the carbon-pile and rheostat analysis in the VSM Base
   project's motor-control paper.
4. **Document the wiring.** Draw a wiring diagram of the base as built:
   the controller, the terminal block, the motor and light leads, the power
   cord, and how each run is routed and secured.
5. **Model it.** Build a 3D reference model in OpenSCAD from the
   measurements and photos: the base, the dome top and the knee mechanism.
   It will show an assembled view, an exploded view of the mechanism and a
   section through the controller. The machine itself appears only as its
   bed's outline in the seat.
6. **Write it up.** Put together a written account of what was found, with
   the photographs, drawings and measurements, as a historical reference.
7. **Later, perhaps.** Rewire the base safely, and make a replacement knee
   lever from the socket's measurements: bent steel, or a printed lever
   with a steel insert at the socket end.

## Planned layout

- `photos/`: photographs, as found and during disassembly.
- `measurements/`: the measurements, with notes on how each was taken.
- `model/`: the OpenSCAD model.
- `drawings/`: the wiring diagram and views exported from the model.
- `docs/`: the write-up.

## Status

Just begun: one photograph, and this plan.

## Related

[VSM Base](https://github.com/bobdrzyzgula/VSM-Base), a parametric,
3D-printable base for vintage flatbed sewing machines, including the
Singer 99K, with a knee controller of its own in design.

## Credits

The machine and base belong to Robert Drzyzgula, who is examining,
photographing and measuring them. This README was written by Claude
(Anthropic) at his direction.
