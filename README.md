# Insight-Scripts-Project-Template
OpenClinica Insight Scripts

## Alerts

The `Alerts` directory contains SQL scripts for generating various alerts. Each alert has a `live` and `test` version.

- **Alert 1 - Alert name**: Alerts for new SAEs and Notable Events, and updates to SAEs.

## Reports

The `Reports` directory contains SQL scripts for generating various reports.

### Custom Reports

- **Standard_AE_Report_Code**: Generates reports for adverse events.
- **Standard_Signing_Report_Code**: Generates reports for signing events.

### Standard Reports

- **Fully_Standard_Report_Code**: Contains standard report templates.


### Data Models

Contains data models used within other alerts and reports.



## IR

The `IR` directory contains SQL scripts related to the Image Repository (IR) system.

- **PatientsForIR.sql**: Creates a patient list for IR app upload.
  
## Versioning

Each script contains a version number in the comments. Updates should increment the version and document changes in the commit message.
