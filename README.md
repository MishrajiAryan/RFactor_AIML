# RFactor AIML Results Portal

## Overview

The RFactor AIML Results Portal is a comprehensive web application designed to display and manage results from AI/ML quiz competitions organized by RaSoR (Research and Solutions for Robotics). This platform provides an intuitive interface for viewing individual submissions, rankings, and detailed performance analytics.

## Live Demo

**🌐 [View Live Application](https://rfactor-aiml-result.vercel.app/)**

## Features

### Core Functionality
- **Results Dashboard**: Clean, organized display of quiz results and participant rankings
- **Individual Profiles**: Detailed view of each participant's performance and submissions
- **Medal System**: Visual recognition with gold, silver, and bronze medal awards
- **Responsive Design**: Optimized for desktop and mobile viewing experiences
- **Data Persistence**: SQLite database integration for reliable data storage

### Technical Highlights
- Modern HTML5 structure with semantic markup
- Custom medal graphics and visual assets
- JSON-based data management for flexible content updates
- Deployment-ready configuration for Vercel hosting

## Project Structure

```
RFactor_AIML/
├── index.html              # Main application interface
├── studentData.json        # Participant data and results
├── rfactor_aiml.sqlite     # Database file
├── background.jpg          # Application background image
├── Rasor.ico              # Favicon for browser tab
├── gold.png               # Gold medal graphic
├── silver.png             # Silver medal graphic
├── bronze.png             # Bronze medal graphic
└── .idea/                 # IDE configuration files
```

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Database**: SQLite
- **Data Format**: JSON
- **Deployment**: Vercel
- **Development**: IntelliJ IDEA

## Getting Started

### Prerequisites
- Modern web browser with JavaScript support
- Local web server (optional, for development)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/MishrajiAryan/RFactor_AIML.git
   cd RFactor_AIML
   ```

2. **Open the application**
   - Open `index.html` directly in your browser, or
   - Use a local development server for enhanced features

3. **View results**
   - Navigate through the interface to explore participant results
   - Check individual performance metrics and rankings

## Data Management

### Student Data Format
The `studentData.json` file contains structured information about participants and their quiz performance. This format allows for easy updates and maintenance of results data.

### Database Integration
The SQLite database (`rfactor_aiml.sqlite`) provides persistent storage for more complex queries and data relationships.

## Deployment

This application is configured for seamless deployment on Vercel:

1. **Automatic Deployment**: Connected to this GitHub repository for continuous deployment
2. **Production URL**: [rfactor-aiml-result.vercel.app](https://rfactor-aiml-result.vercel.app/)
3. **Environment**: Optimized for production with CDN delivery

## Contributing

Contributions to improve the RFactor AIML Results Portal are welcome:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/enhancement`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/enhancement`)
5. Open a Pull Request

## About RaSoR

This project is part of the RaSoR (Research and Solutions for Robotics) initiative, focusing on promoting AI/ML education through interactive competitions and assessments.

## License

This project is open source and available under standard GitHub terms.

## Contact

For questions, suggestions, or support:
- **Repository**: [github.com/MishrajiAryan/RFactor_AIML](https://github.com/MishrajiAryan/RFactor_AIML)
- **Live Application**: [rfactor-aiml-result.vercel.app](https://rfactor-aiml-result.vercel.app/)

---

**Built with ❤️ for the AI/ML community**
