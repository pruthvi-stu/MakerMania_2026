# Gear — Draft 1

**Project:** MAKERMANIA 2026 — Double Worm Gear Mechanism

**File:** cad/gear_draft_1.stl

## Version

- Draft: 1
- Date: 2026-06-05

## Description

This CAD export is the primary gear for the double worm-gear mechanism developed by the team. It is provided as an STL for 3D printing and review.

## Design Notes

- Mechanism type: double worm gear set (two worm drives sharing a common output gear)
- Intended function: high-reduction, self-locking rotary actuation with compact axial profile
- Key dimensions and constraints: modeled to mate with 8 mm worm shafts and M3 fasteners (verify in CAD before assembly)

## Materials & Print Settings (recommended)

- Material: PETG or ABS for mechanical strength; PLA for prototyping only
- Layer height: 0.2 mm
- Infill: 40% gyroid or cubic
- Perimeters: 3
- Supports: minimal — depends on orientation

## Assembly

1. Verify worm shaft alignment and bearing bores before press-fit.
2. Use M3 screws with lock washers to secure gear to hub if required.
3. Check backlash and axial spacing; shim as needed using 0.2 mm shims.

## Testing & Validation

- Run a low-speed rotation test under no-load for 1 minute to inspect for binding.
- Measure reduction ratio and compare with design target (+/- 2%).
- Perform torque test up to expected operational torque; inspect gear teeth for deformation.

## Files Included

- gear_draft_1.stl — 3D-printable STL stored in `cad/`. If the binary STL is not present, upload the provided `docs/cad_sources/Gear Wheel.stl` as `cad/gear_draft_1.stl`.

## Revision History

- 2026-06-05 — Draft 1 created; documentation added by project maintainer.

## Author

- Team: Pruthvi Jadhav • Parth Vaishampayan • Aditi Patwa
