# Task-2 Dynamic Table

## Description
This project generates an HTML table dynamically from a JavaScript array of objects. The table headers are created from the keys of the first object, and the rows are populated from the array’s values, eliminating the need for manually writing table tags.

## Features
- Generates table heading automatically from the keys of the first object in the data array.
- Dynamically creates rows and cells based on the array's values.
- No need of manually writing the <tr> and <td> tags again and again in order to add new data.
- If new keys are added to later objects (but not in the first one), they will create extra empty cells without corresponding headers.

## technologies Used
- HTML5-Structure of table and page
- CSS3-Styling of the layout and table
- JavaScript(Vanilla JS)-Dynamically creating table headers and rows from array data

## Folder Structure
DynamicTable
   |── DynamicTable.html **Main HTML file with javaScript and CSS**
   └── README.md **Documentation**

## How to run 
1. Clone the repository
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
2. Open the DynamicTable.html file in any Web Browser
    or
    Use Go live in VS Code to launch it
3. Table will be generated automatically from the array data in the script.

## Working
- A JavaScript array contains objects with key–value pairs.
- Keys are used to create the table header (<thead>) dynamically.
- Values are used to create table rows (<tr>) and cells (<td>).
- The table is created entirely using JavaScript DOM methods.
- No rows or cells are hardcoded in HTML.
- The table updates automatically if the array data changes.




