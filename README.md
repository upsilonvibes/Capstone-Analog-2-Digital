# 🏗️ Project: Analog to Digital (A2D)

### Multimodal AI Document Digitization & Audit Report
**Date:** April 2026  
**Tools:** Gemini 3 Flash, HTML5, CSS3  
**Objective:** To evaluate the precision of multimodal AI in converting varied physical media—including handwritten scripts, printed brochures, and technical lab notes—into structured, web-ready digital formats.

---

## 📋 Executive Summary
This project demonstrates a high-fidelity workflow for digitizing "analog" data. By leveraging AI vision, static images of physical documents were transformed into searchable, structured HTML tables and lists. 

**Average Accuracy:** ~98.8%  
**Total Data Points Extracted:** 100+

---

## 📂 Document Catalog & Findings

### 1. Handwritten Script (Spanish Lessons)
* **Media:** Notebook entry with mixed ink colors and margin annotations.
* **Challenge:** Slanted text near the notebook spine and non-literal annotations.
* **Result:** 100% character accuracy for the Spanish text, including inverted punctuation (¡, ¿).

### 2. University Brochure (NUAA)
* **Media:** Three-fold printed flyer with multi-currency tables and vertical academic lists.
* **Challenge:** Normalizing "¥" and "CNY" symbols while flattening vertical course lists into CSV-compatible rows.
* **Result:** Successful extraction of 52 distinct data points, including complex tuition structures and technical course titles like "Econometrics."

### 3. Physics Lab Practical Notes
* **Media:** Handwritten grading table with red-ink raw score annotations and bulleted definitions.
* **Challenge:** Distinguishing between primary scores and raw fractions (e.g., 78/80) written in different ink.
* **Result:** Perfect extraction of student grades and expansion of technical shorthand (e.g., "btn" to "between").

---

## 🛠️ Technical Insights

### Key Strengths
* **Data Flattening:** The AI effectively converted complex vertical layouts into horizontal, machine-readable rows.
* **Contextual Intelligence:** The model understood domain-specific context, accurately identifying educational grading structures and technical academic majors.

### Human-in-the-Loop Necessity
The project highlighted the importance of human auditing. For instance, the AI interpreted the phrase "No entiendo" as "I don't know" rather than the literal "I don't understand," showing a bias toward common conversational translations over verbatim transcription.

---

## 🚀 How to Use
1.  **View Report:** Open `index.html` in any modern browser to view the formatted digitization report.
2.  **Styles:** Custom styling is handled via the separate `style.css` file to ensure a clean, professional "Technical Report" aesthetic.
3.  **Data Export:** The HTML tables are structured to be easily copy-pasted into Excel or Google Sheets for further analysis.

---

## ⚖️ License & Copyright
&copy; April 2026 | Analog To Digital Research