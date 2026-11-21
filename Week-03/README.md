# Week 3: Password Cracking with JTR & Network Walks Tools

Completed as part of the Cybersecurity & Ethical Hacking internship tasks with **Network Walks**[cite: 1, 2, 18].

---

## Module 1: Password Cracking with John the Ripper (JTR)
- **Objective:** Recover the password of a password-protected PDF file (`My Locked PDF1.pdf`) using John the Ripper and Johnny GUI[cite: 2].
- **Workflow:**
  1. Installed John the Ripper and Johnny GUI, then pointed Johnny's settings to the John executable (`john.exe`)[cite: 4, 5, 6].
  2. Extracted the `$pdf$` hash from the locked PDF and saved it to a text file (`hash1.txt`)[cite: 7, 8, 9, 10].
  3. Loaded the hash file into Johnny, started a cracking attack, recovered the password, and unlocked the PDF[cite: 11, 12, 13, 14, 15].

---

## Module 2: Password Cracking with Network Walks Tools
- **Objective:** Extract a crackable PDF hash and run a dictionary attack using Network Walks' browser-based Hash Calculator and Password Cracker[cite: 18, 19, 21].
- **Workflow:**
  1. Opened the locked PDF in Network Walks' **Hash Calculator** to extract the `$pdf$` hash value[cite: 19, 20].
  2. Pasted the extracted hash into Network Walks' **Password Cracker** and ran a dictionary attack against a wordlist[cite: 21, 22].
  3. Retrieved the cracked password and used it to open and unlock the protected PDF[cite: 22, 23].

---

## Key Takeaways
- Weak, short, or common passwords can be recovered rapidly via dictionary and brute-force attacks[cite: 18, 22, 23].
- Longer passwords combining mixed character types significantly increase cracking time and complexity[cite: 23].
- Password cracking labs highlight why strong authentication and proper file protection matter in practice[cite: 2, 18].

