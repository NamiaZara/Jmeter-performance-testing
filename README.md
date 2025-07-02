
# JMeter Performance Test – Booking API

## ✅ What I Have Done

- Created a JMeter script (`booking.jmx`) to test the Booking API.
- Performed **Load Test** and **Stress Test**.
- Collected results in `booking-api-test-report.xlsx`.
- Generated an HTML report from JMeter.
- Took screenshots of key statistics and test summaries.

---

## 🛠 Prerequisites

- [JMeter](https://jmeter.apache.org/) installed (version 5.4 or above recommended).
- Java installed and configured in system path.
- Git installed (for uploading to GitHub).

---

## 🚀 How to Run the Test

1. Open JMeter.
2. Load the `booking.jmx` file.
3. Set thread properties according to your need.
4. Run the test (green play button).
5. To generate HTML Report:
   - Right-click on the Test Plan > Add > Listener > Summary Report.
   - Save result to `dmoney.jtl`.
   - Use `JMeter > Tools > Generate Report Dashboard` to create HTML report:
     ```bash
     jmeter -g dmoney.jtl -o Reports
     ```

---

## 📸 Screenshots
### ✅ Request Summary
## Load
![image](https://github.com/user-attachments/assets/afaf88e1-0f39-4ee7-a275-3b01e8ed25a7)

## Stresss
![image](https://github.com/user-attachments/assets/ea9818b3-21c6-4e80-9641-48273b1c3ffe)

### 📈 Load Test Report
![image](https://github.com/user-attachments/assets/70a754be-130b-46a8-adf5-245fcbc8d93c) 

### 🔥 Stress Test Report
![image](https://github.com/user-attachments/assets/8a72a8ca-0e26-4276-85eb-9574691b103c)
