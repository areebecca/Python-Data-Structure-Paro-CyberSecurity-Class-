# PYTHON DATA STRUCTURE 
## Objective
The primary goal of this lab was to explore and demonstrate the fundamental built-in data structures in Python. Specifically, the lab focused on understanding the properties of Lists, Tuples, and Dictionaries, including how to create, modify, and analyze them using various built-in methods
## Tools Used
Language: Python 3
Environment: Google Colab
Libraries: pandas (for DataFrame conversion)
## Step_by_ Step Process
List Operations: Defined mutable collections and practiced element manipulation using addition, removal, and reordering methods.
Tuple Exploration: Created immutable sequences to understand the difference between fixed and changeable data.
Dictionary Construction: Built key-value pair collections using multiple initialization methods (standard curly braces and the dict() function).
Data Transformation: Updated dictionary content with new keys and converted the final structured data into a tabular format using a DataFrame.
## Commnands  Excuted
### 1. List Manipulations
Creation: x = [1, 2, 3, 4]
Adding Elements: x.append(5), x.extend(['a', 'b']), and x.insert(0, 0)
Removing Elements: x.remove(0) and x.pop(-1)
Searching & Organizing: z.count('c'), z.sort(), and z.reverse()
### 2. Tuple Operations
Creation: data_team = {'names': [...], 'Age': [...], 'Position': [...]}
Retrieval: data_team.keys(), data_team.values(), and data_team.items()
Update: data_team.update({'Gender': [...], 'Duty Station': [...]})
Tabulation: df = pd.DataFrame(data_team)
## Screenshots of Results
<img width="1844" height="893" alt="Screenshot 2026-02-20 144016" src="https://github.com/user-attachments/assets/af2ef7d2-910b-482f-80b0-2189833b56a6" />
<img width="1792" height="774" alt="Screenshot 2026-02-20 135328" src="https://github.com/user-attachments/assets/be9ba86e-2712-48b1-b407-5dbd050c5067" />
<img width="1785" height="800" alt="Screenshot 2026-02-20 135344" src="https://github.com/user-attachments/assets/96faf15e-3cb5-4ce8-adc0-578219cb86e8" />
<img width="1771" height="593" alt="Screenshot 2026-02-20 135356" src="https://github.com/user-attachments/assets/7a3266f6-ec34-479f-991a-865cf8ffc168" />
<img width="1760" height="602" alt="Screenshot 2026-02-20 135416" src="https://github.com/user-attachments/assets/e52c94c5-b050-4dbd-8d97-0cd62e639017" />
<img width="1784" height="561" alt="Screenshot 2026-02-20 135429" src="https://github.com/user-attachments/assets/6657bb43-7e5c-4956-a3ec-98fe85209f07" />

## Key Observations/ Lessons Learned
Mutability: Lists and Dictionaries are mutable (can be changed), while Tuples are immutable, making them safer for data that should not be modified.
Indexing: Python uses zero-based indexing. Using .index() is an efficient way to locate the position of a specific element.
Data Integrity: The count() method is vital for checking the frequency of occurrences in both Lists and Tuples.
Scalability: Converting a Dictionary into a pandas DataFrame is a powerful step for transitioning from raw data storage to professional data analysis and reporting.
# LINK TO THE NOTE BOOK
https://colab.research.google.com/drive/1tDJeMKb7pwxInePIRXLsNeH8PRM6IVyH?usp=sharing


