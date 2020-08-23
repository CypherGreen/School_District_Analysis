# School_District_Analysis
Using Anaconda and Jupyter Notebook to analyze school performance measures.

---

## Overview of the school district analysis:

This project focused on cleaning, formatting, and analyzing school district data in order to determine how the schools performed. The district needed to know how to allocate funding to the schools based on how they had performed academically. The individual school size, type of school, and percentages of passing and failing totals were analyzed. After the final results had been presented to the school district, the 9th grade scores from Thomas High School were indicated as having cheated. The district had to be able to remove that school's results from the analysis report without affecting the other schools. The process used to reach this goal was to replace the 9th grade Thomas High School scores with NaN (Not a Number).

---

## Results:

* As we can see in the images below, when comparing the original district summary and the revised district summary we can make a few conclusions. 
1. The Average Math Score _fell_ by 0.1
2. The Percentage of Passing Math _fell_ by 1.1
3. The Percentage of Passing Reading _fell_ by 1.3
4. The Overall Passing Percentage _fell_ by 0.9

**Original District Summary:**
![Orig_Dist_Sum](https://github.com/CypherGreen/School_District_Analysis/blob/master/Report_Images/Orig_Dist_Sum.png)


**Revised District Summary:**
![Revis_Dist_Sum](https://github.com/CypherGreen/School_District_Analysis/blob/master/Report_Images/Revis_Dist_Sum.png)

---

* As the images below show, the school summary also had some changes after Thomas High School 9th graders were removed from the calculations.
Only Thomas High School was affected by the NaN scores.
1. The Percentage of Passing Math _fell_ by 26.4
2. The Percentage of Passing Reading _fell_ by 27.6
3. The Overall Passing Percentage _fell_ by 26 

**Original School Summary:**
![Orig_Sch_Sum](https://github.com/CypherGreen/School_District_Analysis/blob/master/Report_Images/Orig_Sch_Sum.png)


**Revised School Summary:**
![Revis_Sch_Sum](https://github.com/CypherGreen/School_District_Analysis/blob/master/Report_Images/Revis_Sch_Sum.png)

---

* Thomas High School used to be in the top percent of passing schools, now is at the bottom percent.

**Original Top Schools**
![Orig_Top_Schools](https://github.com/CypherGreen/School_District_Analysis/blob/master/Report_Images/Orig_Top_Schools.png)


**Revised Bottom Schools**
![Revis_Bottom_Schs](https://github.com/CypherGreen/School_District_Analysis/blob/master/Report_Images/Revis_Bottom_Schs.png)

---

* Thomas High School 9th grade was the only grade affected by the revision, so only their reading and math score percentages changed. 
* The scores by school spending range $630-644 were changed after the revision:
1. The percentage of those passing math _fell_ by 6.0 
2. The percentage of those passing reading _fell_ by 7.0 
3. The overall passing percentage _fell_ by 7.0

**Revised School Spending Summary:**
![Revis_Spending_Sum](https://github.com/CypherGreen/School_District_Analysis/blob/master/Report_Images/Revis_Spending_Sum.png)

---

* The scores by school size also changed. The medium school size range percentages for the passing math, reading, and the overall passing percentage all _fell_ by 6.0

**Revised School Size Summary**
![Revis_Sch_Size_Sum](https://github.com/CypherGreen/School_District_Analysis/blob/master/Report_Images/Revis_Sch_Size_Sum.png)

---

* The scores by school type decreased as well. Since Thomas High School is a charter school, only the charter numbers were affected.
1. The percentage of those passing math _fell_ by 4.0
2. The percentage of those passing reading _fell_ by 4.0
3. The percentage of those overall passing _fell_ by 3.0

**Revised School Type Summary**
![Revis_Sch_Type_Sum](https://github.com/CypherGreen/School_District_Analysis/blob/master/Report_Images/Revis_Sch_Type_Sum.png)

---

## Summary:

In conclusion, when NaN was used to replace the 9th grade scores from Thomas High School, the overall passing percentages did drop when analyzing parameters that had Thomas High School 9th grade in it. The charter school passing percentages dropped, the medium school size numbers dropped, and the passing percentages for reading and math dropped. Using NaN allowed us to only affect the data for Thomas High School while still keeping the total student numbers the same so the overall data analysis would still be accurate when it came to percentages.
