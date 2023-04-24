# groupings
A command line app to determine groupings for a class. 

Instructions:
1. Download the .exe and save it to a new folder on your computer.
2. Place the student list in the same folder as the .exe 
3. RUn the .exe by double clicking on the icon. Wait a few seconds for the command prompt window to pop up.
4. First, the .exe will print to screen the number of Males and Females and the Total class size. 
5. Second, the user will  be prompted to input the number of groups. (User can take the Total Class Size and do the math)
6. Third, the user will be prompted to input the desired Male/female allocation for each groupp.
7. Wait for the program to run...Take a few seconds. IN the meantime, a few statistics will be printed to screen. Finally, the "best" three .csv files are saved in a newly created output_folder
8. The metric for evaluation is SSD, sum of the squared deviation between each group mean GPA and the class meanGPA.

Details of SSD
The goal is to get the groups well matched in terms of GPA. In opeations, it means to get the groups close to the class mean GPA. A way to evaluate how close they are to the class mean GPA is to calculate the squared difference between each group mean GPA from the class mean GPA. By summing all the groups, we will get the sum of squared differences. The lower the SSD, the closer are the group GPA to the class mean GPA.

Each class of n groups, the sum of squared difference: (Group 1 mean GPA - class mean GPA) ^2 + (Group 2 mean GPA - class mean GPA)^2 ......(Group N mean GPA - class mean GPA)^2.

To test for statistical difference in GPA between groups, you can run ANOVA tests. These tests are not in the current implementation of this .exe
