Automobile Sales Dashboard

Overview

This project is a Dash-based web application that provides insights into historical automobile sales data. The dashboard allows users to visualize automobile sales trends over time, with options to analyze data by year or recession periods.

Features

Interactive Dropdowns: Users can select report types (Yearly or Recession) and specify the year for analysis.

Dynamic Data Visualization:

Line charts for average automobile sales by year.

Bar charts for automobile sales by vehicle type.

Pie charts for advertising expenditure distribution.

Comparative analysis of sales trends across different economic conditions.

Responsive Layout: Uses Tailwind CSS for a modern, responsive design.

Technologies Used

Dash (for the web framework)

Pandas (for data manipulation)

Plotly Express & Graph Objects (for data visualization)

HTML & CSS (TailwindCSS) (for styling and layout)

Data Source

The application loads data from an external CSV file hosted at:
Historical Automobile Sales Dataset

Installation & Setup

Prerequisites

Ensure you have Python installed on your system. Recommended version: Python 3.8+

Install Dependencies

pip install dash pandas plotly

Run the Application

Save the provided Python script and execute the following command in your terminal:

python app.py

Then, open a browser and navigate to http://127.0.0.1:8050/.

How to Use

Select Report Type:

"Yearly Statistics": View sales trends for a selected year.

"Recession Period Statistics": Analyze sales trends during recession periods.

Choose a Year (Enabled only for "Yearly Statistics").

Visualize the Data: The dashboard will dynamically update with relevant charts.

Application Structure

.
├── app.py             # Main application script
├── README.md          # Project documentation
├── requirements.txt   # Dependencies list

Future Enhancements

Add more interactive filters (e.g., brand, region, fuel type).

Implement additional economic indicators for deeper analysis.

Enhance UI with more custom styling and animations.
