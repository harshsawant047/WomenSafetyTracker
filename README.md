# Women's Safety Analytics Application

A comprehensive safety analytics platform providing real-time insights and emergency assistance for women in India. This application uses geospatial data visualization, risk analysis, and community reporting to enhance women's safety awareness.

## Features

### Data Visualization
- **Crime Heatmaps**: Interactive visualization of crime data across Indian states
- **Risk Analysis**: Safety scoring and risk assessment for different regions
- **State-wise Statistics**: Detailed crime statistics for each Indian state

### User Features
- **User Authentication**: Secure registration and login system
- **Profile Management**: Personal information and emergency contact management
- **Emergency SOS**: One-touch emergency alert system

### Safety Tools
- **Community Reporting**: Platform for anonymously reporting safety incidents
- **Safety Resources**: Directory of police stations, hospitals, and support organizations
- **Emergency Helplines**: Quick access to national and state-level emergency numbers

### Technical Features
- **Dual Database System**: PostgreSQL for relational data, MongoDB for NoSQL data
- **API Integration**: MapmyIndia integration for India-specific geolocation features
- **Data Analytics**: Statistical analysis of crime patterns and safety trends

## Technology Stack

- **Backend**: Python Flask
- **Database**: PostgreSQL + MongoDB
- **Frontend**: HTML, CSS, JavaScript with Bootstrap
- **Maps**: Leaflet.js with MapmyIndia integration
- **Data Visualization**: Chart.js
- **Geospatial Analysis**: GeoPandas, NumPy, Pandas

## Documentation

- [Local Setup Guide](docs/local_setup_guide.md): Instructions for setting up the project locally
- [MongoDB Data Guide](docs/mongodb_data_guide.md): Explanation of MongoDB data generation and structure
- [Requirements List](docs/requirements_list.md): List of required Python packages and their descriptions

## Data Sources

This application uses the following Indian crime data sources:
- State-wise Crimes Committed Against Women (2015) - National Crime Records Bureau
- Historical crimes against women data

## Project Status

This project is actively under development with focus on the following areas:
- Enhanced data visualization for crime statistics
- Improved risk analysis algorithms
- Integration with additional India-specific safety resources

## Prerequisites

- Python 3.11+
- PostgreSQL database
- MongoDB database
- MapmyIndia API credentials (for India-specific features)

## Quick Start

See the [Local Setup Guide](docs/local_setup_guide.md) for detailed instructions on getting started with the application.

```bash
# Clone repository
git clone <repository-url>
cd womens-safety-analytics

# Install dependencies
# See docs/requirements_list.md for the complete list of packages
pip install flask pandas numpy geopandas psycopg2-binary pymongo

# Configure environment variables
# (See local_setup_guide.md for details)

# Run the application
python main.py
```

## Contributing

Contributions to this project are welcome. Please ensure your code follows the existing coding style and includes appropriate tests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.