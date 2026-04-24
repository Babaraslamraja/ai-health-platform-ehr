# FHIR-Based Interoperability Layer for EHR Integration

## Overview

This project builds on a prior EHR data integration pipeline by introducing a basic HL7 FHIR-based interoperability layer.

It demonstrates how structured clinical data can be transformed into standardized FHIR resources (Patient, Observation, Condition) to simulate real-world healthcare data exchange between systems.

The project also highlights the importance of clinical data standards and introduces the concept of semantic interoperability through basic SNOMED CT awareness.

---

## Objectives

- Convert structured patient data into FHIR resources (JSON format)
- Simulate interoperability using standardized healthcare data structures
- Demonstrate linkage between patient, observations, and conditions
- Introduce foundational concepts of clinical terminology mapping (SNOMED CT)
- Show transition from raw clinical data to interoperable formats

---

## FHIR Resources Generated

The following FHIR resources are created:

- Patient → represents demographic information  
- Observation → represents clinical measurements (e.g., blood pressure, glucose)  
- Condition → represents diagnoses (e.g., hypertension, diabetes)  

Each resource follows a simplified HL7 FHIR structure and is linked appropriately.

---

## Project Structure

- `data/` → input dataset (shared care record)  
- `notebooks/` → transformation logic (FHIR conversion)  
- `outputs/` → generated FHIR JSON resources  

---

## Outputs

FHIR resources are generated and saved as JSON files:

- `patient.json`  
- `observation.json`  
- `condition.json`  

These outputs simulate how healthcare systems exchange standardized data.

---

## Technologies Used

- Python  
- Pandas  
- JSON  
- HL7 FHIR (conceptual implementation)  

---

## Key Achievements

- Transformed tabular healthcare data into structured FHIR resources  
- Demonstrated interoperability workflow using standardized formats  
- Established relationships between patient, observation, and condition data  
- Built foundational understanding of healthcare data standards  

---

## Key Insight

This project reinforces that healthcare interoperability is not only a technical challenge but also a matter of standards, structure, and governance.

Accurate data exchange requires alignment between systems, terminologies, and data models — not just data processing.

---

## Status

Completed – Demonstrates a foundational FHIR interoperability workflow using Python and pandas.