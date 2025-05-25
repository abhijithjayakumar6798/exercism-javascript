# Annalyn's Quest - Game Logic Functions

This project implements quest logic for an RPG game featuring **Annalyn**, a brave girl on a mission to rescue her best friend. The game involves interaction with various characters like a knight, an archer, and a prisoner.

## Scenario

Annalyn's best friend was kidnapped while searching for berries in the forest. Annalyn tracks the kidnappers to a camp guarded by:

- A **mighty knight**
- A **cunning archer**
- A **prisoner** (Annalyn’s best friend)

Annalyn must decide what actions she can take, optionally with the help of her **pet dog**.

---

## Actions and Conditions

### 1. Fast Attack

- **Condition:** The knight is **asleep**.
- **Reason:** The knight takes time to wear his armor.
- **Function:** `canExecuteFastAttack(knightIsAwake)`

```javascript
const knightIsAwake = true;
canExecuteFastAttack(knightIsAwake); 
// => false
