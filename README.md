# ☀️ Solar Load Lifter

A small working model of a load lifter powered entirely by solar energy. A solar panel runs a DC motor, a gearbox reduces the speed to give high torque, and a rope-and-roller system lifts the load.

## How It Works

1. The 5 W solar PV panel produces DC current.
2. The DC motor (200 rpm) converts it into mechanical motion.
3. A compound gearbox with 6 helical gears reduces the speed to **60 rpm** and increases torque.
4. The rope passes over 3 rollers and lifts the load through a hook.
5. A DPDT switch reverses the motor for up and down movement.

The gearbox is self-braking, so the load stays in position without power.

## Specifications

| Parameter | Value |
|---|---|
| Solar panel | SLP05-12, 5 W, 17 V, 0.45 A |
| Motor speed (input) | 200 rpm |
| Gearbox output | 60 rpm |
| Gear ratio (T1/T2) | 9 / 30 |
| Measured torque | 5 kg/cm² |
| Rope | Cotton with polyester, 4 layers bonded with resin |
| Rollers | 3 (¾ section) |

## Components

- Solar PV panel
- DC motor
- Compound helical gearbox (6 gears)
- DPDT switch
- Cotton rope, rollers and spring-latch hook
- Plywood base and aluminium square-rod structure
- Brackets, nuts and bolts, wiring

## Cost

| Item | Cost (₹) |
|---|---|
| Raw materials | 5,770 |
| Machining labour | 2,112 |
| Other charges | 234 |
| Transport | 1,580 |
| **Total** | **9,696** |

## Limitations

- Output depends on sunlight, so it does not work at night without storage.
- The resin bond in the rope is not waterproof.

## References

- *Alternating Energy Sources* by S. C. Nimkar
- *Manufacturing Processes* by A. N. Patil
- *Fundamentals of Electronics* by Katre
- *Mechanical Measurement* by R. V. Jalgaonkar
