Currency Converter

![currencyConverter](https://github.com/user-attachments/assets/f4f6a67f-68a6-495b-b059-21c10f148921)

A React-based currency converter that allows users to convert between various currencies in real-time. The app fetches live exchange rates using an API, offering users an intuitive and responsive experience.

Features

- Real-time Currency Conversion: Users can convert between different currencies instantly.
- Currency Selection: Users can select from a variety of currency options.
- Amount Input: Users can input the amount they wish to convert.
- Currency Swap: Easy swapping of base and target currencies for a seamless user experience.
- Responsive Design: The UI is built with Tailwind CSS to ensure it looks great on all devices.

Tech Stack

- useState: To manage states like amount, selected currencies, and conversion rates.
- useEffect: To fetch updated currency rates when the selected currency changes.
- useCallback: For performance optimization of functions like amount handling and currency swapping.
- useRef: For referencing DOM elements where necessary.
- API Integration: Utilized an external API for fetching up-to-date exchange rates.

Installation and Setup
Prerequisites

    Node.js and npm should be installed on your system.

Steps

Clone the repository:

    git clone https://github.com/tasnifrahman/Currency_Converter.git

Navigate to the project directory:

    cd Currency_Converter

Install dependencies:

    npm install

Run the development server:

    npm start

    Open http://localhost:5137 in your browser to view the application.

Usage

- Amount Input: Enter the amount you wish to convert.
- Currency Selection: Choose the base and target currencies from the dropdown.
- Convert: The converted amount will display automatically as you enter or change values.
- Swap Currencies: Use the swap button to reverse the base and target currencies.
