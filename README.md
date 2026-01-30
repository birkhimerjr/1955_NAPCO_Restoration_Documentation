# 1955 Chevrolet NAPCO 1st Series Pickup Truck

## Research, Documentation & Restoration Project

This repository documents the research, parts sourcing, and restoration of a **1955 Chevrolet 1st Series (Advance Design)** pickup truck equipped with a NAPCO 4-wheel drive conversion.

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

### 1955 Chevrolet 1st Series (Advance Design)

The 1955 First Series trucks are the **final year of the Advance Design generation** (1947-1955), produced from late 1954 through early 1955 before the Second Series "Task Force" trucks were introduced in March 1955. These trucks represent the pinnacle of the Advance Design era.

**Key Features:**
- **One-piece curved windshield** - Updated design introduced in 1954
- **Alligator hood** - Traditional front-opening hood
- **5-bar grille** - Horizontal bar grille design
- **Proven inline-6 engine** - 235ci Thriftmaster
- **Rugged design** - Eight years of refinement

### 1955 First Series vs Second Series

| Feature | 1955 First Series (Your Truck) | 1955 Second Series |
|---------|-------------------------------|-------------------|
| **Also Known As** | Advance Design | Task Force |
| **Production Period** | Late 1954 - Early 1955 | March 1955 - Late 1955 |
| **Windshield** | One-piece curved | Wraparound one-piece |
| **Hood** | Alligator (front-hinged) | Rear-hinged |
| **Grille** | 5-bar horizontal | Egg-crate pattern |
| **V8 Option** | Not available | First year available |
| **Dashboard** | 1954 carryover | All-new design |

### Why 1955 First Series NAPCO Trucks Are Special

| Factor | Significance |
|--------|--------------|
| **Final Advance Design year** | Last of an iconic 8-year design run |
| **Extreme rarity with NAPCO** | Very few First Series trucks received NAPCO |
| **Transitional year** | Bridge between two great truck eras |
| **Collector demand** | Highly sought after by enthusiasts |
| **Historical importance** | Represents peak of Advance Design evolution |

---

## What is NAPCO?

### Northwestern Auto Parts Company (1918-1961)

**NAPCO** (Northwestern Auto Parts Company) of Minneapolis, Minnesota was the premier manufacturer of 4-wheel drive conversion kits for light-duty trucks. Their "Powr-Pak" system was unique in the automotive industry:

- **Factory-authorized** - Installed by GM dealerships
- **Professional quality** - Engineered to OEM standards
- **Warranty compatible** - Maintained factory warranty
- **Complete system** - Transfer case, front axle, and all hardware

NAPCO began offering conversions for Chevrolet trucks in 1954, making 1955 First Series trucks among the earliest Chevrolet applications.

### NAPCO System Components

```
                    ┌─────────────────┐
                    │    TRANSMISSION │
                    │   (3-spd/4-spd) │
                    └────────┬────────┘
                             │
                    ┌────────▼────────┐
                    │  TRANSFER CASE  │
                    │     Spicer      │
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
| Transfer Case | Spicer with Dual-Range Hi-Lo, 2-speed |
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
- [ ] Identify VIN decoding for 1955 First Series NAPCO trucks
- [ ] Research production numbers and surviving examples
- [ ] Document known NAPCO suppliers and service providers
- [ ] Document differences between 1954 and 1955 First Series

### Documentation
- [ ] Create comprehensive parts catalog with cross-references
- [ ] Document disassembly with detailed photography
- [ ] Record original paint codes and trim specifications
- [x] Map wiring diagrams and electrical systems *(1954-1955 diagrams downloaded)*
- [x] Compile service manual excerpts and technical data *(Assembly manual downloaded)*

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
│   │   ├── 1955-first-series-history.md    # Advance Design history
│   │   └── 1955-second-series-history.md   # Task Force reference
│   │
│   ├── specifications/
│   │   ├── napco-technical-specifications.md  # Detailed NAPCO specs
│   │   ├── 1955-first-series-specifications.md # Your truck's specs
│   │   └── rear-axle-specifications.md        # Rear diff & axle specs
│   │
│   ├── parts/
│   │   └── parts-catalog.md           # Parts inventory & tracking
│   │
│   └── manuals/
│       ├── README.md                  # Service manual index
│       ├── wiring/                    # Wiring diagrams (1954-1955)
│       ├── assembly/                  # Factory assembly manuals
│       ├── operators/                 # Owner's manuals
│       └── napco/                     # NAPCO-specific documentation
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

### Key Specifications (1955 Chevrolet 1st Series 3100 NAPCO)

| Specification | Detail |
|--------------|--------|
| **Model Year** | 1955 First Series (Advance Design) |
| **Series** | 3100 (1/2 ton) |
| **Wheelbase** | 114 inches |
| **Engine** | 235ci Thriftmaster I6 (112hp) |
| **Transmission** | 3-speed manual (std), 4-speed optional |
| **NAPCO Option** | Powr-Pak 4x4 conversion |
| **Transfer Case** | Spicer with Dual-Range Hi-Lo |
| **Front Axle** | Dana/Spicer 44 |
| **Windshield** | One-piece curved glass |
| **Hood Type** | Alligator (front-opening) |

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

> **[Complete specifications →](docs/specifications/1955-first-series-specifications.md)**

---

## Getting Started

### For New Restorers

1. **Read the history** - Understand what makes your truck special
   - [NAPCO History](docs/history/napco-history.md)
   - [1955 First Series History](docs/history/1955-first-series-history.md)

2. **Document your truck** - Before touching anything
   - Photograph everything (see [Photo Guide](photos/README.md))
   - Record all serial numbers (see [VIN Decoder](resources/references/vin-decoder.md))
   - Assess current condition

3. **Understand the specifications**
   - [NAPCO Technical Specifications](docs/specifications/napco-technical-specifications.md)
   - [1955 First Series Specifications](docs/specifications/1955-first-series-specifications.md)
   - [Rear Axle Specifications](docs/specifications/rear-axle-specifications.md)

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
| [1955 First Series History](docs/history/1955-first-series-history.md) | History of your Advance Design truck |
| [1955 Second Series History](docs/history/1955-second-series-history.md) | Task Force reference (for comparison) |

### Technical Specifications
| Document | Description |
|----------|-------------|
| [NAPCO Specifications](docs/specifications/napco-technical-specifications.md) | Transfer case, front axle, gear ratios, torque specs |
| [1955 First Series Specifications](docs/specifications/1955-first-series-specifications.md) | Engine, transmission, dimensions, colors |
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

### Advance Design Community
- Advance Design trucks forum
- The 1947-Present Chevrolet & GMC Truck Message Board
- NAPCO 4x4 Registry
- Vintage NAPCO Facebook groups

### Technical References
- 1955 Chevrolet Truck Shop Manual (First Series)
- NAPCO Installation and Service Manual
- Dana/Spicer Axle Service Manual
- GM Parts Counter Catalogs

### Major Parts Suppliers
- **LMC Truck** - General truck parts
- **Classic Parts of America** - Advance Design specialists
- **Jim Carter Truck Parts** - Used and NOS parts
- **Mar-K Quality Parts** - Bed wood and metal

> **[Complete suppliers list →](resources/suppliers/parts-suppliers.md)**

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
- Period-correct specifications for 1955 First Series
- NAPCO production information
- Parts cross-reference data
- Supplier recommendations

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

> *"A 1955 First Series NAPCO truck represents the perfect combination of proven Advance Design reliability with go-anywhere 4-wheel drive capability—a rare piece of American automotive history."*
