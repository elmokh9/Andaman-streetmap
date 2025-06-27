# Andaman & Nicobar Islands Street Network Analysis

This project analyzes the street network and healthcare facility distribution in the Union Territory of Andaman and Nicobar Islands using OpenStreetMap data and geospatial analysis techniques.

## Project Overview

Inspired by Jean-Luc Jucker's visualizations, this analysis explores the street networks of Andaman and Nicobar Islands using the OSMnx Python package. The project combines street network analysis with healthcare facility mapping to understand accessibility and distribution patterns in this strategically important Union Territory.

## Motivation

- **Personal Connection**: Visited Andaman and Nicobar Islands in December 2018 and was captivated by the region
- **Strategic Importance**: The islands house the first and only tri-service theater command of the Indian Armed Forces
- **Healthcare Access**: Understanding the distribution and accessibility of healthcare facilities in remote island territories

## Dataset Sources

1. **Street Network Data**: Retrieved from OpenStreetMap using OSMnx package
2. **Healthcare Facilities**: Web-scraped from the Government of Andaman & Nicobar website
3. **Population Data**: Collected for demographic analysis and planning insights
4. **Geocoding**: Google Maps API used for accurate location coordinates

## Key Features

- Street network visualization and analysis
- Healthcare facility mapping and distribution analysis
- Accessibility analysis (travel time calculations between nodes)
- Population distribution exploration
- Interactive maps with facility markers and road networks

## Technologies Used

- **OSMnx**: Street network retrieval, modeling, analysis, and visualization from OpenStreetMap
- **Folium**: Interactive map visualization
- **Google Maps API**: Geocoding services
- **Python**: Data analysis and web scraping
- **Jupyter Notebook**: Analysis environment

## Analysis Components

### 1. Street Network Analysis
- Network topology and connectivity analysis
- Road density and distribution patterns
- Network statistics and metrics

### 2. Healthcare Facility Mapping
- **Blue markers**: Public healthcare facilities
- **Beige network**: Road infrastructure
- Spatial distribution analysis of medical services

### 3. Accessibility Analysis
- Travel time calculations between network nodes
- Nearest facility accessibility for residents
- Service coverage area analysis

### 4. Population-Based Planning
- Demographic distribution mapping
- Infrastructure planning insights
- Service optimization recommendations

## Key Insights & Applications

This type of analysis can inform:
- **Urban Planning**: Better road network design based on population distribution
- **Public Services**: Optimal placement of hospitals, schools, and government offices
- **Emergency Response**: Police response time optimization
- **Healthcare Access**: Identifying underserved areas
- **Administrative Planning**: District boundary and service area optimization

## Technical Challenges

- **Performance**: OSMnx package has high response time for complex queries
- **Geocoding Accuracy**: OpenStreetMap geocoding yielded less satisfactory results compared to Google Maps API
- **Data Quality**: Web-scraped data required extensive cleaning and validation

## Data Sources

- **OpenStreetMap**: Street network data via OSMnx
- **Government of Andaman & Nicobar**: Webscraped data from Healthcare facility information websites
- **Census Data**: Population distribution statistics

## Future Enhancements

- Real-time traffic data integration
- Multi-modal transportation analysis
- Seasonal accessibility patterns
- Disaster preparedness and evacuation route analysis
