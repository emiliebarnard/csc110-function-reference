# calculate_exam_score

`calculate_exam_score(current_grade, target_grade)`

<br>

Returns single score required to earn across both midterm and final exams as a floating-point number to achieve `target_grade`.  
Returned value is calculated based on `current_grade` which accounts for 75% of `target_grade`. Returned value accounts for 25% of `target_grade`.

## Examples

```
calculate_exam_score(66.6, 90)
93.60000000000002
```
```
calculate_exam_score(63.5625, 80)
65.75
```
