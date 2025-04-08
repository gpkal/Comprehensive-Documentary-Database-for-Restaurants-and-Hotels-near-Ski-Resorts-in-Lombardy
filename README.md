# Lombardy Ski Tourism Database Project

## Overview
Documentary database of restaurants and hotels near Lombardy ski resorts, utilizing web scraping and API integration.

## Methodology
1. **Data Acquisition**: TripAdvisor, The Fork, Google, Booking.com (web scraping), Lombardy Open Data APIs
2. **Data Cleaning**: Deduplication, address standardization, null handling
3. **Integration**: Cross-source merging, data enrichment
4. **Storage**: MongoDB (schema-less approach)
5. **Quality Assessment**: Accuracy (63% restaurants, 50% hotels), completeness, consistency

## Key Features
- Coverage: 44 Lombardy municipalities
- Data: Geo-location, contact info, ratings, reviews
- Sample queries provided for data extraction

## Challenges & Future Work
- Implementing automatic updates
- Real-time availability tracking
- Geospatial visualization integration

## Execution Guide
1. Acquisition folder files (non-concurrent execution)
2. Cleaning folder files (concurrent execution possible)
3. Integration folder:
   a. hotels_reference.ipynb
   b. hotel_to_json.ipynb
   c. merging_booking_API.ipynb, merger_restaurants.ipynb
4. pymongo.ipynb

> **Note**: Scraping results may vary due to execution timing.

---

<div align="center">
<i>Project carried out for the Data Management course of the academic year 2023-2024.<br>
Master of Science in Data Science course</i>
</div>
