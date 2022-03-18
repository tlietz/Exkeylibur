# Exkeylibur

```markdown
I froze your switches and made Exkeylibur,
and pushed it onto Github forever.
It stays there like Excalibur,
Are you its Arthur?
Say you are.

Take the cool, dark, steeled board,
Steal it, sheath it, in your workflow.
All would drown their other keebs to be together.
Must they breathe? 'Cause typing feels like heaven.
```

*Based off of ['Excalibur' - by David Brent](https://www.youtube.com/watch?v=634TC7Feku4)*

I would like to thank the honorable [Ferris Sweep](https://github.com/davidphilipbarr/Sweep), for without you, the Exkeylibur would have no pcb layout.

## Prelude

An Exkeylibur is a 36-key, diodeless, wireless-only keyboard with Ferris stagger and a reversible PCB.

An Exkeylibur can be wielded without a sheath, however, you are encouraged to create one.

A promicro, or any other non-wireless microcontroller drop-in for the promicro, is **not** supported. This is because the GPIO pin that would normally go to a TRRS jack
now goes to an extra switch.

## Features

- Wireless only
- No diodes required
- 36 keys
- Reversible PCB
- Ferris stagger
- Choc-spaced
- Promicro MCU footprint

## V2 Changes

- Rotated thumb keys by 90 degrees to support 1.5u keycaps
- Added room to place rubber feet
- Moved home thumb row key to be between the original inner and outer thumb key placement of the Ferris
- Place reset button in a position that can be easily pressed with finger
- Slightly increased reset button pcb pad spacing to support more sizes
- Removed stagger on inner columns to reduce strain on index finger when reaching for the bottom key.
- Added drill holes to support Corne MCU covers

## Firmware

Wield the Exkeylibur with the [firmware](https://github.com/tlietz/zmk-config)

---

## Images

### V2

### V1

#### Original

![original-pcb](https://github.com/tlietz/Exkeylibur/blob/main/images/og_pcb.png)

#### Hilt

![hilt-pcb](https://github.com/tlietz/Exkeylibur/blob/main/images/hilt_pcb.png)

#### Dagger

![dagger-pcb](https://github.com/tlietz/Exkeylibur/blob/main/images/dagger_pcb.png)
