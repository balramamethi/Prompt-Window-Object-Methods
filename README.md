exam_result = window.prompt("exam_result?", "");
if(exam_result>90){
    alert("Excellent. Pass with Distinction.");
} else if(exam_result>89 && exam_result<70){
    alert("Well Done. Pass with Honours.");
} else if(exam_result>89 && exam_result<70){
    alert("Just passed.");
} else if(exam_result<55){
    alert("Failed. Do better next time.");
}
