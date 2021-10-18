# module4
Pandas and Jupyter Notebook

# School District Analysis for Budgeting Purposes

## Overview
Chief data scientist, Maria, works at a city school district and is responsible for preparing the analysis, reporting and presentation of all standardized test data.  The test data to be analyzed is for the subjects of math and reading. The analysis will be used to highlight trends and patterns for 15 schools within the district.

The task is to assist Maria with analyzing student funding and student's standardized test scores. The school board and superintendent will utilize the analyses to make informed decisions regarding budgeting.  The privacy of student records is of the utmost importance and confidentiality is a priority.

After the analysis was completed, the school board notified Maria and her supervisor that the student data file shows a potential for academic dishonesty in relation to Thomas High School's 9th grade class. Without knowing the full extent of the grade alterations, the school board would still like to move forward with the analysis. NaN's (not a number) were entered for the 9th grade class at Thomas High School so the data could be re-analyzed.

## Results

* How is the district summary affected?

It doesn't appear that the NaN's entered for the 9th grade class' math and reading scores at Thomas High School had any effect on the overall data for the school. I am of the opinion that the data presented in 9th grade (despite the potential alteration) was on par with the 10th, 11th and 12th grade data and nothing was skewed from the initial analysis to the final analysis.

![district_vs_charter_results](https://user-images.githubusercontent.com/90632470/137649604-ca208c26-838d-4562-b727-547386a61f7a.PNG)

* How is the school summary affected?

It doesn't appear that the NaN's entered for the 9th grade class' math and reading scores at Thomas High School had any effect on the overall data for the school. I am of the opinion that the data presented in 9th grade (despite the potential alteration) was on par with the 10th, 11th and 12th grade data and nothing was skewed from the initial analysis to the final analysis.

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

It doesn't appear that the NaN's entered for the 9th grade class' math and reading scores at Thomas High School had any effect on the overall data for the school. I am of the opinion that the data presented in 9th grade (despite the potential alteration) was on par with the 10th, 11th and 12th grade data and nothing was skewed from the initial analysis to the final analysis.

* How does replacing the ninth-grade scores affect the following:

	** Math and reading scores by grade:
		It appears that there was no real effect to the data with regard to math and reading scores by grade. The results remained the same as the initial analysis after the NaN's were entered for the 9th grade scores at Thomas High School.

	** Scores by school spending:
		It appears that there was no real effect to the data with regard to scores by school spending. The results remained the same as the initial analysis after the NaN's were entered for the 9th grade scores at Thomas High School.
		It is also noted that there doesn't appear to be a correlation between high (or low) spending ranges per student and high (or low) passing scores by school.

	** Scores by school size:
		It appears that there was no real effect to the data with regard to scores by school size. The results remained the same as the initial analysis after the NaN's were entered for the 9th grade scores at Thomas High School.
		It is also noted that there does appear to be a trend between the larger schools seeing lower overall passing scores. It may be worth investigating further to better determine if smaller schools yield higher scores.

	** Scores by school type:
		It appears that there was no real effect to the data with regard to scores by school type. The results remained the same as the initial analysis after the NaN's were entered for the 9th grade scores at Thomas High School.
		It is also noted that there appears to be a correlation between the school type and the passing scores. It seems that those noted as District tended to see higher reading percentages and lower math percentages in comparison. Those noted as Charter tended to see higher passing math percentages and lower passing reading percentages.

![school_results_part1](https://user-images.githubusercontent.com/90632470/137649619-8020f4fa-07dd-4345-9dad-767b0c02ed09.PNG)
![school_results_part2](https://user-images.githubusercontent.com/90632470/137649626-fda499e1-8933-412e-8280-2f8683ea09fa.PNG)

## Summary
Despite seeing no real changes to the overall data once the NaN's were input, there were still small changes at the more granular level noted:

1. The student data was noted to have changed when the NaN's were edited. These edits were verified to ensure the current data being analyzed was updated.

![specific_NaN_instance](https://user-images.githubusercontent.com/90632470/137649632-fe514329-3c8e-4f4d-8870-466d0f467ed3.PNG)

2. There were 39,170 students total.  Once the NaN's were entered, the total students dropped to 38,709.

![total_students](https://user-images.githubusercontent.com/90632470/137649643-e72ffc29-ad41-4dbb-9076-397ece4d742e.PNG)

3. The Thomas High School average math scores changed from 83.418349 in the original analysis to 83.350937 after the edits were made.

4. The Thomas High School average reading scores changed from 83.848930 in the original analysis to 83.896082 after the edits were made.

To recap, I am of the opinion that the data was either 1) not tampered with or 2) that the data reflected in the 9th grade Thomas High School grades was consistent with those seen in the 10th, 11th and 12th grade data. Either of these could be reasons why there was an unnoticeable change in the analysis when the NaN's were entered.
