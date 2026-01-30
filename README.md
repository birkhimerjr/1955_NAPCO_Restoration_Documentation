# 1955 Chevrolet NAPCO 1st Series Pickup Truck

## Research, Documentation & Restoration Project

This repository documents the research, parts sourcing, and restoration of a 1955 Chevrolet 1st Series (Task Force) pickup truck equipped with a NAPCO 4-wheel drive conversion.

---

## Table of Contents

- [About the Vehicle](#about-the-vehicle)
- [What is NAPCO?](#what-is-napco)
- [Project Goals](#project-goals)
- [Repository Structure](#repository-structure)
- [Quick Reference](#quick-reference)
- [Getting Started](#getting-started)
- [Documentation Index](#documentation-index)
- [Resources](#resources)
- [Contributing](#contributing)

---

## About the Vehicle

### 1955 Chevrolet Task Force Pickup

The 1955 Chevrolet pickup marked the beginning of the iconic "Task Force" truck series (1955-1959), representing a complete redesign from the Advance Design trucks. This was a revolutionary design that set the standard for American trucks.

**Key Features:**
- **Wraparound windshield** - First in any truck, 20% more glass
- **Lowered hood line** - Improved forward visibility
- **Egg-crate grille** - Distinctive, bold styling
- **First V8 option** - 265ci Turbo-Fire available
- **Modern cab design** - Panoramic visibility

The 1955 Second Series (Task Force) trucks were introduced in March 1955 and quickly became popular with both commercial and personal-use buyers.

### Why 1955 NAPCO Trucks Are Special

| Factor | Significance |
|--------|--------------|
| **First year of Task Force** | Beginning of iconic design era |
| **NAPCO rarity** | Estimated <1,000 1955 NAPCO trucks built |
| **V8 availability** | First year Chevy offered V8 in trucks |
| **Collector demand** | Among most sought-after vintage trucks |
| **Historical importance** | Bridge between work trucks and personal vehicles |

---

## What is NAPCO?

### Northwestern Auto Parts Company (1918-1961)

**NAPCO** (Northwestern Auto Parts Company) of Minneapolis, Minnesota was the premier manufacturer of 4-wheel drive conversion kits for light-duty trucks. Their "Powr-Pak" system was unique in the automotive industry:

- **Factory-authorized** - Installed by GM dealerships
- **Professional quality** - Engineered to OEM standards
- **Warranty compatible** - Maintained factory warranty
- **Complete system** - Transfer case, front axle, and all hardware

NAPCO proved that light-duty trucks could successfully handle off-road conditions, directly influencing GM's decision to offer factory 4WD starting in 1960.

### NAPCO System Components

```
                    ┌─────────────────┐
                    │    TRANSMISSION │
                    │   (3-spd/4-spd) │
                    └────────┬────────┘
                             │
                    ┌────────▼────────┐
                    │  TRANSFER CASE  │
                    │   NAPCO 203     │
                    │   (2-speed)     │
                    └───┬─────────┬───┘
                        │         │
           Front Output │         │ Rear Output
                        │         │
              ┌─────────▼───┐ ┌───▼─────────┐
              │ FRONT AXLE  │ │  REAR AXLE  │
              │ Dana 44     │ │   (Stock)   │
              │ w/Locking   │ │             │
              │ Hubs        │ │             │
              └─────────────┘ └─────────────┘
```

| Component | Description |
|-----------|-------------|
| Transfer Case | NAPCO Model 203, 2-speed (Hi/Lo) |
| Front Axle | Dana/Spicer 44 with NAPCO steering knuckles |
| Front Driveshaft | Custom length, Spicer 1310 U-joints |
| Shifter | Floor-mounted single lever |
| Hubs | Manual locking (Warn, Cutlass, or flanges) |
| Suspension | Heavy-duty front springs, relocated hangers |

> **[Read complete NAPCO history →](docs/history/napco-history.md)**

---

## Project Goals

### Research
- [x] Document original NAPCO specifications and part numbers
- [ ] Compile factory documentation and dealer literature
- [ ] Identify VIN decoding for 1955 NAPCO trucks
- [ ] Research production numbers and surviving examples
- [ ] Document known NAPCO suppliers and service providers

### Documentation
- [ ] Create comprehensive parts catalog with cross-references
- [ ] Document disassembly with detailed photography
- [ ] Record original paint codes and trim specifications
- [ ] Map wiring diagrams and electrical systems
- [ ] Compile service manual excerpts and technical data

### Restoration
- [ ] Assess current condition and create restoration plan
- [ ] Source correct replacement parts (NOS/reproduction)
- [ ] Document restoration process step-by-step
- [ ] Track costs and supplier information
- [ ] Record completed work with before/after photos

---

## Repository Structure

```
1955_NAPCO_Restoration_Documentation/
│
├── README.md                          # This file
│
├── docs/
│   ├── history/
│   │   ├── napco-history.md           # Complete NAPCO company history
│   │   └── 1955-chevrolet-truck-history.md
│   │
│   ├── specifications/
│   │   ├── napco-technical-specifications.md  # Detailed NAPCO specs
│   │   ├── 1955-chevrolet-truck-specifications.md
│   │   └── rear-axle-specifications.md        # Rear diff & axle specs
│   │
│   ├── parts/
│   │   └── parts-catalog.md           # Parts inventory & tracking
│   │
│   └── manuals/
│       └── README.md                  # Service manual index
│
├── photos/
│   ├── README.md                      # Photo organization guide
│   ├── original/                      # Initial condition photos
│   ├── disassembly/                   # Teardown documentation
│   ├── restoration/                   # Work in progress
│   └── completed/                     # Finished restoration
│
├── resources/
│   ├── suppliers/
│   │   └── parts-suppliers.md         # Vendor directory
│   │
│   ├── literature/
│   │   └── README.md                  # Period literature index
│   │
│   └── references/
│       └── vin-decoder.md             # VIN interpretation guide
│
└── logs/
    ├── work-log.md                    # Restoration diary
    └── expenses.md                    # Cost tracking
```

---

## Quick Reference

### Key Specifications (1955 Chevrolet 3100 NAPCO)

| Specification | Detail |
|--------------|--------|
| **Model Year** | 1955 Second Series (Task Force) |
| **Series** | 3100 (1/2 ton) |
| **Wheelbase** | 114 inches |
| **Engine Options** | 235ci I6 (123hp), 265ci V8 (145hp) |
| **Transmission** | 3-speed manual (std), 4-speed optional |
| **NAPCO Option** | Powr-Pak 4x4 conversion |
| **Transfer Case** | NAPCO Model 203, 2-speed |
| **Front Axle** | Dana/Spicer 44 |
| **Front Axle Ratio** | Match rear (3.73, 4.10, 4.56) |
| **Ground Clearance** | ~8.5" (vs 7.5" 2WD) |

### NAPCO Gear Ratios

| Position | Ratio | Use |
|----------|-------|-----|
| 2WD High | 1.00:1 | Normal driving |
| 4WD High | 1.00:1 | Light off-road |
| 4WD Low | 1.94:1 | Heavy off-road |

### Critical Fluid Specifications

| Component | Capacity | Type |
|-----------|----------|------|
| Transfer Case | 2.5 pints | 80W-90 GL-4 |
| Front Differential | 2.5 pints | 80W-90 GL-5 |
| Rear Differential | 3.5 pints | 80W-90 GL-5 |

> **[Complete specifications →](docs/specifications/napco-technical-specifications.md)**

---

## Getting Started

### For New Restorers

1. **Read the history** - Understand what makes your truck special
   - [NAPCO History](docs/history/napco-history.md)
   - [1955 Chevrolet Truck History](docs/history/1955-chevrolet-truck-history.md)

2. **Document your truck** - Before touching anything
   - Photograph everything (see [Photo Guide](photos/README.md))
   - Record all serial numbers (see [VIN Decoder](resources/references/vin-decoder.md))
   - Assess current condition

3. **Understand the specifications**
   - [NAPCO Technical Specifications](docs/specifications/napco-technical-specifications.md)
   - [1955 Chevrolet Specifications](docs/specifications/1955-chevrolet-truck-specifications.md)

4. **Start tracking**
   - Log work sessions in [Work Log](logs/work-log.md)
   - Track expenses in [Expense Tracker](logs/expenses.md)
   - Inventory parts in [Parts Catalog](docs/parts/parts-catalog.md)

5. **Find parts and suppliers**
   - [Parts Suppliers Directory](resources/suppliers/parts-suppliers.md)

---

## Documentation Index

### History & Background
| Document | Description |
|----------|-------------|
| [NAPCO History](docs/history/napco-history.md) | Complete history of Northwestern Auto Parts Company |
| [1955 Truck History](docs/history/1955-chevrolet-truck-history.md) | History of the Task Force design |

### Technical Specifications
| Document | Description |
|----------|-------------|
| [NAPCO Specifications](docs/specifications/napco-technical-specifications.md) | Transfer case, front axle, gear ratios, torque specs |
| [1955 Truck Specifications](docs/specifications/1955-chevrolet-truck-specifications.md) | Engine, transmission, dimensions, colors |
| [Rear Axle Specifications](docs/specifications/rear-axle-specifications.md) | Differential, gear ratios, bearings, rebuild specs |

### Parts & Sourcing
| Document | Description |
|----------|-------------|
| [Parts Catalog](docs/parts/parts-catalog.md) | Complete parts inventory tracker |
| [Suppliers Directory](resources/suppliers/parts-suppliers.md) | Vendor contact information |

### Reference Materials
| Document | Description |
|----------|-------------|
| [VIN Decoder](resources/references/vin-decoder.md) | Serial number interpretation |
| [Literature Index](resources/literature/README.md) | Period documentation collection |
| [Manuals Index](docs/manuals/README.md) | Service manual references |

### Project Tracking
| Document | Description |
|----------|-------------|
| [Work Log](logs/work-log.md) | Restoration session diary |
| [Expense Tracker](logs/expenses.md) | Cost tracking by category |
| [Photo Guide](photos/README.md) | Photo organization system |

---

## Resources

### NAPCO Community
- NAPCO 4x4 Registry
- The 1947-Present Chevrolet & GMC Truck Message Board
- Vintage NAPCO Facebook groups
- NAPCO owners' email lists

### Technical References
- 1955 Chevrolet Truck Shop Manual
- NAPCO Installation and Service Manual
- Dana/Spicer Axle Service Manual
- GM Parts Counter Catalogs

### Major Parts Suppliers
- **LMC Truck** - General truck parts
- **Brothers Trucks** - Task Force specialists
- **Classic Parts of America** - Comprehensive catalog
- **Randy's Ring & Pinion** - Axle components

> **[Complete suppliers list →](resources/suppliers/parts-suppliers.md)**

### Recommended Reading
- *Chevrolet Pickups 1946-1972* by John Gunnell
- Period truck magazines (archived)
- Hemmings publications

---

## Vehicle Documentation

### Record Your Truck's Information

| Item | Value | Notes |
|------|-------|-------|
| **VIN** | | |
| **Engine Number** | | |
| **Body Number** | | |
| **NAPCO Transfer Case #** | | |
| **NAPCO Axle #** | | |
| **Paint Code** | | |
| **Trim Code** | | |
| **Date Acquired** | | |
| **Purchase Price** | | |
| **Current Mileage** | | |
| **Known History** | | |

---

## Contributing

This is a personal restoration project, but contributions of historical information, technical corrections, and NAPCO-specific knowledge are welcome.

### Types of Contributions Welcomed
- Historical documentation and photos
- Technical corrections and clarifications
- Period-correct specifications
- NAPCO production information
- Parts cross-reference data
- Supplier recommendations

### How to Contribute
- Open an issue with information or corrections
- Submit pull requests with documentation updates
- Share through vintage truck forums and communities

---

## Acknowledgments

This project builds on the knowledge shared by the vintage truck community, NAPCO enthusiasts, and generations of restorers who have preserved these remarkable vehicles.

---

## License

This documentation is for personal research and educational purposes. Historical documents and images remain property of their respective copyright holders.

---

## Project Status

| Phase | Status | Notes |
|-------|--------|-------|
| Repository Setup | Complete | Documentation structure created |
| Historical Research | In Progress | Ongoing |
| Vehicle Documentation | Not Started | Pending photo session |
| Disassembly | Not Started | |
| Parts Sourcing | Not Started | |
| Restoration | Not Started | |
| Reassembly | Not Started | |
| Completion | Not Started | |

---

*Project Started: January 2026*
*Last Updated: January 2026*

---

> *"A NAPCO truck is not just a vehicle—it's a piece of American engineering history that proved light-duty trucks could go anywhere."*
