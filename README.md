# room-6-
Classification - Student Performance Prediction
Build a system to predict if a student will be a High Achiever,
Pass, or Fail in the MI-class based on HW and exam scores
This function classifies students into "High Achiever," "Pass," or "Fail" based on their homework and exam scores, and it uses simple condition checks to determine each category.
def classify_student(homework_score, exam_score):
    # Classification logic
    if homework_score >= 85 and exam_score >= 85:
        return "High Achiever"
    elif homework_score >= 60 and exam_score >= 60:
        return "Pass"
    else:
        return "Fail"

# Test cases
print(classify_student(90, 92))  # Output: High Achiever
print(classify_student(65, 70))  # Output: Pass
print(classify_student(55, 58))  # Output: Fail
