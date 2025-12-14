# Project Meeting Minutes & Progress Log

**Team:** Bastien & Mael
**Module:** C-250-01
**Topic:** AI for Predictive Maintenance

---

##  Meeting 1: Project Kick-off
**Date:** October 25, 2024
**Agenda:**
- Review of module requirements (Assessment Specification).
- Selection of the AI topic.
- Role assignment.

**Decisions:**
- **Topic Selected:** Predictive Maintenance for Aircraft Engines.
- **Data Source:** We decided to use the NASA C-MAPSS dataset (Turbofan degradation) as it is the industry standard for this type of problem.
- **Roles:**
    - Mael: Lead Developer (Python/Colab) & Data Analysis.
    - Bastien: Documentation (GitHub) & Presentation structure.

---

##  Meeting 2: Development Phase
**Date:** November 20, 2024
**Agenda:**
- Progress check on data loading.
- Algorithm selection.

**Progress & Issues:**
- **Success:** Data successfully loaded into Google Colab.
- **Challenge:** We struggled to define the "Target" variable.
- **Solution:** We implemented a logical calculation: `RUL = Max_Cycle - Current_Cycle`.
- **Model Choice:** We decided to start with a Random Forest Regressor because it is robust and handles non-linear sensor data better than simple regression.

---

##  Meeting 3: Finalization & Portfolio
**Date:** December 10, 2024
**Agenda:**
- Review of model performance (RMSE).
- GitHub repository cleanup.
- Preparation for the Viva/Presentation.

**Outcomes:**
- **Results:** Model achieved an RMSE of ~41 cycles, which is acceptable for a first prototype.
- **Portfolio:** Old files removed, README updated with specific contributions.
- **Next Steps:** Create the PowerPoint slides for the final defense.
