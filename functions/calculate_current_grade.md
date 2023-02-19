# calculate_current_grade

`calculate_current_grade(hw_score, lab_score, pa_score)`

<br>

Returns current partial raw score grade as a floating-point number between 0.0 and 75.0, calculated based on the following:
- `hw_score`: score on homework assignments as floating-point number between 0.0 and 100.0, which accounts for 15% of the total course grade
- `lab-score`: score on lab assignments as floating-point number between 0.0 and 100.0, which accounts for accounts for 15% of the total course grade
- `pa_score`: score on programming assignments as floating-point number between 0.0 and 100.0, which accounts for 45% of the total course grade

## Examples

```
calculate_current_grade(89, 100, 85)
66.6
```
```
calculate_current_grade(77.5, 95, 83.75)
63.5625
```

<br>

### Find functions by...
* [Alphabetical order](https://github.com/emiliebarnard/csc110-function-reference/tree/main/functions "Go to functions folder")
* [Programming assignment](https://github.com/emiliebarnard/csc110-function-reference/blob/main/pa.md "Programming assignments in chronological order")
