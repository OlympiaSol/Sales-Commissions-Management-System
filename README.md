# Sales-Commissions-Management-System
This project involves reengineering a legacy Java application to manage sales and commissions for a clothing company. It processes sales data, calculates commissions for sales representatives, and generates reports. The focus is on refining the application's architecture, enhancing code quality, and extending functionality.
### Detailed Project Reengineering Overview

The project is centered around the comprehensive reengineering of a Java application designed for managing sales and commissions within a small clothing company. This application, which currently processes input in txt or XML formats containing sales receipt information, requires significant enhancements to improve its functionality, maintainability, and performance. The refactoring tasks outlined in the document are structured to address various issues and introduce new capabilities as follows:

#### Refactoring Tasks:
- **Data Package Improvements:**
  - Removal of "lazy classes" such as Coat, Shirt, Skirt, and Trouser classes that contribute minimally to the application's functionality.
  - Renaming the Agent class to more accurately reflect its role, along with the elimination of duplicate code and replacement of deprecated Java Vector data structures to modern alternatives.

- **File Handling Enhancements:**
  - Introduction of clearer class names and package organization for FileAppender, FileAppenderTXT, and FileAppenderXML classes to enhance clarity and maintainability.
  - Application of the Template Method pattern to standardize file updating algorithms across different file types.

- **Input and Output Package Refactoring:**
  - Simplification of txt file parsing algorithms in the TXTInput class and harmonization of parsing algorithms across TXTInput and XMLInput classes through the Template Method pattern.
  - Improvement of class names and implementation of common algorithms for saving report files in txt and XML formats, ensuring consistency and reducing redundancy.

- **GUI Package Overhaul:**
  - Enhancement of GUI functionality to allow users to select specific files for report saving, moving away from predefined filenames.
  - Improvement of class names and refactoring within the GUI package to streamline user interactions and simplify complex code structures.

#### Extension Tasks:
- **HTML Input and Output Handling:**
  - Expansion of the application's capabilities to include processing input from HTML files, utilizing appropriate HTML tags to structure the information.
  - Implementation of functionality to generate and store sales representative reports in HTML format, ensuring the data is organized and accessible.

#### Deliverables Preparation:
The project's culmination involves preparing a comprehensive report and other deliverables to document the refactoring efforts, enhancements, and testing procedures. This documentation is crucial for ensuring clarity and transparency regarding the changes made and the methodologies applied throughout the project's lifecycle.

