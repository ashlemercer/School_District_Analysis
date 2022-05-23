# School_District_Analysis

### Overview of School District Analysis
For this challenge, the district discovered that the grades of the Thomas High School 9th graders may have been tampered with, and therefore looked to us to replace their math and reading scores with NaN's. 

# Process
To do so, we found the total number of 9th graders at THS and subtracted it from the total number of students to get a new total student count. We then retrieved the new passing math and reading percentages using that number, and then repeated the rest of the steps from the original PyCitySchool exercise to get the updated information. For steps 5-14, we calculated the number of 10th-12th graders, and found their passing math/reading scores and overall passing percentage.

### Results
- **How is the district summary affected?**
  - We found that the overall district summary was only affected by about a hundredth of a decimal point, as indicated in the numbers below
  
  **Before:**

  <img width="702" alt="District Summary Before" src="https://user-images.githubusercontent.com/103979087/169727739-b19e72e0-d544-4848-988f-57c594bf7b18.png">

 
  **After:**

  <img width="706" alt="District Summary Challenge" src="https://user-images.githubusercontent.com/103979087/169727755-c321cf24-1ba4-421f-a921-c252d5bc48b2.png">


- **How is the school summary affected?**
  - The individual school summary was more dramatically affected, bringing those overall scores down to a 64.9%.
 
  **Before:**

  <img width="828" alt="Per School Before" src="https://user-images.githubusercontent.com/103979087/169728283-0fb62a20-8f49-4769-97e9-703236a74caf.png">

  **After:**

  <img width="827" alt="Per School THS" src="https://user-images.githubusercontent.com/103979087/169728457-2cbdf6e0-b2a9-40a6-812d-55e4cf95d24e.png">
 
- **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**
  - Despite the lower scores for the 9th graders, Thomas High School still remains in the top 5 performing schools in the district

  <img width="1018" alt="Top 5 Schools" src="https://user-images.githubusercontent.com/103979087/169729201-310c2dfd-607b-4e73-beae-319e9ac20cd7.png">
