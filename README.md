# Student GPA Calculator and Analysis

This project is a Python script that calculates and analyzes the GPA of students based on their course grades. It provides functionalities to display sorted student GPAs, calculate course-wise average grades, and display the top-performing students.

## Features

- **Calculate GPA**: Computes the GPA for each student based on their grades and course credits.
- **Display Sorted Students**: Lists all students sorted by their GPA in descending order.
- **Course Averages**: Calculates and displays the average grade point for each course.
- **Top Students**: Displays the top `n` students based on their GPA.

## Project Structure

```
.
├── sm students gpa calc and analysis.py  # Main Python script
├── 21results.pdf                         # Input data (if applicable)
├── smResults21output.pdf                 # Output data (if applicable)
```

## Usage

1. **Run the Script**:
   Execute the Python script to display the GPA analysis.

   ```bash
   python3 "sm students gpa calc and analysis.py"
   ```

2. **Functions**:
   - `display_sorted_students(student_data)`: Displays all students sorted by GPA.
   - `display_course_averages(student_data)`: Displays the average grade point for each course.
   - `display_top_students(student_data, n)`: Displays the top `n` students based on GPA.

3. **Modify Parameters**:
   - Change the value of `n` in the script to display a different number of top students.

## Example Output

### Course Averages
```
| Course Code   | Course Title                              | Credit | Avg Grade Point  |
|---------------|-------------------------------------------|--------|------------------|
| GEB 211       | Animal and Human Physiology              | 3.0    | 3.50             |
| GEB 212       | Animal and Human Physiology Lab          | 1.0    | 3.25             |
| ...           | ...                                       | ...    | ...              |
```

### Top Students
```
| Registration No. | Student's Name           | GPA   | GEB 211 | GEB 212 | GEB 213 | GEB 221 | GEB 223 | GEB 224 | GEB 225 |
|------------------|--------------------------|-------|---------|---------|---------|---------|---------|---------|---------|
| 2021431035       | MST. JANNATUL MAWA SATHI | 3.80  | 4.0     | 4.0     | 4.0     | 3.75    | 3.75    | 3.75    | 3.75    |
| ...              | ...                      | ...   | ...     | ...     | ...     | ...     | ...     | ...     | ...     |
```

## Requirements

- Python 3.x

## How It Works

1. **Student Data**: The script contains a dictionary of student data with their grades for each course.
2. **GPA Calculation**: The `calculate_gpa` function computes the GPA using course grades and credits.
3. **Sorting and Display**: Functions like `display_sorted_students` and `display_top_students` sort and display the data in a tabular format.

## Customization

- Add or modify student data in the `student_data` dictionary.
- Update course metadata (credits, titles) in the `course_metadata` dictionary.

## License

This project is for educational purposes and is not licensed for commercial use.

## Author

- **Your Name**: [S.M. Ashikur Rahman](https://www.linkedin.com/in/s-m-ashikur-rahman-1a3b03181/)

Feel free to contribute or suggest improvements!
