Usage

```
<clock-face 
time-zone="America/Toronto"
second-hand="true"
></clock-face>
```

CSS Variables:

```
  svg.clock {
    width: var(--clock-size, 100%);
    height: var(--clock-size, 100%);
  }

  .clock-face {
    fill: var(--clock-face-fill, none);
    stroke: var(--clock-face-outline, currentColor);
    stroke-width: var(--clock-face-width, 1.5);
  }

  .hours-hand,
  .minutes-hand,
  .seconds-hand {
    stroke-width: var(--clock-face-width, 1.5);
  }

  .hours-hand,
  .minutes-hand {
    stroke: var(--clock-hand-outline, currentColor);
  }

  .seconds-hand {
    stroke: var(--clock-seconds-color, orange);
  }
```

