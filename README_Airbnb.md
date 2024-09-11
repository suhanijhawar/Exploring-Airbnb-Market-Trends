
# New York City Airbnb Market Analysis (2019)

## Project Overview
This project takes a closer look at the New York City Airbnb market in 2019, which caters to a high demand for temporary lodging for travelers. Data from multiple file types—CSV, Excel, and TSV—are combined to explore listings, prices, room types, and review details.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Data Processing](#data-processing)
- [Analysis](#analysis)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Dataset
Three files contain data on Airbnb listings in New York City from 2019:

### 1. `airbnb_price.csv`
This CSV file contains data on Airbnb listing prices and locations.
- **listing_id**: Unique identifier of the listing
- **price**: Nightly listing price in USD
- **nbhood_full**: Name of borough and neighborhood where the listing is located

### 2. `airbnb_room_type.xlsx`
This Excel file contains data on Airbnb listing descriptions and room types.
- **listing_id**: Unique identifier of the listing
- **description**: Description of the Airbnb listing
- **room_type**: Type of room (shared room, private room, or entire home/apartment)

### 3. `airbnb_last_review.tsv`
This TSV file contains data on Airbnb host names and the dates of the last reviews.
- **listing_id**: Unique identifier of the listing
- **host_name**: Name of the listing host
- **last_review**: Date when the listing was last reviewed

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/nyc-airbnb-analysis.git
   ```

2. Navigate to the project directory:
   ```bash
   cd nyc-airbnb-analysis
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Data Processing
The data from the CSV, Excel, and TSV files are merged on the `listing_id` field to create a unified dataset. The following steps are involved:
- Reading data from CSV, Excel, and TSV formats
- Data cleaning and handling missing values
- Merging the datasets based on the `listing_id`

## Analysis
The analysis includes:
- Exploring the distribution of Airbnb listing prices across different boroughs and neighborhoods
- Analyzing the types of rooms available and their impact on pricing
- Reviewing the frequency and recency of reviews by hosts

## Results
The findings from the analysis will provide insights into:
- The price range of Airbnb listings across New York City's boroughs
- The most popular types of rooms available on Airbnb
- Host activity and review trends

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request to contribute to the project.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
