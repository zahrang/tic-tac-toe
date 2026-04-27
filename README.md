# Tic-Tac-Toe Game Theory Analysis

## Overview

This project analyzes Tic Tac Toe game outcomes based on different player skill levels using **game theory principles**. It simulates thousands of games to quantify how perfect vs imperfect play affects results.

### Key Questions Answered:
- **Perfect vs Perfect**: Does optimal play always lead to a draw?
- **Perfect vs Imperfect**: How often does the perfect player win?
- **Imperfect vs Imperfect**: Do mistakes balance out over time?
- **Random vs Random**: What's the baseline distribution?

## The Three Analysis Scenarios

| Scenario | Player X | Player O | Theoretical Outcome |
|----------|----------|----------|---------------------|
| **Perfect vs Perfect** | Perfect AI | Perfect AI | 100% Draws |
| **Perfect vs Imperfect** | Perfect AI | Makes mistakes | Perfect wins most |
| **Imperfect vs Imperfect** | Makes mistakes | Makes mistakes | Balanced distribution |
| **Random vs Random** | Random moves | Random moves | ~33% each outcome |

## Game Theory Background

Tic Tac Toe is a **solved game** - with perfect play from both players, the outcome is always a draw. This project quantifies how deviations from optimal strategy affect win/loss/draw rates.

### Player Types:

1. **Perfect Player** 
   - Uses optimal strategy
   - Blocks opponent's winning moves
   - Takes center/corners when available
   - Never loses to imperfect play

2. **Imperfect Player** 
   - Plays perfectly 70% of the time
   - Makes random moves 30% of the time
   - Simulates human-like mistakes

3. **Random Player** 
   - Chooses completely random moves
   - Serves as baseline comparison

## Visual Outputs

The analysis generates **4 professional graphs**:

1. **Win/Loss Distribution Bar Chart** - Compare all scenarios
2. **Game Length Analysis** - Average moves per scenario
3. **Stacked Outcome Distribution** - 100% stacked view
4. **Perfect Player Dominance** - Win rate vs mistake rate
5. **Pie Charts** - Detailed breakdown of key scenarios
6. **Summary Table** - Complete statistics table
