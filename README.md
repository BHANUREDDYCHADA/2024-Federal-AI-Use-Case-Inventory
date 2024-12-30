# 2024 Federal Agency AI Use Case Inventory

This 2024 Federal Agency Artificial Intelligence (AI) Use Case Inventory repository is a centralized consolidation of AI use case inventories from across U.S. Federal agencies, consistent with Section 5 of Executive Order (EO) 13960, “Promoting the Use of Trustworthy Artificial Intelligence in the Federal Government,” and pursuant to the Advancing American AI Act and OMB Memorandum M-24-10, “Advancing Governance, Innovation, and Risk Management for Agency Use of Artificial Intelligence.” The inventory provides transparency into how Federal agencies are using AI systems to advance their missions and deliver services to the public.

## Overview

Federal agencies, with limited exceptions, are required to conduct annual inventories of their AI use cases and make this information publicly available. Federal agencies are to post a machine-readable CSV of all publicly releasable use cases on their agency’s AI website. For more information on AI Use Case reporting instructions, refer to the Guidance For 2024 Agency Artificial Intelligence Reporting found in the Additional Resources section. 

## Repository Structure
```
├── data/
│   ├── 2024_consolidated_ai_inventory_raw.csv      # Raw Consolidated Inventory CSV
│   ├── 2024_consolidated_ai_inventory_raw.xls      # Raw Consolidated Inventory XLS
│   ├── 2023_consolidated_ai_inventory_raw.xls      # Raw Consolidated Inventory XLS  
├── validation/                    
    ├── data_dictionary.yaml                   # 2024 Use Case Inventory Data Dictionary
```

## Summary
As of December 17, 2024, the following represents a summary of the current consolidated Federal dataset:
- 37 agency submissions
- 1757 AI use cases
- 227 rights-impacting and/or safety-impacting use cases

| Agency Name | Total Publicly Reported AI Use Cases | Safety and Rights-Impacting Use Cases |
|------------|-----------------------------------:|------------------------------------:|
| Department of Agriculture | 89 | 4 |
| Department of Commerce | 57 | 0 |
| Department of Energy | 79 | 3 |
| Department of Health and Human Services | 271 | 4 |
| Department of Homeland Security | 183 | 34 |
| Department of Housing and Urban Development | 6 | 1 |
| Department of Labor | 70 | 2 |
| Department of State | 51 | 0 |
| Department of the Interior | 180 | 0 |
| Department of the Treasury | 54 | 2 |
| Department of Veterans Affairs | 229 | 145 |
| Environmental Protection Agency | 17 | 1 |
| General Services Administration | 24 | 1 |
| National Aeronautics and Space Administration | 18 | 0 |
| National Science Foundation | 16 | 0 |
| Office of Personal Management | 2 | 2 |
| Social Security Administration | 23 | 9 |
| United States Agency for International Development | 137 | 17 |
| Commodity Futures Trading Commission | 4 | 1 |
| Consumer Financial Protection Bureau | 4 | 0 |
| Election Assistance Commission | 2 | 0 |
| Equal Employment Opportunity Commission | 8 | 0 |
| Federal Deposit Insurance Corporation | 55 | 1 |
| Federal Energy Regulatory Commission | 4 | 0 |
| Federal Housing Finance Agency | 18 | 0 |
| Federal Reserve Board of Governors | 50 | 0 |
| Federal Trade Commission | 6 | 0 |
| National Archives and Records Administration | 9 | 0 |
| National Transportation Safety Board | 2 | 0 |
| Pension Benefit Guaranty Corporation | 2 | 0 |
| Postal Regulatory Commission | 1 | 0 |
| Presidio Trust | 5 | 0 |
| Securities and Exchange Commission | 28 | 0 |
| Tennessee Valley Authority | 39 | 0 |
| United States Agency for Global Media | 8 | 0 |
| United States Commission on Civil Rights | 2 | 0 |
| United States Trade and Development Agency | 4 | 0 |
| **Total** | **1,757** | **227** |


## Key Considerations

- All reported agency AI use cases, with limited exceptions, are included in this inventory. Note, certain use cases are not required to be individually inventoried or to be shared or publicly released. Excluded categories include:
    - Research and development (R&D) use cases (However, agencies must still inventory any R&D use case that is currently being used to control or significantly influence a decision or outcome about individuals, or that has an approved agreement for transition into agency operations.)
    - National Security Systems
    - Intelligence Community systems
    - Department of Defense use cases
    - Use cases whose sharing would be inconsistent with applicable law and governmentwide policy
- In limited circumstances, use case details may be reported to OMB and withheld from public release.


## Submissions Schedule
- Agency submissions due: December 16, 2024.
- Updates will be processed on a rolling basis.

## Additional Resources
- [Executive Order 14110](https://www.govinfo.gov/content/pkg/FR-2023-11-01/pdf/2023-24283.pdf)
- [OMB Memorandum M-24-10](https://www.whitehouse.gov/wp-content/uploads/2024/03/M-24-10-Advancing-Governance,-Innovation,-and-Risk-Management-for-Agency-Use-of-Artificial-Intelligence.pdf)
- [Advancing American AI Act](https://www.congress.gov/117/plaws/publ263/PLAW-117publ263.pdf)
- [2024 AI Use Case Inventory Reporting Instructions](https://www.whitehouse.gov/wp-content/uploads/2024/03/DRAFT-Guidance-for-Agency-Artificial-Intelligence-Reporting-per-EO14110.pdf#:~:text=With%20limited%20exceptions%2C%20agencies%20must%20%28I%29%20conduct%20an,waivers%20from%20Section%205%20of%20OMB%20Memorandum%20M-24-10.)
- [AI.gov](https://ai.gov/ai-in-gov/)
- [CIO.gov](https://www.cio.gov/policies-and-priorities/Executive-Order-13960-AI-Use-Case-Inventories-Reference/)

## Contact
This data collection and repository is maintained by Morgan Zimmerman and Varoon Mathur. For questions about this repository, please open an issue or contact the maintainers at OFCIO_AI@omb.eop.gov. For agency-specific inquiries, please contact the relevant agency Chief Artificial Intelligence Officer.
