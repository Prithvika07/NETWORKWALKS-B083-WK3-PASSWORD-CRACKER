# NETWORKWALKS-B083-WK3-PASSWORD-CRACKER
Week 3 Project at Networkwalks – PDF password auditing using JTR, Johnny, and Networkwalks tools.

# PDF Password Auditing

## About

This project is part of my cybersecurity training.

The project involved recovering passwords from three
password-protected PDF files using different tools.

## Files and Tools

| PDF | Tool Used |
|---|---|
| My Locked PDF1.pdf | John the Ripper + Johnny |
| PDF 2 | Networkwalks Tool |
| PDF 3 | Networkwalks Tool |

## Task 1 - John the Ripper and Johnny

For the first PDF, I used John the Ripper (JTR) and
Johnny GUI.

### Steps

1. Installed John the Ripper on Windows.
2. Installed Johnny GUI.
3. Configured Johnny with the `john.exe` file.
4. Extracted the password hash from the PDF.
5. Saved the hash in a text file.
6. Opened the hash file in Johnny.
7. Started a new attack.
8. Checked the result.
9. Used the recovered password to open the PDF.

### Result

The password audit was completed successfully.

The result showed:

`100% (1/1: 1 cracked, 0 left)`

This confirmed that the password was successfully recovered.

### Screenshots

![Johnny Settings](JTR/johnny-settings.png)

![Hash File](JTR/hash-file.png)

![Attack Result](JTR/attack-result.png)

![PDF Opened](JTR/pdf-opened.png)


## Task 2 - Networkwalks Tool

For the second PDF, I used the Networkwalks tool provided
as part of the training.

The PDF was processed using the tool and the password
was successfully recovered.

### Result

The recovered password was tested with the PDF to verify
that it could be opened successfully.

### Screenshot

![Networkwalks Result](Networkwalks-Tool/file2-result.png)


## Task 3 - Networkwalks Tool

For the third PDF, I again used the Networkwalks tool
provided as part of the training.

The password was recovered and verified by opening the
protected PDF.

### Result

The password recovery was successful.

### Screenshot

![Networkwalks Result](Networkwalks-Tool/file3-result.png)


## What I Learned

- Basic password auditing concepts
- How John the Ripper works
- How Johnny provides a graphical interface for JTR
- How password hashes are used during password auditing
- How different tools can be used for password recovery
- How to verify a recovered password

## Conclusion

This project helped me understand the basic process of
password auditing and password recovery.

All testing was performed as part of my cybersecurity
training using the provided PDF files and tools.
