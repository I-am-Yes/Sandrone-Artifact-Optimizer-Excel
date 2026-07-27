# Sandrone Stellar-conduct Damage Calculator & Artifacts Stats Optimizer
This is an Excel project.

<img width="1295" height="1072" alt="image" src="https://github.com/user-attachments/assets/61f73ec0-0c79-4edb-b1c3-72241890b270" />

---

# Features

- Sandrone damage calculator (Stellar-conduct)
- Sandrone's Artifact main stat and substat optimizer
- Brute-force simulation of every possible artifact combination
- Calculates highest achievable damage based on:
  - Level
  - Weapon
  - Team buffs
  - Artifact stats
  - ATK / EM / CRIT DMG balance
- Shows recommended stat priorities
- Displays how close your current build is compared to the optimized build

---


## How to use:

- Open the Excel file; you should see the whole project, especially the main sheet name: [Interface] (already focused on this sheet by default)
- Customize your Level and Weapon (dropdown list)
- Type in your Sandrone's stats: ATK, EM, and %CRIT_DMG (example below)
- That's all you need to do; now see your damage calculated.

Note: The calculated damage has 2 results; the lower one is at 10 stacks, and the higher one is at 12 stacks (Base_Reaction_Coefficient)


### Example:
<img width="784" height="322" alt="image" src="https://github.com/user-attachments/assets/393be8b5-16a9-4768-968a-2075dd3d388f" />

<img width="789" height="199" alt="image" src="https://github.com/user-attachments/assets/3aed685d-fe58-4634-b8de-d3bbf60d0fdb" />

## Click this checkbox for more details.
<img width="1905" height="999" alt="image" src="https://github.com/user-attachments/assets/eb211be6-217d-4d65-a592-d05ff310128c" />

---


# Explanation:
System Optimized Build:
- Shows you the highest achievable Sandrone damage at the current setup: Level, Weapon, Teamates. (This does not base on your input stats such as ATK, EM, %CRIT_DMG)
- The Highest Damage is calculated by adjusting between %ATK, EM, and %CRIT_DMG of the Main and Sub stats of all 5 artifact pieces. (see sheet: [artifact_substat_cases] for more details)
- It also shows the substat counts for each type of substat.
- "Highest Total Stats" section showing the actual stats after Team buffs, Weapon buffs, etc. Combined with the Best Artifacts possible.

At the bottom:
- Progress bar of how your Sandrone builds far away from the best build possible.
- Advice to increase your damage by which stats are needed and which should be reduced.
Note: Higher numbers mean they should be given more priority.

<img width="710" height="421" alt="image" src="https://github.com/user-attachments/assets/64d31279-1cae-4ea4-9bfc-94f431478eeb" />

<img width="708" height="90" alt="image" src="https://github.com/user-attachments/assets/dd4e05d0-1cb4-430e-ad84-d620a72fa09a" />

## This project basically brute-force simulates and calculates every possible artifact stats case to find the highest damage output!

<img width="848" height="611" alt="image" src="https://github.com/user-attachments/assets/f9eece39-afb3-4382-98d6-9c0ea67a3fd2" />


---

# Requirements

- Microsoft Excel 365 is recommended
- Required features:
  - LET()
  - Dynamic Arrays

- Optional:
  - Power Query (used for refreshing artifact data)

---

# License

This project is licensed under the MIT License.

You are free to use, modify, and redistribute this project as long as the original copyright notice and license are included.
