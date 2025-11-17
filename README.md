# Students-Mental-Health-Analysis  
  **Language:** SQL  
  **Level:** Intermediate
  
In this project, we explore whether studying in a foreign country affects mental health outcomes for international university students.  
What you will find in this repository:  

- The database --> mental_health.csv (286 records) 
- The notebook --> mental-health.ipynb

CONTENT 
 1. Introduction
 2. Hypotheses before analyzing the data
 3. Results & Evaluation of hypotheses
 4. Key Insights
 5. Conclusion
--------------------------------------
## 1. Introduction

Does going to university in a different country affect your mental health? How is this study relevant ?  
  This analysis is relevant because mental health challenges among students(especially international students) are increasing and can significantly affect academic performance and well-being. It also provides data-driven insights that universities and support programs can use to design better resources and interventions.
  
  Here is a data description of the columns you may find helpful.


| Field Name     | Description |
|----------------|-------------|
| `inter_dom`    | Types of students (international or domestic) |
| `japanese_cate` | Japanese language proficiency |
| `english_cate`  | English language proficiency |
| `academic`     | Current academic level (undergraduate or graduate) |
| `age`          | Current age of student |
| `stay`         | Current length of stay in years |
| `todep`        | Total score of depression (PHQ-9 test) |
| `tosc`         | Total score of social connectedness (SCS test) |
| `toas`         | Total score of acculturative stress (ASISS test) |

-------------------------------------
##  2. Expectations / Hypotheses
- Hypothesis 1:  Students who have been in the country longer will show lower depression (PHQ-9) scores.
- Hypothesis 2:  Students who stay longer might report higher social connectedness, as they build relationships over time.
- Hypothesis 3:  Acculturative stress is expected to be higher during shorter stays and decrease as students adapt.
------------------------------------
##  3. Results & Evaluation of hypotheses

Hypothesis 1: Students who have been in the country longer will show lower depression (PHQ-9) scores.
| Stay Group | Avg PHQ-9 Score |
|-----------|----------------|
| Short     | 8.90           |
| Medium    | 9.10           |
| Long      | 10.13          |

**Result:** Contrary to expectations, depression scores are **highest in the Long-stay group**, suggesting that longer residence does **not necessarily reduce depressive symptoms**.

---
Hypothesis 2: Students who stay longer might report higher social connectedness.

| Stay Group | Avg Social Connectedness (tosc) |
|-----------|--------------------------------|
| Short     | 37.94                          |
| Medium    | 37.48                          |
| Long      | 35.78                          |

**Result:** Social connectedness is **slightly lower for Long-stay students**, indicating that longer stays **do not automatically lead to stronger social bonds**.

---

Hypothesis 3: Acculturative stress is expected to be higher during shorter stays and decrease over time.
| Stay Group | Avg Acculturative Stress (toas) |
|-----------|--------------------------------|
| Short     | 71.03                          |
| Medium    | 72.86                          |
| Long      | 75.44                          |

**Result:** Acculturative stress is **highest for Long-stay students**, suggesting that stress may **accumulate over time** rather than decrease.

---
## 4. Key Insights

- Longer stay does **not automatically improve mental health or social connectedness**.  
- Depression and acculturative stress may **increase over time** for some students.  
- Universities should consider **ongoing mental health support and integration programs**, not just for newcomers but also for students who have been in the host country longer.
--- 
## 5. Conclusion

The data suggetst that staing longer in the host country do not necessarily improve international students’ mental health or social connectedness. In fact, depression and acculturative stress may increase over time, highlighting the need for ongoing support and integration programs for all students, not just newcomers.
