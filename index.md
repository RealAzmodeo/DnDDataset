# D&D 2024 Data Index and Navigation Guide

This document serves as a guide to the structure and content of this D&D 2024 data repository.

## Overview

The data is organized into JSON files within the `data/` directory. Each category of information (races, classes, spells, etc.) has its own subdirectory. The goal is to create a modular and cross-referenceable database for all aspects of D&D 2024.

## Main Data Categories

-   **`/data/races/`**: Contains JSON files for each playable race/species (e.g., `human.json`, `elf.json`). Each file details ability score modifiers, traits, size, speed, etc.
-   **`/data/classes/`**: Contains JSON files for each character class (e.g., `fighter.json`). Each file includes hit dice, proficiencies, class features by level, etc.
    -   Subclasses will eventually be linked or included here.
-   **`/data/backgrounds/`**: (To be added) Will contain JSON files for character backgrounds.
-   **`/data/feats/`**: (To be added) Will contain JSON files for available feats.
-   **`/data/equipment/`**:
    -   **`/data/equipment/weapons/`**: (To be added) JSON files for different types of weapons.
    -   **`/data/equipment/armor/`**: (To be added) JSON files for different types of armor.
    -   **`/data/equipment/items/`**: (To be added) JSON files for general adventuring gear and magic items.
-   **`/data/spells/`**: Contains JSON files for spells and cantrips (e.g., `fireball.json`, `mage_hand.json`). Each file details spell level, school, casting time, range, components, duration, and effects.
-   **`/data/rules/`**: (To be added) Contains JSON files for core game rules, conditions, actions in combat, etc.

## Referencing

Data items (races, classes, spells, features, etc.) are intended to be cross-referenceable using unique string IDs (e.g., a class feature might grant a specific feat by its ID). The exact schema for these references will be refined as the database grows.

## Glossary

A `glossary.json` file is available at the root of the repository, providing definitions for common D&D terms.

## Contributing

(To be added) Guidelines for contributing to this data set.
