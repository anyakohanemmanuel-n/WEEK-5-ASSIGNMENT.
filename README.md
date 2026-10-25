# WEEK-5-ASSIGNMENT.
question1.js,


const firstName = "Emmanuel";
const lastName = "Anyakoha";
const subject1Score = 45;
const subject2Score = 38;
const subject3Score = 30;

const totalScore = subject1Score + subject2Score + subject3Score;

let remark;
if (totalScore >= 70) {
  remark = "Excellent";
} else if (totalScore >= 50 && totalScore <= 69) {
  remark = "Good";
} else if (totalScore >= 35 && totalScore <= 49) {
  remark = "You can do better";
} else {
  remark = "Fail";
}

const fullName = firstName + " " + lastName;

console.log("===== EXAMINATION RESULT =====");
console.log("Student Name : " + fullName);
console.log("Subject 1    : " + subject1Score);
console.log("Subject 2    : " + subject2Score);
console.log("Subject 3    : " + subject3Score);
console.log("Total Score  : " + totalScore);
console.log("Remark       : " + remark);
console.log("==============================");
