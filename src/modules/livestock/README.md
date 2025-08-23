# Livestock Management Module

This module handles comprehensive livestock management for the Agri ERP system.

## Overview

The Livestock Management module is a comprehensive component of the Agri ERP system, providing complete livestock operations management capabilities. It manages animal registration, health monitoring, feeding programs, breeding operations, and production tracking to optimize livestock productivity and animal welfare.

## Sub-modules

### Animal Management
• Animal registration and identification tracking
• Individual animal profiles and history
• Species and breed management
• Animal inventory and transfer operations
• Performance monitoring and statistics

### Health Management
• Veterinary care and treatment records
• Vaccination scheduling and tracking
• Disease monitoring and prevention
• Health alerts and notifications
• Medical history maintenance

### Feed Management
• Feed inventory and distribution
• Nutritional planning and optimization
• Feed quality control and testing
• Consumption tracking and analysis
• Automated feeding schedule management

### Breeding Management
• Breeding program planning and execution
• Genetic tracking and lineage management
• Reproduction cycle monitoring
• Mating records and offspring tracking
• Performance-based breeding decisions

### Production Management
• Milk production tracking and analysis
• Egg production monitoring
• Meat production and processing records
• Quality control and grading
• Productivity optimization insights

## Key Features

• Real-time Animal Tracking: Live monitoring of animal locations and status
• Health Monitoring: Comprehensive veterinary care management system
• Automated Feeding: Smart feeding schedules and nutritional optimization
• Breeding Analytics: Data-driven breeding program management
• Production Optimization: Performance tracking and productivity insights
• Mobile Access: Field-ready mobile applications for livestock management
• Integration Ready: Seamless integration with farm management and inventory modules

## Directory Structure

```
livestock/
├── controllers/
│   ├── AnimalController.js
│   ├── HealthController.js
│   ├── FeedController.js
│   ├── BreedingController.js
│   └── ProductionController.js
├── services/
│   ├── AnimalService.js
│   ├── HealthService.js
│   ├── FeedService.js
│   ├── BreedingService.js
│   └── ProductionService.js
├── models/
│   ├── Animal.js
│   ├── Health.js
│   ├── Feed.js
│   ├── Breeding.js
│   ├── Production.js
│   ├── Treatment.js
│   └── VeterinaryRecord.js
├── views/
│   ├── AnimalManagement.jsx
│   ├── HealthDashboard.jsx
│   ├── FeedingSchedule.jsx
│   ├── BreedingProgram.jsx
│   └── ProductionTracking.jsx
└── tests/
    ├── unit/
    └── integration/
```

## API Endpoints

• GET /api/livestock/animals - Get all animals with filtering options
• POST /api/livestock/animals - Register new animal
• GET /api/livestock/animals/:id - Get specific animal details
• PUT /api/livestock/animals/:id - Update animal information
• POST /api/livestock/animals/:id/transfer - Transfer animal ownership
• GET /api/livestock/health - Get health records
• POST /api/livestock/health/treatment - Record medical treatment
• GET /api/livestock/feed - Get feeding schedules
• POST /api/livestock/feed/schedule - Create feeding schedule
• GET /api/livestock/breeding - Get breeding records
• POST /api/livestock/breeding/mate - Record mating event
• GET /api/livestock/production - Get production data
• POST /api/livestock/production/record - Record production entry

## Integration Points

• Farm Management Module: Pasture allocation and resource planning
• Inventory Module: Feed inventory and equipment management
• Financial Module: Cost tracking and revenue management
• Crop Production Module: Feed crop planning and utilization
• Analytics Module: Performance analytics and optimization insights
• Veterinary Systems: External veterinary service integrations
• IoT Devices: Sensor data integration for automated monitoring

## Installation and Setup

1. Install dependencies:
```bash
npm install
```

2. Configure environment variables:
```bash
cp .env.example .env
```

3. Run database migrations:
```bash
npm run migrate
```

4. Start the development server:
```bash
npm run dev
```

## Contributing

Please read the main project CONTRIBUTING.md for guidelines on contributing to this module.

## License

This module is part of the Agri ERP system and follows the same licensing terms.
