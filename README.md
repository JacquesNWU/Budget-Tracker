# Family Budget Tracker

A desktop application for managing household finances together. Track income, expenses, and payments with your partner in a simple, intuitive interface.

## Features

- 📊 **Real-time KPI Dashboard** - View total income, expenses, paid amounts, and remaining balance at a glance
- 💰 **Income & Expense Tracking** - Add and categorize all your financial transactions
- 👥 **Payment Responsibility** - Track who pays what (Husband/Wife/Both)
- ✅ **Payment Status** - Mark expenses as paid/unpaid throughout the month
- 📥 **CSV Export** - Export your monthly budget data for record-keeping
- 🔄 **Monthly Reset** - Start fresh each month while keeping your budget structure
- 💾 **Auto-save** - All data is automatically saved locally
- 🇿🇦 **ZAR Currency** - Built specifically for South African Rand

## Installation

### Option 1: Download Pre-built Executable (Windows)

1. Go to [Releases](https://github.com/JacquesNWU/budget-tracker/releases)
2. Download the latest `Budget Tracker Setup X.X.X.exe`
3. Run the installer
4. Launch Budget Tracker from your Start Menu

### Option 2: Run from HTML (All Platforms)

1. Download `index.html` from this repository
2. Double-click the file to open it in your browser
3. Bookmark it or create a desktop shortcut for easy access

### Option 3: Build from Source

#### Prerequisites
- [Node.js](https://nodejs.org/) (v14 or higher)
- npm (comes with Node.js)

#### Steps

```bash
# Clone the repository
git clone https://github.com/yourusername/budget-tracker.git
cd budget-tracker

# Install dependencies
npm install

# Run in development mode
npm start

# Build executable for Windows
npm run build
```

The built executable will be in the `dist/` folder.

## Usage

1. **Add Income**: Select "Income" from the type dropdown and enter your salary or other income sources
2. **Add Expenses**: Add all your monthly expenses (rent, utilities, groceries, etc.)
3. **Assign Responsibility**: Choose who pays each item (Husband/Wife/Both)
4. **Track Payments**: Click the "Unpaid/Paid" button to mark items as paid throughout the month
5. **Monitor Progress**: Watch your remaining balance update in real-time
6. **Export Monthly Records**: Click "Export CSV" at month-end to save your records
7. **Reset for New Month**: Click "Reset Month" to clear all payment statuses and start fresh

## File Structure

```
budget-tracker/
├── index.html          # Main application file (standalone version)
├── main.js            # Electron main process
├── package.json       # Project configuration and dependencies
├── README.md          # This file
├── LICENSE            # License information
└── screenshots/       # Application screenshots (optional)
```

## Technologies Used

- **Electron** - Desktop application framework
- **HTML/CSS/JavaScript** - Core web technologies
- **Tailwind CSS** - Styling framework
- **LocalStorage** - Data persistence

## Data Storage

All your budget data is stored locally on your computer using browser LocalStorage. Your financial information never leaves your device and is not sent to any server.

**Data Location:**
- Standalone HTML: Browser's LocalStorage
- Electron App: User data directory

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

If you encounter any issues or have questions:
- Open an [Issue](https://github.com/yourusername/budget-tracker/issues)
- Email: your.email@example.com

## Roadmap

- [ ] Multi-currency support
- [ ] Data backup to cloud
- [ ] Category-based budgeting
- [ ] Charts and graphs
- [ ] Mobile app version
- [ ] Recurring expense automation

## Acknowledgments

- Built with ❤️ for family financial management
- Icons by [Lucide Icons](https://lucide.dev/)
- Styled with [Tailwind CSS](https://tailwindcss.com/)

## Disclaimer

This application is for personal budgeting purposes only. It is not financial advice software. Always consult with a qualified financial advisor for professional financial planning.

---

**Made with 💰 in South Africa**
