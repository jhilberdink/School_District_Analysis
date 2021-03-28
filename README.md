# School_District_Analysis
## Overview of the School District Analysis
After conducting an initial analysis of school district statistics, evidence was discovered that math and reading scores for ninth-grade students at Thomas High School (THS) had been altered. These ninth-grade scores were dropped and district statistics were recalculated using only tenth through twelfth-grade scores for THS. Below is a summary analysis of the results. For the code used to complete this analysis, see [PyCitySchools](/PyCitySchools_Challenge)
## Results
Dropping ninth-grade THS scores had the following effects on the full school district results:
- The initial district summary showed that 75% of students were passing math, 86% passing reading, and 65% were passing both math and reading
![district initial](https://user-images.githubusercontent.com/79542537/112764928-b0644000-8fd8-11eb-9525-fc5f107bdca1.png)
Math, reading, and overall scores all showed slight declines after excluding ninth-grade THS results from the district summary statistics.
![updated_district](https://user-images.githubusercontent.com/79542537/112762271-c7049a00-8fcc-11eb-9066-93f9504180b6.png)
- The summary of individual schools also shows a slight decrease in scores for THS. The school's percentage of students passing both math and reading declined from 90.94% to 90.63%. Compare the following results from the initial analysis with the revised analysis excluding THS ninth graders.
![THS_initial_summary](https://user-images.githubusercontent.com/79542537/112762565-42b31680-8fce-11eb-9930-78ab6f39068a.png)
![THSupdated](https://user-images.githubusercontent.com/79542537/112762566-447cda00-8fce-11eb-9194-6b95e32e65ed.png)
- While Thomas High School's test scores declined slightly in the revised analysis, it remians a high-performing school. It retains its spot as the second highest school in the percentage of students passing both math and reading.
![image](https://user-images.githubusercontent.com/79542537/112762640-bd7c3180-8fce-11eb-81bd-cc6d9cef9115.png)
- Dropping Thomas High School ninth-grade scores has the following results on district statistics:
  - THS was tied with Pena High School for the highest ninth-grade math and reading scores before excluding its results. Without the scores from THS, the district will show slightly poorer test results from the ninth grade, but other grade levels will remain unaffected. Compare the initial results for math scores by grade with the updated results:
![results by grade initial](https://user-images.githubusercontent.com/79542537/112765616-f1118880-8fdb-11eb-88e7-9b7ce85401ca.png)![revised grades](https://user-images.githubusercontent.com/79542537/112765622-fb338700-8fdb-11eb-844b-253232f1423c.png)
  - Dropping THS ninth-grade scores led to a slight decrease in test scores for schools spending between $630 and $644 per student.
![initial size](https://user-images.githubusercontent.com/79542537/112765864-3a160c80-8fdd-11eb-99d4-32bd244076a8.png)
![revised size](https://user-images.githubusercontent.com/79542537/112765868-3d10fd00-8fdd-11eb-9b75-7d197e4cbba6.png)
  - Test results for medium-sized schools also showed a slight decline after dropping THS ninth_grades scores.
![initial spending](https://user-images.githubusercontent.com/79542537/112765879-4b5f1900-8fdd-11eb-86e0-8d8f31e33509.png)
![revised spending](https://user-images.githubusercontent.com/79542537/112765881-4d28dc80-8fdd-11eb-9379-89692f3ac95f.png)
  - Finally, removing THS ninth_grades scores led to a small decrease in the average test scores for charter schools.
![types](https://user-images.githubusercontent.com/79542537/112766278-fe7c4200-8fde-11eb-9bc0-e312a756fd33.png)
![revised types](https://user-images.githubusercontent.com/79542537/112766195-a0e7f580-8fde-11eb-91a8-0c4fde5e2332.png)
## Summary
After updating the school district analysis, 
