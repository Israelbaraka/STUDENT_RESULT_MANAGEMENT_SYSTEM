NAMES:  BARAKA MURHIMA ISRAEL – BTCES/2023/63733
        MUKABE MASAMBA LUMIERE – BTCES/2023/66461
        ISRAEL MWANGA   -    BTCES/2023/51566
        MERCY CHEGE  -  BTCES/2021/96303
        
BIT2120 – COMPUTER PROGRAMMING II
PROJECT TITLE: STUDENTS GRADING SYSTEM / STUDENTS RESULT MANAGEMENT SYSTEM 

Link: https://github.com/Israelbaraka/STUDENT_RESULT_MANAGEMENT_SYSTEM.git

Screenshots of the features of the applications:

 
  


   

 

Features:

1.	Login System
2.	Admin Panel
3.	Create/Manage Classes
4.	Create/Manage Subjects
5.	Add/Manage Students
6.	Declare Results (Grades)


FLOAT CHART :
Start
|
|--- session_start()
|--- error_reporting(0)
|--- include('includes/config.php')
|--- Check if length of $_SESSION['alogin'] is empty
|    |
|    |--- True: Redirect to "index.php"
|    |
|    |--- False:
|         |
|         |--- Start HTML output
|         |    |
|         |    |--- Include 'includes/topbar.php'
|         |    |--- Start 'main-wrapper'
|         |         |
|         |         |--- Include 'includes/leftbar.php'
|         |         |
|         |         |--- Start 'main-page'
|         |               |
|         |               |--- Display 'Dashboard' title
|         |               |
|         |               |--- Display dashboard statistics:
|         |               |    |
|         |               |    |--- Query and display total registered students
|         |               |    |
|         |               |    |--- Query and display total subjects listed
|         |               |    |
|         |               |    |--- Query and display total classes listed
|         |               |    |
|         |               |    |--- Query and display total results declared
|         |               |
|         |               |--- Include necessary CSS and JS files
|         |
|         |--- End HTML output
|
|--- End
