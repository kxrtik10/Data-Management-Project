==========================================
Project 0: Database Setup and Data Upload
==========================================

Team Members
1. Kartik Seth (ks2221)
2. Jeongtae Kim (jk2065)
3.
4.

----------------------------------------
1. Known Issues & Unfinished Functions
- Table could be formatted better

--------------------------------
2. Collaboration & References
- Consulted Rutgers iLab resources and CS336 lecture notes.
- Collaboration was mainly focused on accessing the ilab and designing the ER diagram.
- Used the SERIAL type for the ID Column which "auto-increments integers for columns"
   - https://www.geeksforgeeks.org/postgresql-serial/

-------------------------------------------
3. Data Insights & Entity Division Rules
Data Insights
- Most loans are for home purchases.
- Lower-income applicants have a higher rejection rate.
- Co-applicants may improve approval chances.
- Loan application patterns vary by region.
- Different lenders specialize in different loan types.
  
Entity Division
- LoanApplication: Core entity for loan records.
- Applicant: Stores primary applicant details.
- CoApplicant: Manages secondary applicants (if any).
- Lender: Contains lender information.
- Property: Stores loan-related real estate details.
- Decision: Tracks approval, denial, and loan outcomes.

----------------------------------------
4. Development Challenges & Time Spent
Challenges
- Creating the table where handwriting the one line containing all the tabs and seperating each tab with a comma and VARCHAR(255) was time-consuming. (1 1/2 hours)
  
Time Spent
- In creating the E.R. Diagram, it took approximately 4-5 hours as going through the data was time consuming with the addition of having to keep in mind the tabs that must fall in their respective tables.
- Creating the Table took 1 1/2 hours but figuring out the procedure of uploading the CSV file and etc, the process took 2 additonal hours.
- So all in all, the time spent on the project took 8-9 hours. 
