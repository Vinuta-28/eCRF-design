# eCRF-design
This repository features an eCRF design for a hypothetical 12-week study (totaling up to 18 weeks including Screening, Lead-in, Treatment, and Follow-up periods) of DS-8500a in Type 2 Diabetes Mellitus subjects on Metformin. The accompanying CSV file serves as a transparent data dictionary, outlining all fields, their attributes, and the robust validation mechanisms integrated for superior data integrity.

Key design features include:

Precise Data Type Validation: Guaranteeing inputs conform to expected formats, such as numerical values for age and blood glucose.

Bounded Range Validation: Limiting numerical entries to clinically appropriate ranges, for instance, body temperature between 35.0 and 42.0 degrees Celsius.

Intelligent Cross-Field Validation: Employing logic to ensure consistency and relevance, such as displaying pregnancy-related questions only when the subject's gender is female.
To prevent missing critical information, essential fields (e.g., 'Subject Consent Signed', 'Type of Glucose Measurement') are marked as 'Required,' preventing form completion until these data points are supplied. A variety of field types—from text boxes to dropdowns and radio buttons—have been thoughtfully implemented to streamline data entry and minimize discrepancies."
