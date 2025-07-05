 CodeAlpha Secure Code Review – Task 3

This project is part of the CodeAlpha Cyber Security Internship.

I reviewed a Python file with some intentional security issues and created a report explaining:
- What the issues are
- Why they are dangerous
- How to fix them
- Secure coding best practices

---

 Files in This Repo

- `vulnerable_app.py`  
  A sample Python script containing:
  - Hardcoded login credentials
  - Path traversal vulnerability
  - Command injection risk

- `secure_code_review_report.md`  
  A markdown report explaining all 3 issues clearly with solutions.

---

 Summary of Issues

1. **Hardcoded Passwords**  
   ❌ Visible login credentials in the code

2. **Path Traversal**  
   ❌ Allows accessing sensitive files using `../`

3. **Command Injection**  
   ❌ Dangerous use of `os.system()` to run system commands

---

 Recommendations

- Use hashed passwords from a secure database
- Validate and sanitize all user inputs
- Avoid dangerous functions like `os.system` and use safer alternatives

---

 Submitted To:
CodeAlpha Cyber Security Internship – Task 3: Secure Coding Review
