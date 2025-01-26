# DonateWater-Youth-Driven-Citizen-Science
Comprehensive research of the water source characteristics, user experiences, and environmental conditions that contribute to the analysis of water access and quality
# DonateWater Dataset
## Overview

The DonateWater dataset is a product of a youth-driven citizen science initiative aimed at addressing water access challenges in Nigeria. The dataset contains information on water sources, functionality, ownership, and accessibility collected by volunteers using the DonateWater mobile application. This dataset supports research aligned with Sustainable Development Goal 6 (Clean Water and Sanitation).

## Contents
The dataset includes the following information:

* **Water source type and functionality**
* **Water quality and treatment**
* **Accessibility and ownership**
* **Geo-located data of water sources**

## Dataset Format
The dataset is provided in CSV format and includes the following fields: 
* `Id`: Unique identifier for each entry. 
* `comment`: General observations or notes about the water source.
* `creationTimeStamp`: Date and time of data submission.
* `geometry`: Generalized geolocation of the water source.
* `peopleTravelToWaterSource`: Time taken by individuals to travel to the water source.
* `responsibleForFetch`: Demographics responsible for fetching water.
* `Status`: Data validation status.
* `waterDrinkable`: Whether the water is drinkable.
* `waterFree`: Whether the water is free to access
* `waterPublic`: Ownership of the water source (public/private).
* `waterSourceLocation`: Geographic coordinates of the water source
* `waterState`: Physical state of the water (e.g., clear, muddy).
* `waterTreated`: Specifies if the water is treated and the method used.
* `waterType`: Type of water source (e.g., borehole, hand-dug well).
* `waterUsed`: Whether the water is used for drinking.
* `doYouQueue`: Response on whether users queue for water and under what circumstances
* `ImageUrls`: URLs to images submitted by the participant for the water source
* `UserEmail`: Anonymized hash of the user's email who submitted the survey
* `userPositionSurveyCreatedLat` `userPositionSurveyCreatedLng` `userPositionSurveyStartedLat` `userPositionSurveyStartedLng`: Latitude and longitude positions of the citizen or user
* `waterSourceNearby`: Indicates if there are other water sources nearby.

<br>

## Anonymization Steps
To ensure the privacy and security of contributors, the dataset has been anonymized. Below are the steps taken to protect sensitive information:
1. **Removal of Personal Identifiable Information (PII):**
   - The `UserEmail` field was anonymized as part of users data protection compliance.
<!-- 2. **Location Data Generalization:**
    - Precise geolocation coordinates were rounded to two decimal places to ensure a 1 km generalization radius. -->
2. **Comment Sanitization:**
    - The `comment` field was scanned for personal references, which were removed or redacted where necessary.
<!-- 4. **Volunteer Location Masking:**
   - The volunteerLocation field was excluded to protect contributors' locations.-->
3. **Image Data Handling:**
    - URLs in the `ImageUrls` field were reviewed. Any image that might include identifiable details was removed or redacted.
4. **Randomization of Identifiers:**
    - The `ID` field was randomized to prevent traceability to individual submissions.
5. **Validation and Final Review:**
    - The dataset underwent a manual review to ensure no residual sensitive information was left in the final version.
<br>

## Usage Guidelines
This dataset is provided for research and educational purposes only. Users must ensure compliance with applicable data protection regulations when analyzing and using this data.

<br>

## Citation
If you use this dataset in your research or publication, please cite:
> DonateWater Youth Climate Action Foundation. (2024). DonateWater Dataset. [DOI/Link to be here]

<br>

## Contact
For inquiries about this dataset, please contact:
- DonateWater Youth Climate Action Foundation (DWYCAF)
- Web: https://www.donatewater.ng
- Email: [info@donatewater.ng](info@donatewater.ng "send us email")
- X(Twitter): [@DonateWaterNG](https://x.com/DonateWaterNG)











