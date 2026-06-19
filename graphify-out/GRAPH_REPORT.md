# Graph Report - .  (2026-06-19)

## Corpus Check
- 42 files · ~376,602 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 270 nodes · 435 edges · 14 communities (11 shown, 3 thin omitted)
- Extraction: 89% EXTRACTED · 11% INFERRED · 0% AMBIGUOUS · INFERRED: 50 edges (avg confidence: 0.8)
- Token cost: 39,000 input · 4,236 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Memory & Storage Hierarchy|Memory & Storage Hierarchy]]
- [[_COMMUNITY_Electron Microscopy (TEMSEM)|Electron Microscopy (TEM/SEM)]]
- [[_COMMUNITY_Superlattices & Metavalent Bonding|Superlattices & Metavalent Bonding]]
- [[_COMMUNITY_PCM Materials & Phase Transitions|PCM Materials & Phase Transitions]]
- [[_COMMUNITY_Nanophotonics & Plasmonic PCM|Nanophotonics & Plasmonic PCM]]
- [[_COMMUNITY_GST Alloys & Optical Storage|GST Alloys & Optical Storage]]
- [[_COMMUNITY_PCM Devices & Neuromorphic Computing|PCM Devices & Neuromorphic Computing]]
- [[_COMMUNITY_Crystallization & Endurance|Crystallization & Endurance]]
- [[_COMMUNITY_Thermal Energy Storage Applications|Thermal Energy Storage Applications]]
- [[_COMMUNITY_Electronic Switching & Drift|Electronic Switching & Drift]]
- [[_COMMUNITY_Scanning Probe Microscopy|Scanning Probe Microscopy]]
- [[_COMMUNITY_Bi2Te3|Bi2Te3]]
- [[_COMMUNITY_XRDXRR|XRD/XRR]]
- [[_COMMUNITY_Wiki Starter Note|Wiki Starter Note]]

## God Nodes (most connected - your core abstractions)
1. `Ge2Sb2Te5 (GST-225)` - 23 edges
2. `Phase-Change Material (PCM)` - 22 edges
3. `In3SbTe2 (IST)` - 16 edges
4. `Phase-Change Superlattice` - 16 edges
5. `Phase-change materials for rewriteable data storage (Wuttig & Yamada, Nature Materials 2007)` - 13 edges
6. `Sb2Te3` - 12 edges
7. `Optical Switching of GeSbTe-based Phase Change Superlattices with In2Te3 (Widmann Bachelor Thesis)` - 11 edges
8. `Thermal Energy Storage (TES)` - 10 edges
9. `Piperidou 2025 - GST-124/Sb2Te3 Superlattices Thesis` - 10 edges
10. `Metavalent Bonding` - 10 edges

## Surprising Connections (you probably didn't know these)
- `Scanning Transmission Electron Microscope (STEM)` --semantically_similar_to--> `Scanning Electron Microscopy (SEM)`  [INFERRED] [semantically similar]
  raw/yt_6ad47fda5c0c.txt → Raw/Files/Bachelorarbeit_FINAL_RW_final_260513_130841.pdf
- `In3SbTe2 (IST)` --semantically_similar_to--> `Ge-Sb-Te (GST) Alloys`  [INFERRED] [semantically similar]
  Raw/Sources/conrads-2025-ist-review.md → Raw/Files/The plasmonic PCM In3SbTe2 for nanophotonics.pdf
- `Metavalent Bonding` --semantically_similar_to--> `Rocksalt-like crystal structure with vacancies`  [INFERRED] [semantically similar]
  Raw/Sources/piperidou-2025-gst-sb2te3-superlattices.md → Raw/Files/nmat2009.pdf
- `Amorphous-to-Crystalline Phase Transition` --semantically_similar_to--> `Crystallization`  [INFERRED] [semantically similar]
  Raw/Sources/thermally-induced-nanoscale-phase-change-in-chalcogenide-glass-cr2ge2te6-reveale.md → Raw/Files/nmat2009.pdf
- `Phase Change Memory (PCM)` --semantically_similar_to--> `Phase-change materials for rewriteable data storage (Wuttig & Yamada, Nature Materials 2007)`  [INFERRED] [semantically similar]
  Raw/yt_1a8aeb6ce67e.txt → Raw/Files/nmat2009.pdf

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Desktop Memory Hierarchy Tiers** — raw_yt_1a8aeb6ce67e_registers, raw_yt_1a8aeb6ce67e_cache_memory, raw_yt_1a8aeb6ce67e_dram, raw_yt_1a8aeb6ce67e_ssd, raw_yt_1a8aeb6ce67e_hdd, raw_yt_1a8aeb6ce67e_internet_cloud [EXTRACTED 1.00]
- **Volatile Memory Tiers** — raw_yt_1a8aeb6ce67e_registers, raw_yt_1a8aeb6ce67e_sram, raw_yt_1a8aeb6ce67e_dram, raw_yt_1a8aeb6ce67e_vram [INFERRED 0.85]
- **AI Server Memory and Storage Stack** — raw_yt_1a8aeb6ce67e_hbm, raw_yt_1a8aeb6ce67e_ddr5_rdimm, raw_yt_1a8aeb6ce67e_cxl, raw_yt_1a8aeb6ce67e_nvme_ssd [INFERRED 0.85]

## Communities (14 total, 3 thin omitted)

### Community 0 - "Memory & Storage Hierarchy"
Cohesion: 0.06
Nodes (46): Interface-Controlled Thermal Properties, Phase-Change Memory (PCM/PCRAM), Interface-Controlled Thermal Properties of Ultra-Thin Chalcogenide PCM Devices, 1T1C Memory Cell, 3D NAND Flash, AI Accelerator / AI Processor, AI Memory Hierarchy, CPU Cache Memory (+38 more)

### Community 1 - "Electron Microscopy (TEM/SEM)"
Cohesion: 0.07
Nodes (34): Scanning Electron Microscopy (SEM), Transmission Electron Microscopy (TEM), Aperture, CMOS Camera, Condenser Lens, Deflection Coils, Diffraction Limit of Light, Electron Acceleration (70% Speed of Light) (+26 more)

### Community 2 - "Superlattices & Metavalent Bonding"
Cohesion: 0.12
Nodes (33): Atom Probe Tomography (APT), Bond Confinement Effect, Rationale: Thinner SbTe Layers Increase Covalency and Improve Switching, Electron Backscatter Diffraction (EBSD), Electro-thermal confinement, Ge1Sb2Te4 (GST-124), Ge-Sb-Te (GST) Alloys, Ge1Sb2Te4 (GST-124) (+25 more)

### Community 3 - "PCM Materials & Phase Transitions"
Cohesion: 0.09
Nodes (30): Ab Initio Molecular Dynamics (AIMD), Amorphous-to-Crystalline Phase Transition, Chalcogenide Materials, Cr2Ge2Te6 (CrGT), Density Functional Theory (DFT) / First-Principles Calculations, Electrospinning, Latent Heat Storage (LHS), Materials Project (MP) Database (+22 more)

### Community 4 - "Nanophotonics & Plasmonic PCM"
Cohesion: 0.08
Nodes (29): Direct Laser Writing / Optical Programming, Emissivity-Shaping / Thermal Emission Control, Geometric Phase Metasurface, In3SbTe2 (IST), In Situ TEM of PCM, Laser Switching Setup (LSS), Metasurface, Mid-Infrared Spectral Range (+21 more)

### Community 5 - "GST Alloys & Optical Storage"
Cohesion: 0.11
Nodes (27): Atomic Force Microscopy (AFM), Ag5In5Sb60Te30 (AIST), Amine-Thiol Cosolvent (Ethylenediamine/Ethanedithiol), Chemical Solution Deposition, Extended X-ray Absorption Fine Structure (EXAFS), Ge2Sb2Te5 (GST-225), Ge2Sb2Se4Te1 (Ge-Sb-Se-Te), GeTe (+19 more)

### Community 6 - "PCM Devices & Neuromorphic Computing"
Cohesion: 0.15
Nodes (18): Elemental Te Selector Switch, Joule Heating, Machine-Learned Interatomic Potentials (GAP/ACE), Neuromorphic / In-Memory Computing, Nucleation- vs Growth-Dominated Crystallization, Metastable Rocksalt Crystalline Phase, Thermal Engineering / Confinement for RESET Current Reduction, Ostwald's Rule as PCM Screening Framework (+10 more)

### Community 7 - "Crystallization & Endurance"
Cohesion: 0.13
Nodes (17): Amorphization, Amorphous phase, Crystal-crystal phase transition mechanism, Crystalline phase, Crystallization, Crystallization Temperature, Lightweight-Element Doping (N, O, C), Endurance / Cycling Durability (+9 more)

### Community 8 - "Thermal Energy Storage Applications"
Cohesion: 0.24
Nodes (13): Latent Heat Storage, Thermal Energy Storage (TES), Freeman Dissertation: Additive Manufacturing for PC Thermal Energy Storage, Muhabie et al.: Advances in PCMs for TES (SPCM Review), Supramolecular Phase Change Materials (SPCMs), BioPCM ENRG Blanket (Phase Change Solutions), Sunamp Thermino Heat Battery, Are Phase Change Materials the Future of Water Heaters? (Undecided) (+5 more)

### Community 9 - "Electronic Switching & Drift"
Cohesion: 0.24
Nodes (11): Activation Energy of Charge Transport, Resistance Drift, Threshold Switching, Electronic Switching in Phase-Change Materials (Bruns Dissertation), Boniardi (2009) Drift in Ge2Sb2Te5, Mushroom Cell PCM Device, Ovshinsky (1968) Reversible Electrical Switching in Disordered Structures, Pulsed Electrical Tester (PET) (+3 more)

### Community 10 - "Scanning Probe Microscopy"
Cohesion: 0.31
Nodes (9): Atomic Force Microscopy (AFM), Nanoscale Thermal Mapping, Quantum Tunneling Effect, Scanning Probe Microscopy (SPM), Scanning Tunneling Microscopy (STM), Scanning Probe Techniques (Book Excerpt), Atomic Force Microscopy for Cross-Disciplinary Materials Research, Protocol for Nanoscale Thermal Mapping using AFM with PCM (+1 more)

## Knowledge Gaps
- **67 isolated node(s):** `Machine-Learned Interatomic Potentials (GAP/ACE)`, `Vapor-Liquid-Solid (VLS) Growth`, `In Situ TEM of PCM`, `BioPCM ENRG Blanket (Phase Change Solutions)`, `Peak Shaving & Ancillary Services with PCM-TES` (+62 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **3 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Phase-Change Material (PCM)` connect `PCM Materials & Phase Transitions` to `Memory & Storage Hierarchy`, `Superlattices & Metavalent Bonding`, `Nanophotonics & Plasmonic PCM`, `GST Alloys & Optical Storage`, `PCM Devices & Neuromorphic Computing`, `Crystallization & Endurance`?**
  _High betweenness centrality (0.321) - this node is a cross-community bridge._
- **Why does `TEM of Sb2Te3 Thin Films and GeTe/Sb2Te3 Superlattices (Momand)` connect `Superlattices & Metavalent Bonding` to `Electron Microscopy (TEM/SEM)`, `GST Alloys & Optical Storage`?**
  _High betweenness centrality (0.234) - this node is a cross-community bridge._
- **Are the 2 inferred relationships involving `Ge2Sb2Te5 (GST-225)` (e.g. with `Ge1Sb2Te4 (GST-124)` and `Ge-Sb-Te (GST) Material System`) actually correct?**
  _`Ge2Sb2Te5 (GST-225)` has 2 INFERRED edges - model-reasoned connections that need verification._
- **Are the 2 inferred relationships involving `In3SbTe2 (IST)` (e.g. with `Ge-Sb-Te (GST) Alloys` and `Sb2S3 (Antimony Trisulfide)`) actually correct?**
  _`In3SbTe2 (IST)` has 2 INFERRED edges - model-reasoned connections that need verification._
- **Are the 3 inferred relationships involving `Phase-change materials for rewriteable data storage (Wuttig & Yamada, Nature Materials 2007)` (e.g. with `Optical Switching of GeSbTe-based Phase Change Superlattices with In2Te3 (Widmann Bachelor Thesis)` and `Laser-induced phase transitions of Ge2Sb2Te5 thin films (Chu et al., Optics Express 2010)`) actually correct?**
  _`Phase-change materials for rewriteable data storage (Wuttig & Yamada, Nature Materials 2007)` has 3 INFERRED edges - model-reasoned connections that need verification._
- **What connects `Machine-Learned Interatomic Potentials (GAP/ACE)`, `Vapor-Liquid-Solid (VLS) Growth`, `In Situ TEM of PCM` to the rest of the system?**
  _71 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Memory & Storage Hierarchy` be split into smaller, more focused modules?**
  _Cohesion score 0.06086956521739131 - nodes in this community are weakly interconnected._