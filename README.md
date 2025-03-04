# HandReceipt Complete Pitch Deck Slide Guide

This directory contains a comprehensive guide for creating and presenting a pitch deck for HandReceipt, a blockchain-based supply chain management solution targeting both military and commercial markets.


## About HandReceipt

HandReceipt is a blockchain-powered inventory management platform that digitizes supply chain operations for both military and commercial applications. The solution replaces manual, paper-based processes with secure digital records, QR code scanning, and automated verification through blockchain technology.

## Design System

The pitch deck utilizes a Palantir-inspired design system that creates a high-tech, industrial aesthetic appropriate for both defense and commercial audiences. The system supports both dark and light modes while maintaining a consistent visual language throughout.

### Theme System

The design implements a comprehensive theming system using CSS variables:

- **Dark Theme (Default)**: Deep backgrounds with high contrast text and bright accent colors to convey a technical, secure aesthetic.
- **Light Theme**: Clean, bright backgrounds with darker text for high readability in well-lit environments.
- **Theme Switching**: Interactive toggle buttons allow presenters to switch between themes based on presentation environment.

### Typography

- **Primary Font**: IBM Plex Sans - A modern sans-serif typeface with technical precision and clarity
- **Monospace Font**: IBM Plex Mono - Used for technical information, data points, and terminal-style elements
- **Hierarchy**:
  - Slide titles: Large uppercase with terminal-style prefix (">")
  - Section headers: Uppercase with underscore suffix (e.g., "DEFENSE_")
  - Body text: Clean, readable with appropriate contrast ratios

### Color Palette

- **Primary Colors**:
  - Dark theme: `#0a0a0a` (background), `#ffffff` (text), `#0077cc` (primary accent), `#ff6b00` (secondary accent)
  - Light theme: `#f5f5f5` (background), `#1a1a1a` (text), `#0066b3` (primary accent), `#e65c00` (secondary accent)

- **Contextual Colors**:
  - Defense/Military: Blue accent (`#0077cc`) with navy backgrounds (`#14181f`)
  - Commercial: Orange accent (`#ff6b00`) with warm backgrounds (`#1a1a14`)
  - Shared elements: Purple accent (`#7b68ee`) with neutral backgrounds

### Visual Elements

- **Grid Background**: Angular grid pattern providing depth and technical context
- **Angular Shapes**: Sharp corners and geometric forms to convey precision and engineering rigor
- **Hexagonal Sections**: Stylized shapes for market segmentation and technology components
- **Terminal-Style Markers**: ">" characters before important points, mimicking command-line interfaces
- **Underscores**: Used as suffixes for section titles to evoke code naming conventions

### Component Styling

- **Cards**: High-contrast backgrounds with border accents and subtle shadows
- **Buttons**: Minimal styling with hover states and monospaced typography
- **Feature Items**: Interactive elements with icon markers and descriptive text
- **Process Steps**: Numbered elements with clear progression indicators
- **Data Visualizations**: Clean, technical styling with appropriate accent colors based on context

### Responsive Design

The design system is fully responsive, adjusting layout and visual hierarchy appropriately for different screen sizes while maintaining the industrial, high-tech aesthetic.

### Implementation Notes

- CSS variables enable consistent theming and easy updates across all slides
- JavaScript handles theme switching with smooth transitions between modes
- The design system emphasizes readability and information hierarchy while conveying the technical sophistication of the HandReceipt platform
