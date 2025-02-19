# bladder-tracker
This calculator is based on the concepts of Mechanical advantage and Displacement advantage
# Bladder Efficiency Calculator

## Overview
This is a web-based calculator designed to analyze bladder efficiency by measuring and tracking storage and voiding metrics. The tool requires password authentication for access.

## Access Instructions
1. Open the `calculator.html` file in a modern web browser
2. Enter the password: `bladcalc2025`
3. Click "Login" or press Enter

## Using the Calculator

### Initial Setup
1. Select patient gender (Male/Female)
2. Enter study start time in HH:MM format
3. Enter patient age when prompted
4. Click "Start Study"

### Data Entry
For each measurement, enter:
- Measurement Time (HH:MM)
- Voided Volume (mL) - example: 350
- Voiding Time (seconds) - example: 25
- Fill Time will be automatically calculated

### Available Functions
- **Calculate Efficiency**: Processes entered data and updates results
- **SAVE**: Stores current study data in browser's local storage
- **LOAD**: Retrieves previously saved study data
- **CLEAR**: Resets all fields and study data
- **DOWNLOAD**: Exports study data as JSON file

### Results Display
The calculator shows:
- Current measurement results
  - Fill Rate (mL/min)
  - Storage Efficiency (%)
  - Voiding Efficiency (%)
- Study summary statistics
  - Number of measurements
  - Average efficiencies
  - Data reliability metrics
- Visual graph tracking efficiency over time

## Technical Notes
- The calculator uses client-side JavaScript
- Data is stored locally in the browser
- Charts are rendered using Chart.js library
- No server-side components required

## Browser Compatibility
Tested and compatible with:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Support
If you encounter any issues:
1. Ensure you're using a modern, updated browser
2. Clear browser cache if experiencing display issues
3. Check that JavaScript is enabled

