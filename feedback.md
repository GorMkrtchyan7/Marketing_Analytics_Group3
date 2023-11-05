# Table of Contents

1. [Milestone 1](#milestone-1--2oct-13oct)
2. [Milestone 2](#milestone-2--16oct-27oct)
3. [Milestone 3](#milestone-3--30oct-10nov)
<!-- 3. [Subsection 1.1](#subsection-1-1)
4. [Section 2](#section-2)
5. [Conclusion](#conclusion) -->

# Feedback | Group 3

## Milestone 1 | 2Oct-13Oct

1. **Define the problem:** <span style='color:red'>not done</span>
    - Please change the file format from `.txt` to `.md` , as it is not readable
    - I couldn’t understand the link between your problem and Marketing.
2. **Finalizing roles:** <span style='color:green'>done</span>
3. **Create a product roadmap and prioritize functionality (items):** <span style='color:green'>done</span> 
4. **Creating the GitHub repository included readme.md and `.gitignore` (for Python) files:**  <span style='color:green'>done</span>
5. **Create a virtual environment in the above repo and generate requirements.txt (`venv` must be ignored in git)** <span style='color:green'>done</span>
6. **Push *point 1, point 3, point 5 (requirements.txt).*** <span style='color:green'>done</span>: 
7. **Complete the first chapter of  Developing Python Packages:** <span style='color:green'>done</span>
8. **Create a private Slack channel in our Workspace and name it Group-{number}** <span style='color:green'>done</span>
9. **Schedule a call with me and Garo or come during the office hours:** <span style='color:green'>done</span>

By the end of the Milestone 2, you must complete the tasks mentioned above. Feel free to reach out if you have any questions.

Explain the Problem and the Solution


Grade 8/10 (I hope you will explain  me your project)


# Milestone 2 | 16Oct-27Oct

## Fixes From the Milestone 1

I can see that you have changed the topic into book recommendation. In the problem definition I'd like clearly see the recommendation approach. 

## Milestone 2

1. **DB developer:**
    - Design the database using Star schema (provide ERD): <span style='color:green'>done</span>
    - Insert Sample to data <span style='color:green'>done</span>
    - <span style='color:green'>the structure is wrong </span>
3. **Data Scientist:**
    - Complete data generation/acquisition/research: <span style='color:green'>done</span>
    - Select data from DB: <span style='color:green'>done</span>
    - Insert data to DB: <span style='color:green'>done</span>
4. **API developer:**
    - Select data from DB <span style='color:green'>done</span>
    - Insert data to DB <span style='color:green'>done</span>
    - Update data in DB <span style='color:red'>wrong arguments</span>
5. Finish the second chapter of Datacamp course <span style='color:green'>done</span>
6. Finalize file/folder structure: relative imports must work properly <span style='color:red'>not done</span>
    - docs folder: putting all the documents there <span style='color:red'>not done</span>
    - models folder: putting modeling-related classes, functions <span style='color:red'>not done</span>
    - api folder: api related stuff <span style='color:red'>not done</span>
    - db folder: db related stuff <span style='color:red'>not done</span>
    - initialize `__init__.py` files accordingly (see Datacamp assignment chapter 1 and chapter 2) <span style='color:red'>not done</span>
    - logger folder: I will provide this module <span style='color:green'>done</span>

*I can see multiple contributors*  


In order to improve you performance I would recommend:

- approach the datacamp course seriously (it is obvious You are just taking the hints and completing it)
- start to work on group project before the deadline

Remember you are building a package, like in the Datacamp you must have following file structure:

    | GitHubRepo
        | PackageName
            |SubPackage_1
                modlule1
                __init__.py
            |SubPackage_2
                module2.py
                __init__.py
            __init__.py
        setup.py
        example.py/ipynb (from PackageName import SomeModule)



By the end of the 3rd Milestone you must **fix folders and their relationships** 

If you manage the complete the above points by Friday(before the class) you will get **20/20** 

Grade: **10/20**


# Milestone 3 | 30Oct-10Nov


1. Complete things from *Milestone 2*
3. remove M2 M1 folders, we need to have one folder- the name of the package, and its subfolder- modules
2. Finish the **third** chapter of Datacamp course (please complete only the 3rd one)
3. **API Developer:** 
    - Create a `run.py` file for an API (find the minimum workable example [here](https://github.com/hovhannisyan91/fastapi)) 
    - Test it on swagger
    - following request types must be available to test (GET, POST, PUT), will provide more details on Friday.
4. **DB developer:**
    - complete/fix the methods from `SQLHandler()` class
    - finalize the documentation for `schema.py` by using `pyment` package
    - finalize the documentation for `SQLHandler()` by using `pyment` package
5. **Data Scientist:** start working on modeling part, by selecting the date from SQL DB
    - we just need to run sample model and store the output to sql


