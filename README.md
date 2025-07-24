# Muonagolu-ebubechukwu-Madonna-2024714154
Cos 102 assignment 
# Grading System Program by muonagolu ebubechukwu Madonna 
# Reg. No:2024714154

try:
    score = int(input("Enter your score (0 - 100): "))

    # Check if the score is within the acceptable range
    if 0 <= score <= 100:
        if 70 <= score <= 100:
            grade = 'A'
        elif 60 <= score <= 69:
            grade = 'B'
        elif 50 <= score <= 59:
            grade = 'C'
        elif 45 <= score <= 49:
            grade = 'D'
        elif 40 <= score <= 44:
            grade = 'E'
        else:0<= score<=39
            grade = 'F'

        print(f"YES! Your grade is: {grade}")
    else:
        print("Invalid score. Score must be between 0 and 100.")

except ValueError:
    print("Invalid input. Please enter a whole number.")