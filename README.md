# PhonePe Pulse Data Analysis

PhonePe Pulse Data Analysis is a project aimed at extracting insights from the PhonePe Pulse GitHub repository's data, transforming and cleaning it, inserting it into a MySQL database, and creating a live geographical visualization dashboard using Streamlit and Plotly in Python.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Project Description](#project-description)
- [Basic Insights](#basic-insights)
- [Analysis](#analysis)
  - [All India](#all-india)
  - [State-wise](#state-wise)
  - [Top Categories](#top-categories)
- [Contributing](#contributing)
- [License](#license)

## Technologies Used

The technologies used in this project include:

- Python
- Pandas
- MySQL
- Streamlit
- Plotly

## Project Description

The project involves the following steps:

1. Extracting data from the PhonePe Pulse GitHub repository.
2. Transforming and cleaning the data.
3. Inserting the cleaned data into a MySQL database.
4. Creating a live geographical visualization dashboard using Streamlit and Plotly.

## Basic Insights

The `BASIC INSIGHTS` section provides some basic insights about the data, including:

- Top 10 states based on year and amount of transaction
- Least 10 states based on type and amount of transaction
- Top 10 mobile brands based on percentage of transaction
- Top 10 registered users based on states and district
- Top 10 districts based on states and amount of transaction
- Least 10 districts based on states and amount of transaction
- Least 10 registered users based on districts and states
- Top 10 transaction types based on states and transaction amount

## Analysis

The `ANALYSIS` section provides more in-depth analysis, categorized as:

- All India
- State-wise
- Top Categories

### All India

#### Transaction Analysis

This subsection includes a geographical visualization dashboard for transaction analysis, transaction analysis bar chart, and total transaction calculation table.

#### User Analysis

This subsection includes a geographical visualization dashboard for user analysis, user analysis bar chart, and total user calculation table.

### State-wise

#### Transaction

This subsection includes state-wise transaction analysis bar chart and total transaction calculation table.

#### User

This subsection includes state-wise user analysis bar chart and total user calculation table.

### Top Categories

This subsection includes top transaction analysis bar chart and total transaction calculation table, as well as top user analysis bar chart and total user calculation table.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
