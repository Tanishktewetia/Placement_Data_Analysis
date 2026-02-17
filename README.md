# Placement Data Analysis Dashboard

A simple and clean web-based dashboard for analyzing placement data from multiple years.

## Features

- 📊 **Year Selection** - Switch between 2024, 2025, and 2026 data
- 🔍 **Advanced Filtering**
  - Eligibility Percentage (min criteria)
  - CTC Range Slider (0-100 LPA)
  - Category Filter
  - Company Filter
  - Role Filter

- ↕️ **Sorting Options**
  - CTC (High to Low / Low to High)
  - Students Placed (High to Low / Low to High)

- 📈 **Statistics Dashboard**
  - Total Companies Visited
  - Total Students Applied
  - Total Students Selected
  - Selection Rate (%)

- 📋 **Clean Data Table** - Organized display with alternating row colors and hover effects

## Files

- `index.html` - Main dashboard application
- `2024.csv` - 2024 placement data
- `2025.csv` - 2025 placement data
- `2026.csv` - 2026 placement data
- `col.txt` - Column definitions
- `.gitignore` - Git ignore rules
- `README.md` - This file

## How to Use

1. Open `index.html` in your web browser
2. The dashboard will load with 2026 data by default
3. Use the year selector to switch between years
4. Apply filters and sorting as needed
5. Click "Apply Filters" to update results
6. Click "Reset All" to clear all filters

## CSV Data Format

Each CSV file contains the following columns:
- Company Name
- Date of Visit
- Role
- Category
- CTC
- Eligibility Percentage
- Student Applied
- Student Selected

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- PapaParse (CSV parsing)

## Browser Compatibility

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## Installation

Simply clone the repository and open `index.html` in your browser:

```bash
git clone https://github.com/Tanishktewetia/Placement_Data_Analysis.git
cd Placement_Data_Analysis
# Open index.html in browser
```

## License

This project is open source and available under the MIT License.
