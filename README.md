An interactive desktop web portal for self-storage facility administrators to manage, visual, and configure indoor navigation maps and storage unit routes.

Overview

Pandora Map PC serves as the desktop-optimized administrative counterpart to mobile indoor navigation systems. Built specifically for facility managers and staff, it provides a comprehensive interface to map out floor plans, set up routing nodes, track loading dock pathways, and configure unit locations across multi-story storage facilities.

Key Features

Visual Route Editor: Define and update pathways from loading docks to individual storage units.

Multi-Floor Navigation Management: Handle complex layouts, including hallways, elevators, and stairs.

Facility Node Configuration: Easily place and adjust entry points, dock bays, and unit coordinates.

High-Performance Rendering: Designed for fast rendering of large floor plans and complex node networks.

Tech Stack

Frontend: HTML5, CSS3, JavaScript (ES6+)

Styling: Responsive Desktop CSS / UI Framework

Mapping & Pathfinding: Interactive canvas/SVG rendering & pathfinding algorithms

Quick Start

Prerequisites

Node.js (v18.0 or higher)

npm or yarn

Installation

Clone the repository:
git clone https://github.com/noah-dsouza/pandora-map-PC.git
cd pandora-map-PC

Install dependencies:
npm install

Start the development server:
npm run dev

Open your desktop browser at http://localhost:3000.

Map & Data Configuration

To update or upload new facility layouts:

Store new SVG or vector floor plan assets in the project asset directory.

Configure facility nodes, unit maps, and routing rules within the config files.

Contributing

Fork the repository

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request
