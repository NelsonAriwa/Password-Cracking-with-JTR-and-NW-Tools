# Password-Cracking-with-JTR-and-NW-Tools
## Project Overview

This repository contains the final deliverable for **Week 3** of the Networkwalks Cybersecurity Internship.

Two practical modules were completed:

| Module   | Title                                      | Tools Used                                      |
|----------|--------------------------------------------|-------------------------------------------------|
| **W3-PM1** | Password Cracking with JTR               | John the Ripper (Jumbo) + Johnny GUI            |
| **W3-PM2** | Password Cracking with Networkwalks Tools | Hash Calculator + Password Cracker (browser)    |

All activities were performed only on the lab-provided locked PDF files under the authorization of the internship program.

---

## Repository Structure

```
├── README.md
├── W3-PM-FINAL_Password_Cracking_Nelson_Chinedum_Ariwa_B083.pdf
└── evidences/
    <img width="1366" height="728" alt="Window - ScreenPal - 3 25 4 (54)" src="https://github.com/user-attachments/assets/a7c8641b-505a-47a9-921d-124fb1f1f99b" />

    ├── 02_johnny_cracked_password1.jpg
    ├── 03_flag1_pdf1.jpg
    ├── 04_flag2_pdf2.jpg
    ├── 05_johnny_1qaz2wsx.jpg
    ├── 06_flag3_pdf3.jpg
    ├── 07_nw_hash_calculator.jpg
    ├── 08_nw_cracked_password1.jpg
    └── 09_nw_cracked_1qaz2wsx.jpg
```

---

## Results Summary

### John the Ripper (W3-PM1)

| PDF File              | Cracked Password | Flag Captured                                      |
|-----------------------|------------------|----------------------------------------------------|
| My-Locked-PDF1.pdf    | `password1`      | `nw{networkwalks_flag1_jtr_270521_1}`             |
| My-Locked-PDF2.pdf    | `password1`      | `nw{networkwalks_persistence_jtr_270521}`         |
| My-Locked-PDF3.pdf    | `1qaz2wsx`       | `nw{networkwalks_flag_260821_1}`                  |

### Networkwalks Tools (W3-PM2)

| PDF File              | Cracked Password |
|-----------------------|------------------|
| My-Locked-PDF1.pdf | `password1'      |
| My- Locked-PDF2.pdf | 'password1'     |
| My- Locked-PDF3.pdf | `1qaz2wsx`      |

---

## Key Takeaways

- Weak / common passwords are cracked extremely quickly with dictionary attacks.
- Both offline (John the Ripper) and online (Networkwalks) toolchains recovered the same passwords.
- Strong, unique passwords remain the most effective defense against this type of attack.

---

## Disclaimer

All activities documented in this report were performed strictly within the authorized scope of the Networkwalks Cybersecurity Internship (Batch B083).  

These materials are for **educational and research purposes only**.  
Unauthorized password cracking against systems or files you do not own is illegal.

---

**Author:** Nelson Chinedum Ariwa
**Batch:** B083 
**Institution:* Networkwalks.com
