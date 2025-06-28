# data-roles-aau-libraries
This repository contains data and analysis for the paper:  
**"A Study of Data-Focused Roles in Leading North American University Libraries"** published in the Journal of Academic Librarianship.

This project examines how libraries at leading members of the Association of American Universities (AAU) staff and structure their data-focused roles.

## 📁 Repository Contents
- **data/**: Contains exported CSV files of the dataset:
  - `recap.csv`: Recap dataset per university library
  - `roles`: Main dataset listing data-related roles in AAU libraries

- **notebook/**: Python analysis notebook (Google Colab), including data import from Google Sheets, text and statistical analysis, as well as figure generation.

- **figures/**: Visualizations generated from the analysis.

- **manuscript/**: Pre-print manuscript (PDF).

## 📁 Data Overview:
 Main Dataset (AAU_Library_Data_Roles.csv)
- University: Institution names
- Role: Type of role (Librarian, Staff, Other)
- Title: Specific job titles (e.g., "Data Analyst Specialist", "GIS Librarian")

Recap Dataset (AAU_Library_Recap.csv)
- University: Institution names
- Status: Public or Private
- Total: Total number of library staff
- Data Roles: Count of data-focused roles
- Categories: Number of roles categorized as Librarian, Staff, Other, and roles associated with specific keywords (data, digital, GIS, research)
- Web: Link to the library’s dedicated data services webpage (if available)

## 📊 Original Interactive Dataset
For the complete interactive dataset with embedded hyperlinks, please visit:
[[Direct Google Sheets Link Here](https://docs.google.com/spreadsheets/d/1AC_OCRf_JBEl5kcPNHK-zU_pYLIqVvdFnka9Qj9G8tM/edit?usp=sharing)]

## 🔍 How to Use
Clone the repository:
   ```bash
   git clone https://github.com/ahmadrpratama/data-roles-aau-libraries.git
