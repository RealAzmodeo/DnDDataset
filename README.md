# D&D 2024 Modular Data Repository

## Purpose

This repository aims to create a comprehensive, modular, and easily navigable database for Dungeons & Dragons 2024. The goal is to capture all aspects of the game – from player options like races, classes, and spells, to core rules and mechanics – in a structured and cross-referenceable format using JSON files.

This project is intended for developers, content creators, and D&D enthusiasts who need a machine-readable and well-organized source of D&D information.

## Structure Overview

All data is stored in JSON files, primarily located within the `data/` directory. The structure is designed to be intuitive:

-   **`data/`**: Contains all core game data.
    -   `races/`: Information on playable races/species.
    -   `classes/`: Details on character classes and their features.
    -   `backgrounds/`: Character background options.
    -   `feats/`: Available feats.
    -   `equipment/`:
        -   `weapons/`: Weapon statistics and properties.
        -   `armor/`: Armor details.
        -   `items/`: Adventuring gear and magic items.
    -   `spells/`: Descriptions and mechanics for spells and cantrips.
    -   `rules/`: Core game rules, conditions, actions, etc.

-   **`glossary.json`**: A JSON file defining common D&D terminology. Each term has a corresponding definition.
-   **`index.md`**: A markdown file that serves as a detailed guide to the data, explaining the structure of different data types and how to find specific information.

## How to Use

-   **Browse the `data/` directory:** Navigate through the subdirectories to find the JSON files relevant to your needs.
-   **Consult `index.md`:** For a more detailed understanding of the file organization and content.
-   **Use `glossary.json`:** To look up definitions of common D&D terms.

## Data Format & Referencing

Each entity (e.g., a spell, a class feature, a race) is intended to have a unique string `id`. This `id` will be used for cross-referencing between different JSON files. For example, a class might reference a list of spell `id`s it can learn, or a feat might reference a specific racial trait `id` as a prerequisite. The specific schemas for each data type are evolving and can be inferred from the sample files provided.

## Current Status

This repository is in its initial stages of development. The core structure is being established, and sample data is being added for key categories.

## Contributing (Future)

Guidelines for contributing new data, suggesting schema improvements, or reporting issues will be added in the future. The goal is to make this a community-driven resource.

---

*This project is for informational and developmental purposes. Dungeons & Dragons is a trademark of Wizards of the Coast.*
