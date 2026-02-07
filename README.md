# 🚦 Automated Quality Assurance for Street Geometry Data (AI-Assisted)

## 📌 Hackathon Problem
**Problem 2 – Quality Assurance using AI (Simplified)**  
Organized by **Axes Systems GmbH**

---

## 🧠 Problem Overview
Cartographic applications process large volumes of vector data such as points, lines, and polygons.  
Currently, quality assurance (QA) of this data is performed **manually**, which is time-consuming and does not scale.

The goal of this project is to **automate one specific aspect of QA** using AI-assisted logic.

---

## 🎯 Scope of This Solution
- **Focus Area:** Rule-Based Geometry Validation  
- **Single Error Type Detected:** **Invalid Street (LineString) Geometry**
- **Input Format:** WKT (Well-Known Text)
- **Output:** Structured error report (JSON)

---

## ⚙️ Solution Approach
1. Read street geometries from a `.wkt` file
2. Convert each geometry into a computational object
3. Apply validation rules to detect:
   - Empty geometries
   - Zero-length streets
   - Invalid topology
4. Generate a clear, machine-readable error report

This replaces manual inspection with an automated QA pipeline.

---

## 🛠️ Technologies Used
- **Python**
- **Google Colab**
- **Shapely** (geometry parsing & validation)
- **JSON** (error reporting)

---

## 📂 Project Structure
