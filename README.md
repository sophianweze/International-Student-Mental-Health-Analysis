md
# International Student Mental Health Analysis

## Problem Statement
International students may experience varying levels of depression, social connectedness, and acculturative stress depending on how long they have stayed in the host country. This project analyzes how these mental health indicators differ by length of stay among international students.

## Dataset
Student mental health survey dataset focusing on international students.

Key variables:
- `stay` – length of stay
- `todep` – depression score (PHQ)
- `tosc` – social connectedness score (SCS)
- `toas` – acculturative stress score (AS)
- `inter_dom` – international or domestic student indicator

## Tools Used
- SQL

## Approach
- Filtered the dataset to include only international students.
- Grouped students by length of stay.
- Calculated student counts and average mental health scores using SQL aggregation functions.
- Ordered results to compare trends across different stay durations.

## Key Insights
- Most international students are concentrated in shorter stay durations (1–3 years), making trends in these groups more statistically reliable.
- Average depression (PHQ) scores tend to be higher among students with longer lengths of stay, although these groups have smaller sample sizes.
- Social connectedness generally increases with length of stay, suggesting improved integration over time.
- Acculturative stress remains high across multiple stay durations and does not show a consistent decreasing trend as length of stay increases.
- Results for longer stay durations should be interpreted cautiously due to smaller sample sizes.

## Recommendations
- Universities should provide continuous mental health support for international students, not only during their initial years, as depression levels remain elevated at longer stay durations.
- Early programs that promote social connectedness should be strengthened, as connectedness appears to improve with time.
- Since acculturative stress remains high across most stay periods, institutions should offer long-term cultural adjustment and stress management resources.
- Further analysis could explore additional factors such as academic pressure or financial stress to better understand persistent acculturative stress.

## Notes
This project focuses on exploratory analysis and descriptive trends. Findings highlight associations rather than causal relationships.

