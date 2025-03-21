# Olympic Data Analysis Project

## Description
This project involves the analysis of Olympic athletes' data using Python. It connects to a MySQL database, creates a database and table for storing Olympic data, and performs various analyses on the dataset. The analyses include athlete demographics, medal distribution, and visualizations of the data.

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```
2. Install the required packages:
   ```bash
   pip install pandas pymysql seaborn matplotlib openpyxl
   ```

## Usage
1. Ensure that you have a MySQL server running and accessible.
2. Update the database connection details in the `Database_creating.ipynb` file.
3. Run the Jupyter notebook to create the database, load the data, and perform analyses:
   ```bash
   jupyter notebook Database_creating.ipynb
   ```

## Data Sources
The dataset used in this project is sourced from an Excel file named `Olympics Dataset.xlsx`, which contains information about Olympic athletes, including their demographics and medal counts.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
