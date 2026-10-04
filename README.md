# EarthLungs GIS

## EarthLungs Spatial Intelligence Platform

**GIS • Remote Sensing • Drone Mapping • Restoration Intelligence**

EarthLungs GIS is the spatial intelligence platform for viewing EarthLungs site boundaries and running repeatable remote sensing analyses across active EarthLungs sites.

---

## EarthLungs Brand

The platform follows the official EarthLungs visual identity represented by the EarthLungs logo.

| Brand colour | Hex |
|---|---|
| 🟢 EarthLungs Green | `#349E40` |
| 🔵 EarthLungs Blue | `#33B9DD` |
| 🟢 Light Green | `#EAF5EC` |
| 🔵 Light Blue | `#EAF8FC` |

**Primary identity:** EarthLungs Green + EarthLungs Blue

The green represents the restoration and environmental side of the EarthLungs identity, while the blue complements the spatial, environmental and Earth-observation side of the platform.

---

## Current Coverage

The current production platform is connected to:

- 🇰🇪 Kenya
- 🇹🇿 Tanzania
- 🇲🇿 Mozambique

The platform uses approved EarthLungs country site assets and performs analysis for the selected EarthLungs site.

---

## Live GIS Application

### EarthLungs GIS Application

https://ee-nakwawi.projects.earthengine.app/view/earthlungs-gis

---

## Website

https://davidnakwawi.github.io/EarthLungs-GIS/

---

## Analysis Modules

The current production application contains seven analysis modules.

### 01 — NDVI

**Normalized Difference Vegetation Index**

Used for vegetation condition monitoring.

### 02 — NDRE

**Normalized Difference Red Edge**

Used to assess vegetation response using Sentinel-2 red-edge information.

### 03 — NDVI + NDRE Comparison

Comparison of NDVI and NDRE for the selected EarthLungs site across analysis periods.

### 04 — Temporal Change

Baseline versus current temporal change analysis for NDVI and NDRE.

### 05 — LULC

**Land Use / Land Cover**

Land-cover analysis using Google Dynamic World V1 with confidence screening.

### 06 — EVI

**Enhanced Vegetation Index**

Used for vegetation response assessment.

### 07 — NDWI

**Normalized Difference Water Index**

Used for water and moisture-related surface response.

These seven modules form the current locked production analysis scope.

---

## Standard Workflow

```text
Country
   ↓
EarthLungs Site
   ↓
Analysis
   ↓
Exact Date Selection
   ↓
Run Analysis
   ↓
Result
