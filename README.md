# EXA-Lype

*Exaporeomai, Lýpe. A souls-like dark fantasy prototype built in Unreal Engine 5.*

## About

Exaporeomai is a gothic dark-fantasy souls-like set in a world plunged into darkness after the death of the sun god Kýrios. The world has 9 territories, each corrupted by an extreme human emotion. This repository holds the TP1 prototype, the first territory, Lýpe (Grief). Built solo over 6 weeks as a first project in Unreal Engine 5 and Blueprint, inspired by Bloodborne, Dark Souls III, and Lords of the Fallen.

## Lýpe (Grief)

| Theme | Corruption | Role |
|---|---|---|
| Lýpe, Grief | Shock / Pain | Introduction to the world and the catastrophe. The world is in mourning. |

**Opening, The Dock.** 
The player wakes on a dock after a cinematic revealing how they got there. An expedition was sent to investigate the island after a god's fall, and the ship wrecked in a storm. Few survived, and those who reached shore were met by dangerous monsters and fled into the dark. An elder dragged the player to safety and now sits exhausted further down the dock. He becomes the first NPC, offering context, the main quest, and a choice of starting weapon (sword, gun, or greatsword).

**The Drowned Zone / Port Market.** 
A flooded port where rising water slows the player's movement, a mechanic built to make grief's weight *felt* rather than just described. The Drowned attack on sight or ambush when the player's guard is down.

**The Town.** - Two enemy archetypes patrol the streets.
- **The Mourning Wanderers**, slow and dissociated, seemingly harmless until proximity triggers a violent response.
- **The Hollow Sentinels**, aggressive survivors guarding spaces that no longer exist, fast and forceful on engagement.

**The Key.** A puzzle stage gates progress. The player must recover a key to unlock the mechanism opening the gates toward the Cathedral.

**Cathedral and Cemetery (Boss Arena).** Visible from the starting dock and partially hidden behind the town's rooftops (pyramid disclosure), the Cathedral is where a grieving man becomes possessed and transforms into **Korax**, shattering a window that drops both player and boss into the adjoining Cemetery.
- **Form 1**, Korax turns black, crow-like but not fully transformed, fast and erratic.
- **Form 2**, more corrupted by grief and more crow-like, uses AOE wing attacks.

Defeating Korax activates the mechanism leading out of Lýpe.

## Mechanics

- **Water as grief**, a slow zone affecting both player and enemies, used to express the emotional weight of the territory through movement rather than UI or dialogue.
- **Pyramid disclosure**, the boss arena is visible from the very first area, teased through the town's geometry long before it's reachable.
- **Two-phase boss encounter**, Korax escalates from a fast, semi-transformed state into a more corrupted, AOE-heavy second phase.
- **Weapon choice at the first NPC**, sword, gun, or greatsword, set early to shape the rest of the playthrough.

## Built With

- **Unreal Engine 5.8**
- **Blueprint visual scripting** (no C++)
- Asset packs from Polytope Studio (modular armors), nikoff (dead body poses), Unreal water plane assets, and a level prototyping kit

## Getting Started

1. Install **Unreal Engine 5.8**.
2. Clone this repository.
3. Open `EXA.uproject`.
4. Open the `Lype` (or `Lype_WP`) map under `Content/EXA` and hit Play.

## Links

- [Level design write-up / portfolio page](https://dev.timmatane.ca/etudiants/2024/savinovae/portfolio/projets/exa-poreomai-leveldesign.html)

## Author

**Elena "Lena" Savinova**, Techniques d'intégration multimédia, Cégep de Matane
[je.savelena@gmail.com](mailto:je.savelena@gmail.com) | [LinkedIn](https://linkedin.com/in/elena-savinova-lena/)
