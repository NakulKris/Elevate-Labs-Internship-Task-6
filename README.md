# 🔐 Task 6 — Password Strength Evaluation

## 📌 Objective
Evaluate different passwords with varying complexity using an online password strength checker and analyze how complexity affects security.

---

## 🧪 Password Tests & Results

| Password Tested     | Score | Complexity  | Notes / Observations |
|-------------------|------|-------------|---------------------|
| `Qwerty123`       | 69%  | Strong      | Lacks symbols; predictable pattern but meets length & character variety |
| `helloWorld`      | 35%  | Weak        | Only letters used; easy to guess; minimal variation |
| `P@ssw0rd!2025`   | 100% | Very Strong | Good length; includes uppercase, lowercase, numbers, symbols |
| `S3cur3#Key$`     | 100% | Very Strong | High entropy; includes 4-category mix; hard to brute-force |
| `CatsAreCute`     | 44%  | Good        | No numbers/symbols; slightly improved uppercase use |

---

## 🔍 Key Observations
- Passwords **without numbers or special characters** immediately drop into *weak* territory.
- **Length + character diversity** massively boosts score and resistance against brute-force attacks.
- **Common words / predictable patterns** reduce strength even if length is adequate.
- Adding **symbols** and **mixed-case randomness** greatly increases entropy.

---

## 🛡 Best Practices Learned
✔ Minimum **12+ characters**  
✔ Mix of **uppercase, lowercase, numbers, and symbols**  
✔ Avoid **dictionary words and obvious patterns**  
✔ Use **unrelated word combinations** or **passphrases**  
✔ Keep passwords **unique for every account**

---

## 🎯 Conclusion
Strong password security directly depends on randomness, length, and complexity.  
The tests clearly show that adding numbers, symbols, and unpredictable patterns dramatically increases protection against cracking techniques.

---

## 📸 Screenshots
All evaluation screenshots are included in the repository under the `/screenshots/` folder for reference.
