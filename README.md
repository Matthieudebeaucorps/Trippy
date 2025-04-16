# Trippy

An AI-powered travel planning application built in Python, designed to generate customized multi-day trip itineraries based on natural language prompts.

## Project Overview

Trippy is a free, agentic system that combines AI models and structured data to plan unique, personalized journeys for any destination in the world. The app includes:
- Curated daily activities
- Restaurant suggestions for each meal
- Seasonal insights
- Interactive maps

## Release Roadmap

### Release 1
- Generate detailed day-by-day itineraries using prompt-based input
- Include activities and at least two restaurant options per meal
- Base suggestions on ratings and relevance to user requests

### Release 2
- Visual map-based journey using location and route data
- Spatial visualization of itineraries

### Release 3
- Flight data integration
- Optimal travel dates and routes suggestions
- Pricing considerations

## Project Structure

```
trippy/
├── agents/         # AI agents for processing and recommendations
├── data/          # Data storage and processing
├── utils/         # Utility functions and API clients
├── app/           # Streamlit web application
└── ml/            # Machine learning models and training
```

## Development Status

### Day One – Initial Setup
- Created new Python project using Cursor as development environment
- Initialized Git repository and linked to GitHub
- Established folder structure for modular development
- Created initial files:
  - README.md
  - requirements.txt
  - Placeholder modules (prompt_parser.py, streamlit_app.py, api_clients.py)
- Successfully committed and pushed to GitHub

## Technical Stack
Future integrations planned:
- LangChain
- Claude
- Streamlit
- Flowise
- MLflow
- Various APIs:
  - Google Places
  - OpenWeather
  - And more...

## Next Steps
Building the core prompt interpreter agent to generate structured travel itineraries based on free-form user input.