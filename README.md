# Slot Machine Simulator

A Python-based command-line slot machine game that simulates the experience of playing a slot machine. Users can deposit money, place bets, spin the slot machine, and potentially win rewards based on their luck and the payout multiplier for each symbol.

## Features

- Deposit funds to play the game.
- Place bets on up to 3 lines.
- Randomly generate slot machine spins based on symbol frequency.
- Calculate winnings based on matching symbols and payout multipliers.
- Display winnings and remaining balance after each round.
- User-friendly interface with error handling for invalid inputs.

---

## How to Play

1. **Deposit Money**  
   Start by depositing an amount to fund your gameplay.

2. **Choose Number of Lines to Bet On**  
   Decide how many lines (1-3) you want to bet on.

3. **Place Your Bet**  
   Place a bet amount for each line. The total bet is calculated as:  
   `total_bet = bet_per_line * number_of_lines`

4. **Spin the Slot Machine**  
   The slot machine will randomly generate a grid of symbols based on their frequency. If matching symbols appear on the same line, you win a payout based on the symbol's value.

5. **Check Results**  
   After each spin, the game displays:
   - Slot machine grid
   - Total winnings
   - Winning lines
   - Updated balance

6. **Continue or Quit**  
   You can play another round or quit the game at any time.
