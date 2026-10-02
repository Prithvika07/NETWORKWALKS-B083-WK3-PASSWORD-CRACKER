# NETWORKWALKS-B083-WK3-PASSWORD-CRACKER
Week 3 Project at Networkwalks – PDF password auditing using JTR, Johnny, and Networkwalks tools.

# PDF Password Auditing

## Week 3 Project - Networkwalks

This project was completed as part of my Week 3 cybersecurity
project at **Networkwalks**.

The project focused on password auditing and password recovery
using different tools.

## Company

**Networkwalks**

## Tools Used

- John the Ripper (JTR)
- Johnny
- Password Cracker - Networkwalks
- Hash Calculator - Networkwalks

## Project Tasks

Three password-protected PDF files were tested using the tools
provided for the project.

| PDF | Tool Used |
|---|---|
| PDF 1 | John the Ripper + Johnny |
| PDF 2 | Password Cracker |
| PDF 3 | Hash Calculator |


# Task 1 - John the Ripper and Johnny

For the first PDF, I used **John the Ripper (JTR)** with
the **Johnny GUI**.

## Steps

1. Installed John the Ripper on Windows.
2. Installed Johnny.
3. Configured Johnny with the `john.exe` file.
4. Extracted the password hash from the PDF.
5. Saved the hash in a text file.
6. Opened the hash file in Johnny.
7. Started a new attack.
8. Checked the result.
9. Used the recovered password to open the PDF.

## Result

The password was successfully recovered.

The result showed:

`100% (1/1: 1 cracked, 0 left)`

This confirmed that the password was successfully recovered.

## Screenshots

### Johnny Settings

![Johnny Settings](JTR-Johnny/johnny-settings.png)

### Hash File

![Hash File](JTR-Johnny/hash-file.png)

### Attack Result

![Attack Result](JTR-Johnny/attack-result.png)

### PDF Opened

![PDF Opened](JTR-Johnny/pdf-opened.png)


# Task 2 - Password Cracker

For the second PDF, I used the **Password Cracker** tool
provided by **Networkwalks**.

The password-protected PDF was processed using the tool and
the result was checked.

## Result

The password was successfully recovered and verified with
the PDF.

## Screenshot

![Password Cracker Result](Password-Cracker/password-cracker-result.png)


# Task 3 - Hash Calculator

For the third PDF, I used the **Hash Calculator** tool
provided by **Networkwalks**.

The PDF was processed using the tool and the generated
hash information was checked as part of the password
auditing task.

## Result

The required hash information was successfully generated
using the tool.

## Screenshot

![Hash Calculator Result](Hash-Calculator/hash-calculator-result.png)


# What I Learned

- Basic password auditing concepts
- How John the Ripper works
- How Johnny provides a graphical interface for JTR
- How password hashes are used in password auditing
- How to use the Password Cracker tool
- How to use the Hash Calculator tool
- How to verify password recovery results


# Conclusion

This project helped me understand the basic process of
password auditing and the use of different cybersecurity
tools.

I also learned how different tools can be used to work
with password-protected files and password-related hash
information.

This project was completed as part of my Week 3 cybersecurity
training at **Networkwalks**.
