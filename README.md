# ⚡ Tournament Auction Pro

A premium, real-time sports tournament management system designed to automate auctions, scheduling, and standings. Built with **React Native** and powered by **Firebase** for sub-second synchronization.

---

## 🚀 Key Features

### 🔨 Real-Time Auction Room
- **Automatic Bidding**: Simplified one-tap bidding with pre-defined increments.
- **Smart Timer**: Countdown clock that resets on every bid to keep the competition alive.
- **Auto-Sold/Unsold**: Intelligent round closure that processes results the moment the timer hits zero.
- **Anonymous Team Logic**: Secure bidding for team managers using simple team keys, without complex account setup.

### 🗓️ Advanced Tournament Scheduling
- **Format Support**: League (Round Robin), Knockout Brackets, and Mixed formats.
- **Automatic Progression**: Knockout winners automatically advance to the next round's TBD slots.
- **Fixture Generation**: One-click auto-scheduling for full season fixtures.

### 📊 Dynamic Standings & Stats
- **Live Points Table**: Real-time updates with automated Tie-breaker calculations (NRR for Cricket, GD for Football).
- **Player Stats Tracker**: Comprehensive tracking for runs, wickets, goals, and assists.
- **Manual Overrides**: Admin controls for correcting points or manual match adjustments.

---

## 📦 Getting Started

1. **Install dependencies**
   ```bash
   npm install
   ```

2. **Start the app**
   ```bash
   npx expo start
   ```

---

## 📖 User Workflow

1. **Admin Setup**: Create a tournament, add teams, and populate the player pool.
2. **Launch Auction**: Open the Auction Room. Teams log in using their **Team Key**.
3. **Conduct Bidding**: Players are processed sequentially. The system handles all sales and wallet deductions automatically.
4. **Auto-Schedule**: Use the 'Auto-Schedule' feature to generate fixtures for the sold squads.
5. **Score Matches**: Enter results as they happen. Watch the Points Table and brackets update in real-time.

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an issue for feature requests.

---

## 📄 License
This project is licensed under the MIT License.
