# Project Instructions

## WEDNESDAY: Complete Workflow Phase 1-3

Follow the instructions in
[⭐ **Workflow: Apply Example**](https://denisecase.github.io/pro-analytics-02/workflow-b-apply-example-project/).

Complete:

1. Phase 1. **Start & Run** – copy the project and confirm it runs
2. Phase 2. **Change Authorship** – update the project to your name and GitHub account
2. Phase 3. **Read & Understand** – review the project structure and code

## FRIDAY/SUNDAY: Complete Workflow Phases 4-5

Complete:

1. Phase 4. **Make a Technical Modification**
2. Phase 5. **Apply the Skills to a New Problem**

## Topic

Static anomaly detection using simple domain thresholds.

In this project, you will detect anomalies in static tabular data by defining and applying reasonable maximum thresholds.

## Learning Objectives

After completing this project, you should be able to:

- Define what an anomaly is within a specific domain context.
- Explain how domain knowledge influences anomaly detection.
- Read a CSV file into a DataFrame.
- Apply boolean filtering to detect threshold violations.
- Write anomaly results to an artifacts file.
- Run and validate a professional Python project using `uv`.

## Example Code

The example file is located in `src/cintel/`.

It demonstrates:

- reading a CSV file into a DataFrame
- defining simple maximum thresholds
- detecting rows where values exceed those thresholds
- logging the pipeline process
- writing anomalies to an artifacts CSV file

Make sure you have read and successfully run the example before creating your own version.

## Dataset

The example dataset is located in the `data/` folder.

Each row represents one observation and includes:

- `age_years` - age in years
- `height_inches` - height in inches

The example data represents a pediatric clinic.

## Your Task

Using the example as a guide:

1. Copy `src/cintel/anomaly_detector_case.py`.
2. Rename the copy to `src/cintel/yourname_anomaly_detector.py` (all lowercase, no spaces).
3. Copy `data/clinic_data_case.csv`.
4. Rename the copy to `data/clinic_data_yourname.csv`.
5. Modify the dataset to represent a **different population or scenario** (for example: adult clinic patients, dogs at a veterinary clinic, or tortoises at a wildlife center).
6. Define reasonable maximum thresholds for:
   - age (in years)
   - height (in inches)
7. Detect anomalies using your thresholds.
8. Output anomalies to your custom artifacts file.
9. Ensure your script logs meaningful output.

Your logic should remain simple.
You do not need to introduce advanced statistical methods in this module.

## What to Look For

- Which rows clearly violate your thresholds?
- Are there borderline cases?
- Would your thresholds change with more domain knowledge?
- How might this process change if the data were updated continuously?

This discussion connects static anomaly detection to **continuous intelligence systems**, where observations arrive repeatedly over time and anomalies may signal changes in system behavior.
