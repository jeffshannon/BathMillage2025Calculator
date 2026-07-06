# Bath Millage 2026 Calculator

A simple web-based calculator to help Bath residents understand how the proposed 2026 millage increase would affect their property taxes.

## How It Works

Users enter their home's taxable value, and the calculator shows:
- Current annual property tax
- Proposed annual property tax  
- Annual difference
- Monthly difference

## Setup

1. Get the current and proposed millage rates from https://bathmillage2026.com/
2. Update the `RATES` object in `script.js`:
   ```javascript
   const RATES = {
       current: 0.0,   // Replace with actual current rate
       proposed: 0.0   // Replace with actual proposed rate
   };
   ```
3. Open `index.html` in a web browser to use the calculator

## Files

- **index.html** - Calculator interface
- **style.css** - Styling and layout
- **script.js** - Calculation logic
- **README.md** - This file

## Features

- Clean, responsive design
- Real-time calculations
- Mobile-friendly interface
- Currency formatting
- Monthly breakdown of tax difference

## Example

If a home is assessed at $150,000 with:
- Current rate: 13.50 mills
- Proposed rate: 14.25 mills

The calculator shows:
- Current tax: $2,025/year
- Proposed tax: $2,137.50/year
- **Difference: $112.50/year ($9.38/month)**

## Next Steps

1. Contact Bath Community Schools or your local municipality for the exact millage rates
2. Update the rates in `script.js`
3. Deploy to GitHub Pages or a web server
4. Share with residents

## License

Public domain - feel free to modify and share

## More Information

For details about the proposed millage increase, visit:
https://bathmillage2026.com/
