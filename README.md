# Healthcare-Utilisation-in-IIM
Codelists, exposure/outcome definitions and algorithms for the study titled "Healthcare utilisation of people with idiopathic inflammatory myopathies: A population-based cohort in England 2002 to 2021" by Momentum Data. 

## Quality control
All the codelists utilised for data extraction underwent the rigorous quality control process utilised by Momentum Data for multiple real world evidence studies. This process consisted of manual code list generation by a coding expert with a clinical background. The list was then independently reviewed by a second coding expert. The lists then went through an automated quality control process to identify any potential formatting errors or coding inconsistencies. During the data extraction process, high frequency codes were independently reviewed by a third reviewer to ensure that the most commonly used codes correctly match the clinical entity they are being used to identify. A fourth quality control step looks for overlap between code or case definitions where multiple definitions are possible e.g., biochemical disease markers and clinical diagnosis codes for a condition. Finally once variables were generated, the frequency and pattern of variable prevalence was compared with known data from previous analysis in other independent datasets and published literature. Any inconsistencies were reviewed and investigated as appropriate.

## Algorithms for identification

### Idiopathic Inflammatory Myopathy (IIM)
Individuals with IIM were identified and classified into IIM subtypes using a cascading approach based on recorded clinical codes from both primary and secondary care records.

Diagram illustrating the cascading case definition approach can be seen below.

![Diagram](images/IIM_cascading_case_v0.4.png)
---

For the full list of codes:
- [Dermatomyositis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/af2e2c3c940e90c606a5b6e053d883bed5dd67a2/Conditions/Idiopathic%20Inflammatory%20Myopathies/DM%20(Dermatomyositis))
- [Inclusion Body Myositis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/af2e2c3c940e90c606a5b6e053d883bed5dd67a2/Conditions/Idiopathic%20Inflammatory%20Myopathies/IBM%20(Inclusion%20Body%20Myositis))
- [Other Myositis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/af2e2c3c940e90c606a5b6e053d883bed5dd67a2/Conditions/Idiopathic%20Inflammatory%20Myopathies/Other%20Myositis)
  - [Polymyositis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/af2e2c3c940e90c606a5b6e053d883bed5dd67a2/Conditions/Idiopathic%20Inflammatory%20Myopathies/Other%20Myositis/Polymyositis)
  - [Paraneoplastic Polymyositis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/af2e2c3c940e90c606a5b6e053d883bed5dd67a2/Conditions/Idiopathic%20Inflammatory%20Myopathies/Other%20Myositis/Paraneoplastic%20Polymyositis)
  - [Myositis - Unspecified](https://github.com/MomentumData/Momentum-Data-Codelists/tree/af2e2c3c940e90c606a5b6e053d883bed5dd67a2/Conditions/Idiopathic%20Inflammatory%20Myopathies/Other%20Myositis/Myositis%20-%20Unspecified)
  - [Inflammatory Myopathy](https://github.com/MomentumData/Momentum-Data-Codelists/tree/af2e2c3c940e90c606a5b6e053d883bed5dd67a2/Conditions/Idiopathic%20Inflammatory%20Myopathies/Other%20Myositis/Inflammatory%20Myopathy)
- [IIM associated Interstitial Lung Disease](https://github.com/MomentumData/Momentum-Data-Codelists/tree/af2e2c3c940e90c606a5b6e053d883bed5dd67a2/Conditions/ILD%20(Interstitial%20Lung%20Disease)/IIM%20Associated%20ILD) [(ILD)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/af2e2c3c940e90c606a5b6e053d883bed5dd67a2/Conditions/ILD%20(Interstitial%20Lung%20Disease))

---
 
### Healthcare utilisation endpoints
#### Primary Care Consultations

This category includes primary care interactions where the consultation source is recorded as one of the following:

* `Acute visit`
* `Branch Surgery`
* `Clinic`
* `Clinic note`
* `Conversion`
* `Emergency consultation`
* `Enterprise consultation`
* `Face to face consultation`
* `GP Surgery`
* `Home Visit`
* `Home visit note`
* `Main Surgery`
* `Nursing home visit note`
* `Out of hours, Non Practice`
* `Seen in GPs surgery`
* `Seen in Health Centre`
* `Surgery Attendance`
* `Surgery consultation`
* `Telephone`
* `Telephone call to a patient`
* `Telephone Consultation`
* `Telephone encounter`
* `Treatment Room`

> **Note on Deduplication:** To avoid duplication, multiple interactions occurring within two consecutive days are collapsed and treated as a single consultation event.
