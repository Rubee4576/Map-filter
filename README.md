# Student Records - Task 16: Map & Filter

## Objective
Create a web page that displays student records using HTML and JavaScript and allows users to search students by name.

## Files
- `index.html` - Complete HTML, CSS and JavaScript solution.

## Features
1. Student data is stored in an array of objects.
2. Every object contains:
   - Name
   - Marks
   - Class
   - Address
3. JavaScript `map()` is used to generate student cards dynamically.
4. JavaScript `filter()` is used to search students by name.
5. Search works in real time while typing.
6. The Search button also performs the search.
7. A "No student found" message is displayed when there is no match.
8. The layout is responsive for mobile, tablet and desktop screens.

## How to Run
1. Open `index.html` in a browser.
2. Type a student name in the search box.
3. The cards will update automatically.

## Important JavaScript Concepts
### map()
`map()` converts each student object into an HTML card.

### filter()
`filter()` creates a new array containing only students whose names match the search text.

Example:
```javascript
const filteredStudents = students.filter(student =>
    student.name.toLowerCase().includes(searchText)
);
```
