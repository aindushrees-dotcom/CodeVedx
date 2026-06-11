# Utility Usage Prediction Tool

An interactive web-based utility usage prediction tool that uses machine learning (linear regression) to forecast electricity, water, and gas consumption patterns.

## Features

- **Data Management**
  - Add new usage records with month, electricity (kWh), water (L), and gas (m³)
  - Update existing records
  - View all records in a formatted table

- **Machine Learning**
  - Train a linear regression model on historical data
  - Predict future utility usage based on trained coefficients
  - View model parameters and statistics

- **Data Analysis**
  - Calculate dataset statistics (mean, median, min, max, standard deviation)
  - Save data to CSV format
  - Visual terminal-like UI with color-coded sections

- **Data Persistence**
  - Export data to CSV files
  - Git integration simulation

## Interactive Terminal Commands

| Command | Description |
|---------|-------------|
| `menu` | Display main menu |
| `1` | Add new usage record |
| `2` | Update existing record |
| `3` | View all data |
| `4` | Train ML model |
| `5` | Predict next month |
| `6` | Save data to CSV |
| `7` | Show statistics |
| `8` | Git status |
| `help` | Show available commands |
| `clear` | Clear console |
| `0` | Exit |

## How to Use

1. Open `utility_usage_prediction_tool.html` in a web browser
2. Use the on-screen buttons or type commands directly in the input field
3. Start with `menu` to see all available options
4. Add some data records or use pre-loaded sample data
5. Train a model with command `4`
6. Make predictions with command `5`

## Sample Data

The tool comes with 6 months of pre-loaded sample data (January through June) with realistic utility usage patterns.

## Technical Details

- **Frontend**: HTML5 with vanilla JavaScript
- **Algorithm**: Linear Regression (scikit-learn compatible implementation)
- **Data Format**: CSV (month, electricity_kwh, water_litres, gas_m3)
- **UI**: Terminal-style interface with dark theme

## Project Structure

```
utility_usage_prediction_tool.html  - Task 1 interactive application
Task 2 student_performance_prediction_dark.html - Task 2 student performance prediction app
README.md                           - Project documentation
```

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/aindushrees-dotcom/CodeVedx.git
   ```

2. Open the HTML file in your browser:
   ```bash
   open utility_usage_prediction_tool.html
   # or
   start utility_usage_prediction_tool.html
   ```

## License

This project is open source and available under the MIT License.

## Author

CodeVedx - Task 1 Submission

