# Airbnb-GeoDash

**Airbnb-GeoDash** is an interactive web application built using Streamlit to visualize Airbnb listings data. This app showcases the dataset both as a DataFrame and as a geographic visualization, providing insights into pricing, availability, and reviews across different locations. Ideal for portfolio presentations, this project demonstrates data analysis and visualization skills using Python and Streamlit.

## Features

- Interactive visualization of Airbnb listings on a map
- Display of detailed listing information in a DataFrame
- Filtering options for different room types and price ranges
- Calculation of booking prices and review scores

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/Airbnb-GeoVisualizer.git
    cd Airbnb-GeoVisualizer
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Run the Streamlit app:
    ```sh
    streamlit run app.py
    ```

2. Open your web browser and navigate to the provided URL to interact with the app.

## Project Structure

- `app.py`: The main Streamlit application file
- `WK2_Airbnb_Amsterdam_listings_proj_solution.csv': Pickle file containing the Airbnb listings data
- `requirements.txt`: List of required Python packages

## How It Works

1. **Loading Data**: The app loads Airbnb listings and calendar data from Pickle and Parquet files.
2. **Data Cleaning**: The data is cleaned and processed to remove null values and convert data types.
3. **Visualization**: The app uses Streamlit to create interactive visualizations, including a map view of listings and detailed DataFrame views.
4. **User Interaction**: Users can filter the listings by room type, price, and other criteria, and view detailed information about each listing.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the Apache 2.0. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- This project is based on the weekly Uplimit projects course for machine learning with python.
- Thanks to the Streamlit community for providing great resources and examples.
