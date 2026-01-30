# METHODOLOGY.md  
## Venus Cooling Project — Analytical Framework

This document defines the shared analytical methodology used across all repositories in the **Venus Cooling Project**.

The goal is **consistency**, not precision.  
All analyses are conducted at the **order-of-magnitude** level unless explicitly stated otherwise.

---

## Core Philosophy

Planetary-scale engineering problems fail or succeed on:
- **Energy balance**
- **Mass**
- **Timescale**
- **Continuity**

If any one of these is violated by several orders of magnitude, the concept is considered non-viable *regardless of engineering cleverness*.

---

## Guiding Questions (Asked in Every Repo)

Each concept is evaluated by answering:

1. **What is being changed?**
   - Temperature
   - Pressure
   - Composition
   - Incoming solar flux
   - Outgoing thermal radiation

2. **Where does the energy go?**
   - Radiated to space
   - Stored as heat
   - Converted to work
   - Reabsorbed locally

3. **What is the mass involved?**
   - Atmosphere affected
   - Material added or removed
   - Infrastructure mass

4. **On what timescale?**
   - Instantaneous
   - Years
   - Millennia
   - Geological

5. **Is the process continuous or impulsive?**
   - Continuous systems must operate indefinitely
   - Impulsive systems usually thermalize and rebound

---

## Energy Accounting (First-Order)

All projects reduce to variations of:

### Planetary Energy Balance

Incoming Solar Power
≈
Outgoing Thermal Radiation + Stored Energy Change


Cooling Venus requires **sustained net export of energy**, not just redistribution.

Any process that:
- Adds heat
- Temporarily absorbs heat
- Rearranges matter without exporting energy

…is insufficient on its own.

---

## Atmospheric Treatment

Venus’s atmosphere is treated as:
- A **compressible fluid**
- In **hydrostatic equilibrium**
- With **optically thick CO₂** dominating radiative behavior

Common simplifications:
- Ideal gas law for first-pass estimates
- Scale height approximations
- Column mass calculations

If a proposal ignores:
- Recompression
- Choked flow
- Reabsorption of radiation

…it is flagged explicitly.

---

## Radiative Assumptions

- Surface and lower atmosphere are **optically thick**
- Radiative cooling primarily occurs in **upper atmospheric layers**
- Increasing emission at depth usually increases **reabsorption**, not net loss

Lasers, radiators, and exotic emitters are evaluated on **net escaping photons**, not local emission rates.

---

## Mass-Based Arguments

Many concepts fail by mass alone.

Typical checks:
- Compare required mass to:
  - Venus atmosphere (~10²⁰ kg)
  - Earth oceans (~10²¹ kg)
  - Planetary crustal masses
- Convert abstract masses into intuition-builders (vehicles, mountains, planets)

If the mass approaches planetary scales, the concept is treated as **non-viable by construction**.

---

## Timescale Discipline

Cooling is meaningless without a timescale.

Every repo answers:
- Cooling per second
- Cooling per year
- Total time required

If a method:
- Requires millions of years → geological, not engineering
- Requires instantaneous action → usually fantasy or destructive

---

## Failure Mode Emphasis

Negative results are **primary outcomes**, not side notes.

Each repo identifies:
- The dominant failure mode
- Why intuition breaks
- Whether the failure is:
  - Energy-limited
  - Mass-limited
  - Law-of-physics-limited

This is intentional: understanding *why* ideas fail is the educational objective.

---

## Fantasy Concepts (Explicit Handling)

Fantasy or impossible assumptions are allowed **only** when:
- Clearly labeled
- Quantified anyway
- Used to isolate constraints

Even with impossible tools, real limits (energy, pressure, gravity) often remain dominant.

---

## Consistency Rule

All repositories must:
- Reference this methodology
- Declare deviations explicitly
- Use shared constants from `ASSUMPTIONS.md`
- Avoid precision theater (no false accuracy)

Details such as assumptions, constants, and conversion frameworks are intentionally
maintained within individual repositories to preserve local clarity and flexibility.

---

## Summary

The Venus Cooling Project is not about proposing solutions.

It is about answering one question repeatedly and honestly:

> *“Does this idea survive contact with scale?”*

Most do not—and that is the point.

---

