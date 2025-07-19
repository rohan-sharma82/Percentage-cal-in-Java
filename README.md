# Student Percentage Calculator 🎓

A simple Java console application that calculates student percentage based on marks obtained across multiple subjects.

## Features ✨

- Calculate percentage for any number of subjects
- Dynamic input for flexible subject count
- User-friendly console interface
- Formatted percentage output with 2 decimal places
- **Automatic grade calculation** (A+, A, B, C, D, F)
- Clear step-by-step input prompts

## How It Works 🔧

The program calculates percentage using the formula:
```
Percentage = (Total Marks Obtained / Total Possible Marks) × 100
```

Where:
- Total Possible Marks = Marks per Subject × Number of Subjects



## Code Structure 📁

```
Percentage_calculator.java
├── Input handling (Scanner)
├── Subject marks collection (Loop)
├── Percentage calculation
├── Grade determination (A+ to F)
└── Formatted output display
```

## Input Requirements 📝

- **Total marks per subject**: Integer (e.g., 100)
- **Number of subjects**: Integer (e.g., 5)
- **Individual subject marks**: Float values (e.g., 85.5)

## Sample Test Cases 🧪

| Subjects | Max Marks Each | Obtained Marks | Expected % | Grade |
|----------|---------------|----------------|------------|-------|
| 3 | 100 | 85, 78, 92 | 85.00% | A |
| 5 | 50 | 45, 48, 42, 46, 44 | 90.00% | A+ |
| 4 | 75 | 65, 70, 68, 72 | 91.33% | A+ |
| 2 | 80 | 56, 60 | 72.50% | B |

## Grading Scale 📊

| Percentage Range | Grade |
|------------------|-------|
| 90% and above | A+ |
| 80% - 89% | A |
| 70% - 79% | B |
| 60% - 69% | C |
| 50% - 59% | D |
| Below 50% | F |


## Future Enhancements 🔮

- [ ] Input validation for marks (prevent negative or excessive values)
- [ ] Save results to file
- [ ] Multiple student records management
- [ ] GUI interface
- [ ] Custom grading scale options
- [ ] Statistical analysis (class average, highest/lowest scores)
