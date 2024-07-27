# EtsyOrderAnalyzer

## Description
EtsyOrderAnalyzer is a C++ application designed to parse and analyze CSV files containing shipping data. It helps in understanding sales distributions and trends across different geographical areas by extracting and analyzing location-based data (countries, states, and cities) from sales records.

## Features
- Parse CSV files to extract location data.
- Analyze and display counts and trends for countries, states, and cities.
- Display the top N locations based on sales data.
- User-friendly menu-driven interface.

## CSV File Formatting Guidelines
- **Delimiter**: Use tabs (`\t`) as the delimiter between fields.
- **Header Row**: Ensure the CSV file includes a header row with column names.
- **Relevant Columns**: The columns for locations should be named `Ship Country`, `Ship State`, and `Ship City`.

## Installing and Running
1. **Clone the repository**: 
   git clone https://github.com/Epicrae/EtsyOrderAnalyzer.git

2. Navigate to the project directory:
   cd EtsyOrderAnalyzer

3. Compile the program:
   g++ -o EtsyOrderAnalyzer main.cpp -std=c++11   
 
 4. Run the program:
   ./EtsyOrderAnalyzer

##Usage
Enter the name of your CSV file: When prompted, enter the path to your CSV file.
Select an option from the menu:
1. View Shipping Countries
2. View Shipping States
3. View Shipping Cities
4. Top Shipping Locations
5. Exit

Dependencies
C++ Compiler (e.g., GCC, Clang)
Standard C++ libraries
Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
Amber Frick - amberfricks@yahoo.com

GitHub Profile - https://github.com/Epicrae
