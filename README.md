# New York City Airbnb Listings Analysis

This project provides an analysis of Airbnb listings in New York City, using data from multiple sources to extract insights on pricing, room types, and review history. The analysis offers a data-driven look into the Airbnb landscape in one of the world's most popular tourist destinations.

## Project Overview

New York City is a hotspot for travelers, with high demand for short-term rentals. This project analyzes Airbnb listing data to understand listing attributes, price ranges, and review frequencies, helping to shed light on market trends and guest preferences.

## Dataset

The project uses data from three files with information on listings, room types, and review dates:

- **`airbnb_price.csv`**: Contains listing prices and neighborhood data.
  - `listing_id`: Unique identifier for the listing.
  - `price`: Nightly listing price in USD.
  - `nbhood_full`: Borough and neighborhood name.

- **`airbnb_room_type.xlsx`**: Provides listing descriptions and room types.
  - `listing_id`: Unique identifier for the listing.
  - `description`: Description of the listing.
  - `room_type`: Type of room (e.g., private room, entire home).

- **`airbnb_last_review.tsv`**: Includes data on hosts and last review dates.
  - `listing_id`: Unique identifier for the listing.
  - `host_name`: Name of the listing host.
  - `last_review`: Date of the last review.

## Key Findings

- **Earliest and Latest Reviews**: The dataset covers review dates from **January 1, 2019**, to **July 9, 2019**.
- **Room Types**: Of the listings analyzed, **11,356** are private rooms, indicating high demand for this room type.
- **Average Price**: The average nightly price for Airbnb listings in New York City is **$141.78**.

These insights help to capture the state of the NYC Airbnb market and highlight trends in room types and pricing.

## Future Work

Further exploration could include:

- Examining price variations by neighborhood and borough.
- Analyzing seasonal trends in review dates and listing availability.
- Investigating the impact of listing descriptions on booking rates.
