# Hardness Testing & Statistical Analysis of Heat-Treated W-1 Steel

**Course:** Mechanical Engineering Laboratory I  
**Project Type:** Materials Testing & Statistical Analysis  
**Timeline:** Spring 2026  
**Focus Areas:** Rockwell hardness testing, nanoindentation, hypothesis testing, materials characterization

---

## Project Overview

This laboratory project investigated the hardness behavior of **heat-treated W-1 drill rod steel** using two experimental techniques:

- **Rockwell hardness testing**
- **Nanoindentation**

Two steel specimens (Type A and Type B) were tested to determine whether differences in **tempering temperature** produced statistically significant differences in hardness and deformation behavior.

The study combined **experimental materials testing with statistical analysis**, including descriptive statistics and a two-sample hypothesis test to compare the hardness of the two materials.

---

## Engineering Problem

Heat treatment processes such as tempering significantly influence the mechanical properties of steel, including hardness and resistance to plastic deformation.

The engineering objective of this experiment was to determine:

- Whether two heat-treated steel samples exhibited **statistically different hardness values**
- How tempering temperature influences **plastic deformation behavior**
- Whether results from **macro-scale hardness testing** and **nanoindentation** provide consistent conclusions

Understanding these relationships is critical in selecting materials for components that require **specific strength, wear resistance, and durability characteristics**.

---

## Materials & Equipment

**Materials**

- W-1 Drill Rod Steel – Type A
- W-1 Drill Rod Steel – Type B

**Testing Equipment**

- Mitutoyo HR-320MS **Rockwell Hardness Tester**
- Anton Paar **Nanoindentation Tester**

**Analysis Tools**

- Microsoft Excel
- MATLAB

---

## Experimental Methods

### Rockwell Hardness Testing

Rockwell hardness measurements were taken using the **HRC scale**. Multiple indentation tests were performed on each steel specimen to generate a dataset suitable for statistical analysis.

Collected data was used to compute:

- Mean hardness
- Standard deviation
- Sample variance

A **two-sample unpaired t-test** was then performed to determine whether the difference in hardness between the two materials was statistically significant.

---

### Nanoindentation

Nanoindentation testing was used to analyze mechanical behavior at smaller scales. The experiment measured:

- **Vickers hardness**
- **Plastic work**
- **Elastic indentation modulus**

These values were analyzed as a function of **maximum indentation depth**, providing insight into the materials' deformation response under localized loading.

---

## Statistical Analysis

To evaluate whether the hardness values differed significantly, a **two-sample hypothesis test** was performed.

**Null Hypothesis (H₀):**  
The mean hardness of Type A steel equals the mean hardness of Type B steel.

**Alternative Hypothesis (H₁):**  
The mean hardness values of the two materials are different.

A **t-statistic** was calculated and compared to the critical value for a 95% confidence interval.

### Results

- **Mean Hardness (Type A):** 62.23 HRC  
- **Mean Hardness (Type B):** 58.54 HRC  

- **t-Statistic:** 13.10  
- **Critical t Value:** 2.009  

Because the calculated t-value was significantly larger than the critical value, the **null hypothesis was rejected**, confirming a statistically significant difference in hardness.

---

## Key Experimental Findings

### Rockwell Hardness Results

- Type A steel exhibited **higher average hardness**
- Hardness variation remained small across repeated measurements
- Statistical testing confirmed the difference between materials was **significant**

---

### Nanoindentation Results

Nanoindentation measurements supported the Rockwell test results.

Key observations:

- **Type A exhibited higher hardness values**
- **Type B demonstrated greater plastic deformation behavior**
- Elastic indentation modulus remained relatively similar between samples

These results suggest the different tempering conditions altered **plastic deformation characteristics without drastically changing elastic stiffness**.

---

## Engineering Interpretation

The results indicate that **lower tempering temperature produced a harder microstructure** in Type A steel.

Higher hardness corresponds to:

- Greater resistance to indentation
- Reduced plastic deformation
- Potentially increased wear resistance

However, increased hardness can also correlate with **reduced ductility**, which is an important design tradeoff when selecting materials for engineering applications.

---

## Skills Demonstrated

- Materials characterization and testing
- Rockwell hardness measurement
- Nanoindentation analysis
- Statistical hypothesis testing
- Experimental data interpretation
- Engineering technical communication

---

## Conclusion

This experiment demonstrated how heat treatment influences the mechanical properties of steel. Both Rockwell hardness testing and nanoindentation analysis showed that **Type A steel exhibited greater hardness than Type B steel**.

Statistical hypothesis testing confirmed that the difference in hardness between the two materials was **significant at the 95% confidence level**.

The project illustrates how **experimental measurement, statistical analysis, and engineering reasoning** combine to evaluate material behavior and support design decisions.

---

## Supporting Documents

- 📄 **Lab Report**  
  *Outlines Procedure, Results, and Contributions*  
  [View document](https://raw.githubusercontent.com/benjamin-schaffer/benjamin-schaffer.github.io/main/Lab%201%20Group%20Memo%20(1).pdf)
