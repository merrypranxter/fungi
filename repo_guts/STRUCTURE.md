# Fungi Kingdom Database Structure

## Taxonomic Hierarchy
fungi-kingdom/
├── STRUCTURE.md              # This file
├── glossary.yaml             # Mycology terminology
├── README.md                 # Project overview
│
├── phyla/                    # Major fungal phyla
│   ├── ascomycota.yaml
│   ├── basidiomycota.yaml
│   ├── chytridiomycota.yaml
│   └── mucoromycota.yaml
│
├── classes/                  # Taxonomic classes
│   └── [phylum-name]/
│       └── [class-name].yaml
│
├── orders/                   # Taxonomic orders
│   └── [class-name]/
│       └── [order-name].yaml
│
├── families/                 # Taxonomic families
│   └── [order-name]/
│       └── [family-name].yaml
│
├── genera/                   # Genus-level entries
│   └── [family-name]/
│       └── [genus-name].yaml
│
└── species/                  # Individual species
└── [genus-name]/
└── [species-name].yaml

## File Naming Conventions
- Lowercase, hyphenated: `ascomycota.yaml`, `agaricus-bisporus.yaml`
- Species binomial: `genus-species.yaml`
- No spaces, special chars, or capitals

## Data Sources Priority
1. MycoBank (fungal nomenclature authority)
2. Index Fungorum
3. Species Fungorum
4. Field guides (regional)
5. Peer-reviewed journals
