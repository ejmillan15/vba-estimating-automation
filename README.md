# VBA Estimating Automation System

## Overview

Developed a custom Excel VBA automation platform to streamline the estimating process for custom window treatment projects.

The system automates fabric calculations, hardware configuration, labor estimation, installation costs, manufacturing time calculations, and project summary generation.

---

## Business Problem

Project estimates were previously created manually, requiring multiple spreadsheets, repetitive calculations, and extensive review.

The process could take several days depending on project complexity.

---

## Solution

Designed and developed a VBA-based estimating system that:

- Automates project pricing calculations
- Generates room-by-room estimates
- Supports multiple curtain styles and hardware types
- Calculates labor and installation costs
- Applies manufacturing time factors
- Generates project-wide summaries automatically

---

## Key Features

### Curtain Style Logic

Supports multiple curtain styles:

- Ripple Fold (60%, 80%, 100%, 120% fullness)
- Pinch Pleat (100% fullness)
- French Pleat (100% fullness)

### Fabric Calculation Engine

Supports multiple fabric widths:

- 54"
- 110"
- 118"
- 126"
- 145"

Automatically calculates:

- Fabric quantities
- Lining requirements
- Material costs

### Hardware Configuration Engine

Supports:

- Track
- Cord Track
- Motorized Track
- H Rail Rod
- Motorized H Rail Rod

Includes dynamic dropdown logic and automated configuration rules.

### Installation & Labor Logic

Automatically applies installation pricing rules.

Example:

- Heights ≤130" → $6/ft
- Heights >130" → $12/ft

Supports:

- Scaffold allocation
- Helper allocation
- Installation cost distribution

### Manufacturing Time Engine

Uses business rules to estimate production effort based on:

- Curtain style
- Fabric type
- Project dimensions

### Summary Generation

Automatically consolidates all room worksheets into a final project summary.

---

## Technologies Used

- Microsoft Excel
- VBA (Visual Basic for Applications)
- Event-Driven Programming
- Data Validation
- Process Automation
- Business Workflow Design

---

## Results

### Business Impact

- Reduced estimating time by more than 95%
- Reduced manual calculation errors
- Standardized project pricing
- Improved workflow efficiency
- Automated repetitive estimating tasks

---

## System Architecture

```text
User Input
      ↓
VBA Event Handler Logic
      ↓
Business Logic Engine
      ↓
Cost & Configuration Engine
      ↓
Room Automation
      ↓
Summary Generation
      ↓
Final Project Estimate
```

## Screenshots

### Main Calculator Interface

![Main Calculator](screenshots/calculator/01-main-calculator-interface.png)

### Curtain Style Configuration

![Curtain Style](screenshots/calculator/02-curtain-style-dropdown.png)

### Hardware Configuration

![Hardware Configuration](screenshots/calculator/04-hardware-type-dropdown.png)

### Installation Logic

![Installation Logic](screenshots/calculator/11-installation-logic.png)

### Project Summary

![Summary](screenshots/calculator/13-summary-sheet.png)

### VBA Event Handler Logic

![Event Handler](screenshots/vba-event-handler/VBA%20Event%20Handler%20Logic.png)

### Business Logic Engine

![Business Logic](screenshots/business-logic-engine/CalculateHardwareCost().png)

---

## My Contribution

This project was designed and developed as an internal business automation solution.

Key contributions included:

- VBA development
- Business logic implementation
- Cost calculation engine design
- Hardware configuration workflows
- Dynamic dropdown automation
- Room management automation
- Summary generation and reporting
- User interface workflow design

---

## Note

This repository contains a sanitized portfolio version of the project. Company-specific pricing, customer information, and proprietary business data have been removed or modified.
