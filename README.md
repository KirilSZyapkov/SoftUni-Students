# SoftUni-Students

Write a function that stores the students that signed up for different courses at SoftUni. For each course you have to store the name, the capacity and the students that are in it. For each student store the username, the email and their credits. The input will come as an array of strings. The strings will be in some of the following formats: 
"{course name}: {capacity}" – add the course with that capacity. If the course exists, add the capacity to the existing one 
"{username}[{credits count}] with email {email} joins {course name}" – add the student if the course exists (each student can be in multiple courses) and if there are places left (count of students are less than the capacity) 

Finally, you should sort the courses by the count of students in descending. Each course should have its students sorted by credits in descending. 

Print the result in the format: 
"{course one}: {places left} places left 
--- {credits}: {username one}, {email one} 
…" 
