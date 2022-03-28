# School_District_Analysis
Python 3.7.11

## Project Overview
I have been asked to do an analysis given a school distict data containing academic dishonesty. In order to conduct analysis on this data, which contains altered results for grade nine students at Thomas High School, I will replace math and reading scores with NaNs where necessary. I will then explain how this changes the results of the overall analysis. My analysis prior to replacing ninth grade scores at Thomas High School is shown in "PyCitySchools.ipynb." The analysis after replacements is shows in "PyCitySchools_Challenge.ipynb."

## Results

- The analysis of the school district shows that after replacing ninth grade Thomas High School scores with NAns, the average math score decreased while the average reading score remained the same. Passing percentages all decreased. See screenshot one for the school district summary prior to replacements. See screenshot two for the summary after replacements.
! [Screenshot One](Resources/district_summary_before_NaNs.png)
! [Screenshot Two](Resources/district_summary_after_NaNs.png)
- The school summary shows that after replacing ninth grade Thomas High School scores with NAns, the average math and reading scores did not change much. Passing percentages did not change drastically either. See the first screenshot for the school summary prior to replacements. See the second screenshot for the summary after replacements.
! [First Screenshot](Resources/school_summary_before_NaNs.png)
! [Second Screenshot](Resources/school_summary_after_NaNs.png)
- After replacing the ninth graders’ math and reading scores, Thomas High School’s performance relative to the other schools is better. Their overall passing percentage increased.
- Replacing the ninth-grade scores affects the following as such:
- Math and reading scores by grade: no results are returned for ninth grade after replacements
- Scores by school spending: spending decreased after replacements
- Scores by school size: remained the same
- Scores by school type: remained the same

## Summary
After reading and math scores were replaced, passing percentages decreased for the school district summary. Passing percentages changed for the school summary as well, but not drastically. Average reading scores for school district summaries remained the same, while math scores decreased. For the school summaries, the average math and reading scores did not change much either. Scores by school spending decreased after replacements. 
