# algorithms-with-js-ts

Solutions to common coding problems, written in TypeScript. One folder per
problem, each holding the problem statement and the solution.

31 problems so far, with 40 solution files, because some problems have more than
one approach kept side by side.

## How it is laid out

```
addBorder/
  README.md        the problem statement, with an example
  addBorder.ts     the solution

alphabeticShift/
  README.md
  alphabeticShift.ts        first approach
  alphabeticShiftAlt.ts     another way of doing it
  alphabeticShiftAlt2.ts
  alphabeticShiftAltAscii.ts
```

Where a file ends in `Alt`, it is a second or third take on the same problem.
Those are kept on purpose: comparing a readable version against a shorter or
faster one is most of the value in doing these.

## Running one

There is no build setup. Run a file directly with a TypeScript runner:

```bash
npx tsx addBorder/addBorder.ts
```

Or compile it first:

```bash
npx tsc addBorder/addBorder.ts && node addBorder/addBorder.js
```

## Status

Added to now and then rather than worked on continuously.
