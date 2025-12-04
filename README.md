# ECE-2310-Group-Project
Repository containing all code and UMLs for the project

## Objectives:
- Create pseudo code (accurate enough to program in any language).
- Read from a .csv file.
- Write to a .csv file.
- Create seven files that include the timestamp, device, and specified data.
- Organize data into sublevels.
- Alter data using a "Hub" (Convert Fahrenheit to Celsius).
- Handle multiple files.

## Explanations:

- **DataRecord** is an instance of all the data at one time stamp, so like humidity, light, etc. (One row of data).
- **DataRead** is an instance of ALL  **DataRecord**s from a single file (using a vector).
- **DataStorage** is an instance of ALL **DataRead**s (using a vector). This allows the system to handle multiple files if needed. **DataRead**s is essentially an entire file. 
- The **Hub** then uses the **DataStorage** to access each DataRead and each **DataRecord**. 
- **DataStorage**, **DataRead**, and **DataRecord** all have member functions to access their private data, which means they can access each piece of information. This allows the **Hub** to handle any piece of data and process it.
- **DataWrite** is the class that handles taking the **DataRead** objects from the **Hub** and writing them to a file.

Note: The filename can be altered to the directory or filepath of the file.

## UML Diagram

### Initial Design
<img width="4950" height="4475" alt="image" src="https://github.com/user-attachments/assets/86009265-8351-4171-b995-b80cae7addbc" />

### Final Design
<img width="4950" height="4505" alt="image" src="https://github.com/user-attachments/assets/9546608a-c458-45ff-ba0b-950b0f957341" />

##$ [Pseudo Code](https://github.com/mjlt42/ECE-2310-Group-Project/blob/main/Pseudo%20Code%20ECE%202310%20Group%20Project%20Part%202.pdf)


## Collaborators
- Matthew Lopez Tarsky 👑
- Donna La (:
- Ethan Wong
- Eric Reynosa
