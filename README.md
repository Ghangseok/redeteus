var score : UInt = 0

var grade : String = ""

score = 59

print ("Your score is " + String(score))

if score >= 80 && score <= 100 {

    grade = "A"

} else if score >= 70 && score < 80 {

    grade = "B"
    
} else if score >= 60 && score < 70 {

    grade = "C"
    
} else if score >= 50 && score < 60 {

    grade = "D"
    
} else if score >= 0 && score < 50 {

    grade = "F"
}
print ("Your grade is " + grade)

if grade >= "A" && grade <= "D" {

    print("Pass")
    
} else {

    print("Failure")
    
}
