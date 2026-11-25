# John_the_ripper

# Overview
This project involved using John the Ripper (JtR), a password-cracking tool, to understand how password hashes can be analysed and how weak passwords can be exposed. I carried out the exercise in a windows environment to gain practical experience with password hash analysis and understand the importance of strong password practices.
# Objectives
- To understand the basics of password hashing and password security.
- To learn how to use John the Ripper for password hash analysis.
- To perform a practical password-cracking exercise in a controlled environment.
- To learn the importance of creating strong and secure passwords.
# Tools and technology
- windows operating system
- john the ripper
- jonny
- online hashcrack
# Methodology and steps

# Step 1
I downloaded and installed john the ripper, also downloaded johnny which is the GUI for john the ripper and then configured it by adding the john the ripper file to johnny.
<img width="1366" height="718" alt="Screenshot 1" src="https://github.com/user-attachments/assets/0327f9f4-8ce7-4be7-9abb-c9e64ebac60a" />
# Step 2
I extracted the hash of the encrypted pdf using the online hashcrack website, then saved them in a text file using notepad on windows.
<img width="1359" height="651" alt="Screenshot 2 (2)" src="https://github.com/user-attachments/assets/e8240c0d-f5f1-450e-a417-e6ef1a975f7e" />
<img width="301" height="123" alt="Screenshot 3" src="https://github.com/user-attachments/assets/2c145563-3166-47c9-ac02-3beb3aa5d2d3" />

# Step 3
I uploaded the text file which contains the hash of the encrypted file in johnny and then "started new attack" to display the password of the encrypted file.
<img width="1366" height="716" alt="Screenshot 4" src="https://github.com/user-attachments/assets/71e7fce1-f986-49c4-b555-d13102558e8c" />
# Step 4
I tried to open the encrypted pdf, it then requested for password, then i inputed the generated password by john the ripper. the pdf then opened and i gained access.
<img width="1362" height="673" alt="Screenshot 5" src="https://github.com/user-attachments/assets/c318a707-ac1b-4953-a06e-8a4bcdc3e67d" />
<img width="1357" height="681" alt="Screenshot 6" src="https://github.com/user-attachments/assets/64283f64-9691-4ecc-8921-d393b808e716" />
# Result/finding
The exercise provided practical experience in using John the Ripper to analyse a password hash. I observed how the tool processes hash information and displays its results. This helped me understand the practical application of password hash analysis.
# Lesson learned
I learned how to use John the Ripper for password hash analysis and gained a better understanding of how password hashes are processed. The exercise also improved my familiarity with using cybersecurity tools through the Kali Linux terminal and highlighted the importance of password security.
# conclusion
This practical exercise improved my understanding of password hash analysis and gave me hands-on experience using John the Ripper. It also strengthened my knowledge of password security and the use of command-line cybersecurity tools.
# Disclaimer
This exercise was carried out for educational purposes in a controlled lab environment using an authorised sample password hash.





