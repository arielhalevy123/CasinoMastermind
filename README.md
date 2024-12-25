# Casino Mastermind

Welcome to the Casino Mastermind repository! This project is a comprehensive casino management system designed to create an immersive online gaming experience featuring popular games such as blackjack, roulette, and a lucky wheel. The system also includes advanced user management, financial tracking, and administrative functionalities.

---

## Overview
The Casino Mastermind platform is built with the following core features:
- **User Management**: Players can create accounts, log in, and access personalized casino functionalities.
- **Games**:
  - **Blackjack**: A strategic card game with flexible betting.
  - **Roulette**: A classic gambling game with multiple betting options.
  - **Lucky Wheel**: A simple game of chance with varied prizes.
- **Financial Features**:
  - Loan system with interest and repayment management.
  - Player financial summaries.
- **Admin Panel**:
  - Add and manage players.
  - Sort and search player data.
  - View comprehensive casino reports.

---

## How to Use the System

### System Boot
1. The system can be initialized from either a text file or a binary file.
2. During initialization, all registered players and their associated data are loaded into the system.

### User Login
1. Enter your username and password to log in.
2. For admin access, use the username "ADMIN" and password "Admin".
3. New players can create accounts directly within the system.

### Player Features
After logging in as a Player, you can access the following features:

#### 1. **Take a Loan**
- Request a loan up to $1,000.
- You can have a maximum of 5 open loans at a time.
- Loans incur a 15% interest rate.

#### 2. **Repay a Loan**
- Repay loans in a first-in, first-out (FIFO) order.
- You can only repay loans if sufficient funds are available.

#### 3. **View Financial Summary**
- View your:
  - Name
  - Number of loans
  - Total bets
  - Financial status

#### 4. **Play Blackjack**
- Place a bet and play against the dealer.
- Follow standard blackjack rules, aiming to get closer to 21 than the dealer without exceeding it.
- Game stages:
  1. Place bets.
  2. Dealer deals cards.
  3. Player decides to "hit" or "stand".
  4. Dealer plays.
  5. Winner is determined.

#### 5. **Play Roulette**
- Choose a bet size and type:
  - Even/Odd
  - Red/Black
  - Green/0
  - Specific ranges (e.g., first dozen, second dozen).
- Payouts vary by bet type, with potential multipliers up to 36x.

#### 6. **Play Lucky Wheel**
- Pay $65 to spin the wheel.
- Win prizes ranging from $0 to $200.

### Admin Features
Logging in as an Admin provides additional capabilities:

#### 1. **View Casino Details**
- Display:
  - Casino name
  - Number of registered players
  - Details of all players

#### 2. **Add a New Player**
- Manually add a player with a username and password.

#### 3. **Sort Players**
- Sort player data by:
  - Total bets
  - Username
  - Current account balance

#### 4. **Search for a Player**
- Search for players based on sorted criteria.
- View detailed player information, including:
  - Loans
  - Bets
  - Financial status

---

## Key Functionalities
- **Data Persistence**:
  - Player data can be saved and reloaded from files.
  - Ensures continuity between sessions.
- **Flexible Gaming Options**:
  - Supports multiple betting strategies and game types.
- **Robust Financial Tracking**:
  - Transparent loan and repayment management.

---

## Future Enhancements
- Add support for additional games like Poker and Slots.
- Enhance security features, such as two-factor authentication.
- Introduce detailed player analytics for admins.

---



## Contributors
- **Ariel Halevy**: Design and development.

---

## Acknowledgments
Thanks to the open-source community and casino enthusiasts for inspiring this project!

