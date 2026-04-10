This project presents an interactive Power BI dashboard to analyze student performance, attendance, and behavior.
It helps in identifying trends, monitoring performance, and gaining insights at both overall and individual levels.

**Data Preparation**
Cleaned column names and corrected data types.
Handled missing values (e.g., Reason → "Not Mentioned").
Established relationships using StudentID.
Followed Star Schema for efficient data modeling.

**Data Modeling**
Students table used as central dimension
Connected with:
  Scores
  Attendance
  Behavior
  Relationships: One-to-Many (1:*)

**DAX Measures Created**
Total Students
Average Score %
Attendance %
Behavior Count
Performance Category (High / Medium / Low)

**1. Main Dashboard**
KPI Cards: Total Students, Average Attendance, Average Score
Behavior Distribution (Donut Chart)
Attendance Gauge
Student Score Table (with conditional formatting)
Average Score Trend (Line Chart)
Filters: Class, Term, Subject


**2. Detailed Analysis Page**
Student-wise marks (Final, Mid, Unit Test)
Score KPI Card
Section-wise performance (Pie Chart)
Subject-wise comparison (Bar Chart)

**3. Class-wise Insights**
Total Students by Class
Average Score by Class
Subject-wise performance trends


**4. Term Analysis**
Average Score by Term
Visual comparison of performance across terms


**Interactivity Features**
Slicers for dynamic filtering (Class, Subject, Term)
Drillthrough functionality for student-level analysis
Tooltips for additional insights


