# Inventory Management Module

This module handles comprehensive inventory management for the Agri ERP system.

## Overview

The Inventory Management module is a comprehensive component of the Agri ERP system, providing complete inventory control and management capabilities. It manages agricultural inputs, equipment, storage facilities, warehouses, and supplier relationships to optimize resource utilization and supply chain efficiency.

## Sub-modules

### Input Management
- • Agricultural input tracking (seeds, fertilizers, pesticides)
- • Quality control and certification management
- • Usage tracking and application records
- • Expiration date monitoring and alerts

### Equipment Management
- • Equipment registration and asset tracking
- • Maintenance scheduling and service records
- • Depreciation tracking and asset valuation
- • Utilization monitoring and performance analysis

### Storage Management
- • Storage facility capacity management
- • Environmental condition monitoring
- • Inventory allocation and space optimization
- • Stock movement and transfer tracking

### Warehouse Operations
- • Receiving and shipping management
- • Pick and pack workflow automation
- • Inventory counting and audit procedures
- • Order fulfillment and distribution

### Supplier Management
- • Supplier registration and qualification
- • Purchase order creation and management
- • Performance tracking and evaluation
- • Contract management and terms negotiation

## Key Features

• Real-time Inventory Tracking: Live inventory levels with automated reorder points
• Barcode/RFID Integration: Advanced scanning and identification systems
• Batch and Lot Tracking: Complete traceability from source to application
• Multi-location Support: Management across multiple storage facilities
• Automated Reporting: Comprehensive analytics and inventory reports
• Mobile Access: Field-ready mobile applications for inventory management
• Integration Ready: Seamless integration with procurement and production modules

## Directory Structure

```
inventory/
├── controllers/
│   ├── InputController.js
│   ├── EquipmentController.js
│   ├── StorageController.js
│   ├── WarehouseController.js
│   └── SupplierController.js
├── services/
│   ├── InputService.js
│   ├── EquipmentService.js
│   ├── StorageService.js
│   ├── WarehouseService.js
│   └── SupplierService.js
├── models/
│   ├── Input.js
│   ├── Equipment.js
│   ├── Storage.js
│   ├── Warehouse.js
│   ├── Supplier.js
│   ├── Transaction.js
│   └── Contract.js
├── views/
│   ├── InputManagement.jsx
│   ├── EquipmentTracking.jsx
│   ├── StorageDashboard.jsx
│   ├── WarehouseOperations.jsx
│   └── SupplierPortal.jsx
└── tests/
    ├── unit/
    └── integration/
```

## API Endpoints

• GET /api/inventory/inputs - Get all agricultural inputs
• POST /api/inventory/inputs - Create new input record
• GET /api/inventory/equipment - Get equipment inventory
• POST /api/inventory/equipment - Register new equipment
• GET /api/inventory/storage - Get storage facility data
• POST /api/inventory/transactions - Record inventory transaction
• GET /api/inventory/suppliers - Get supplier information
• POST /api/inventory/purchase-orders - Create purchase order

## Integration Points

• Farm Management Module: Field requirements and resource planning
• Crop Production Module: Input usage and harvest storage
• Livestock Module: Feed inventory and equipment sharing
• Financial Module: Cost tracking and budget management
• Procurement Module: Purchase requisitions and supplier management
• Analytics Module: Inventory performance and optimization insights
• External Systems: ERP integrations and supplier portals

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
