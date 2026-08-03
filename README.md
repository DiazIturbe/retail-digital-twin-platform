### Interactive 3D Visualization & Decision Support for Retail Operations

> Transforming operational retail data into an interactive digital twin that supports merchandising, navigation, planning, and operational decision-making.

![Retail Digital Twin](assets/readme/digital_twin_hero.png)

![Unity](https://img.shields.io/badge/Unity-6-black?logo=unity)
![C%23](https://img.shields.io/badge/C%23-239120?logo=c-sharp&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-Prototype-success)
![License](https://img.shields.io/badge/License-MIT-blue)

The **Retail Digital Twin Platform** transforms operational retail information into an interactive three-dimensional representation of a real retail store.

Instead of relying on spreadsheets, merchandising directives and printed layouts, the platform combines operational metadata with an immersive Unity environment, allowing users to search products, navigate the store, visualize merchandising zones, and better understand retail operations through an interactive digital twin.

---

# Live Experience

🌐 **Interactive WebGL Demo**

*(GitHub Pages URL)*

🎥 **Video Demonstration**

*(YouTube / Portfolio Link)*

📖 **Portfolio Case Study**

*(Coming Soon)*

---

# Project Snapshot

- 🏬 Interactive digital replica of a real retail store
- 📦 1,647 operational product locations
- ✅ Zero missing products after metadata validation
- 🔎 Instant product search
- 🧭 Automatic navigation to any product
- 🎯 Interactive merchandising zone highlighting
- 🐍 Python-powered metadata generation pipeline

---

# Executive Summary

Large retail stores manage thousands of products distributed across dozens of departments and merchandising zones.

Although operational data exists in spreadsheets, product catalogues and merchandising directives, those resources rarely communicate one critical element: **space**.

The Retail Digital Twin Platform transforms operational retail information into a living digital environment that mirrors a real store.

Managers and merchandising teams can explore the store virtually, locate products instantly, understand layouts, visualize merchandising information and interact with operational data in ways that traditional reports cannot provide.

---

# The Challenge

Retail operations depend on numerous disconnected information sources.

- Product catalogues
- Inventory spreadsheets
- Merchandising directives
- Floor plans
- Staff experience

While these documents accurately describe products and layouts, they do not communicate the physical environment effectively.

Understanding where products are located, how departments connect, or how merchandising changes impact the store often requires significant manual interpretation.

---

# The Solution

The Retail Digital Twin Platform combines automated data preparation with an interactive Unity visualization environment.

Operational metadata is processed using Python before being imported into Unity, where it becomes an intelligent digital representation of the store.

The result is an operational decision-support platform capable of supporting merchandising, planning, training and store visualization.

---

# Live Demonstration

The platform can be explored directly in the browser using Unity WebGL.

Click the image below to watch the complete walkthrough.

[![Retail Digital Twin Demo](assets/readme/video_cover.png)](https://www.youtube.com/watch?v=wC4Yr8rvEIE)

---

# Platform Walkthrough

## Interactive Store Overview

Explore the complete retail environment while maintaining the real spatial relationships between departments, fixtures and merchandising zones.

![Store Overview](assets/readme/store_overview.png)

---

## Product Search & Operational Filters

Locate products instantly using SKU search or operational filters.

Available filters include:

- Brand
- Department
- Gender
- Sport
- Sale
- Best Sellers
- JD Access

![Search](assets/readme/search_filters.png)

---

## Smart Navigation

Navigate directly to any product location using Unity's NavMesh navigation system.

The platform automatically guides users through the store to the selected product.

![Navigation](assets/readme/navigation.png)

---

## Product Metadata

Every displayed product is connected to operational metadata.

Users can retrieve:

- Product image
- SKU
- Department
- Brand
- Category
- Display location

![Metadata](assets/readme/product_metadata.png)

---

## Zone Highlighting

Visualize merchandising zones and display walls interactively to better understand the operational layout of the store.

![Zones](assets/readme/zone_highlighting.png)

---

## Brand & Department Visualization

Quickly isolate products by operational attributes.

Examples include:

- Nike
- Adidas
- Men's
- Women's
- Footwear
- Accessories

making merchandising analysis considerably easier.

![Brand Filter](assets/readme/brand_filter.png)

---

# From Operational Data to Interactive Visualization

The digital twin is generated through an automated metadata pipeline.

![Pipeline](assets/readme/data_pipeline.png)

```
Store Layout

Product Catalogue

Merchandising Information

↓

Python Metadata Generator

↓

CSV Metadata

↓

Unity Import Pipeline

↓

Retail Digital Twin

↓

Search
Navigation
Visualization
Planning
```

The automated workflow allows operational information to be updated without manually rebuilding the Unity environment.

---

# Real-World Applications

Although developed as a retail proof-of-concept, the platform demonstrates how digital twins can support operational decision-making.

Potential applications include:

- Visual merchandising planning
- New employee onboarding
- Store familiarization
- Product location assistance
- Merchandising directive communication
- Layout validation
- Operational planning
- Interactive training
- Future digital twin initiatives

---

# Key Features

## Interactive Visualization

- Real-time 3D store exploration
- Camera presets
- Free camera navigation
- Interactive environment

### Product Discovery

- SKU search
- Product metadata
- Product images
- Store-wide lookup

### Operational Analytics

- Department highlighting
- Brand filtering
- Merchandising visualization
- Display wall visualization

### Data Integration

- Python preprocessing
- Automated metadata generation
- CSV synchronization
- Unity import pipeline

---

# Technology Stack

| Layer | Technologies |
|--------|--------------|
| Visualization | Unity 6 |
| Programming | C# |
| Data Processing | Python |
| Metadata Storage | CSV |
| Navigation | Unity NavMesh |
| User Interface | Unity UI |
| Version Control | Git & GitHub |

---

# Repository Structure

```text
Assets/
├── Scenes/
├── Scripts/
├── Prefabs/
├── Resources/
├── StreamingAssets/
├── UI/
└── Materials/

Python/
├── Metadata Generator
├── CSV Builder
└── Data Processing

Build/
Documentation/
```

---

# Roadmap

### Next Improvements

- Enhanced UI
- Additional metadata panels
- Improved search experience
- Performance optimization

### Long-Term Vision

- Azure Digital Twins integration
- GIS integration
- Multi-store environments
- Live inventory synchronization
- AI-assisted merchandising recommendations
- Space optimization analytics
- Customer movement visualization

---

# About the Author

**Diego Ernesto Díaz Iturbe**

Data Analytics • Retail Operations • Automation • Interactive Visualization

This project demonstrates how operational data, software engineering and interactive visualization can be combined to create practical decision-support tools for real-world retail environments.

---

## Portfolio

https://impactomex.wixsite.com/eportfolio

## LinkedIn

https://linkedin.com/in/diegodiaziturbe
