CH50 Complement Assay Analysis

Quantitative Analysis of CH50 Complement Hemolytic Assay Using the Von Krogh Method

 Overview

The **CH50 (50% complement hemolytic) assay** is a functional assay used to evaluate the overall hemolytic activity of the classical complement pathway.

In the assay, patient or experimental serum is serially diluted and incubated with antibody-sensitized erythrocytes. Complement activation results in erythrocyte lysis, which is measured as percentage hemolysis.

The **CH50 value** represents the serum dilution producing approximately **50% hemolysis** under the defined assay conditions.

This project demonstrates a reproducible Python workflow for analyzing serial-dilution CH50 assay data and calculating CH50 values using the **Von Krogh mathematical method**.

> Important: All data in this repository are synthetic and created for educational and portfolio purposes. They are not patient data or real laboratory results.

---

# Scientific Background

The complement system is an important component of innate immunity and contributes to:

- Opsonization
- Inflammation
- Immune-complex clearance
- Pathogen elimination
- Membrane attack complex formation

The classical complement pathway** can be activated following recognition of antibody-antigen complexes.

The functional CH50 assay evaluates the ability of serum complement components to produce hemolysis of antibody-sensitized erythrocytes.

The basic experimental concept is:

text
Serum
  │
  ▼
Serial dilution
  │
  ▼
Antibody-sensitized erythrocytes
  │
  ▼
Complement activation
  │
  ▼
Membrane attack complex formation
  │
  ▼
RBC lysis
  │
  ▼
Percentage hemolysis
  │
  ▼
CH50 calculation
