# Software Verification for Tire Pressure Monitoring System (TPMS)

## Overview
The **Tire Pressure Monitoring System (TPMS)** is a critical safety feature in modern vehicles that alerts drivers about under-inflated tires, reducing risks related to tire failures. This project involves **software verification** of TPMS, ensuring its reliability, accuracy, and compliance with automotive standards.

## Project Details
- **Company:** Hyundai Motor India Engineering (HMIE)
- **Industry:** Automotive
- **Technology/Tools Used:**
  - Suresoft Controller Tester
  - Polyspace
  - Unit Testing
  - Integration Testing
  - Requirement-Based Testing
  - Static and Dynamic Testing
- **Objective:** Conduct comprehensive software verification before deployment in production vehicles to enhance safety and reliability.

## Workflow & Testing Methodology
### **1. Requirement Analysis**
- Gather system requirements from developers.
- Define test cases based on functional and non-functional requirements.
- Identify different TPMS variants (Sensata, Continental, Baolong) and their specific testing needs.

### **2. Static Testing**
- Perform **code review** and static analysis using Polyspace.
- Detect potential bugs, memory leaks, and security vulnerabilities before runtime execution.
- Ensure compliance with **MISRA C** and other automotive coding standards.

### **3. Dynamic Testing**
- Conduct unit and integration testing using **Suresoft Controller Tester**.
- Simulate real-world vehicle conditions to assess system response.
- Validate data accuracy from sensors under different driving conditions (speed, temperature, altitude variations, etc.).

### **4. Requirement-Based Testing**
- Map test cases to requirements ensuring full coverage.
- Verify expected vs. actual behavior for each test scenario.
- Conduct **traceability analysis** to track test results against functional requirements.

### **5. Automation & Optimization**
- Developed **automation scripts** to streamline testing.
- Reduced testing time per variant from **1 month to 1 week**.
- Improved efficiency and minimized manual testing efforts.

### **Key Contributions**
- Conducted comprehensive static and dynamic testing before production deployment.
- Performed requirement-based testing to verify developer specifications.
- Tested three different TPMS variants: Sensata, Continental, and Baolong.
- Reduced testing time per variant from 1 month to 1 week through automation.
- Improved efficiency recognized as a major accomplishment by the team.

### **6. Results & Impact**
- Identified critical software bugs before production deployment.
- Improved **system robustness** against false alerts and sensor failures.
- Enhanced vehicle safety by ensuring TPMS functions optimally in all conditions.
- Recognized as a **key efficiency improvement** within the Hyundai R&D team.

## Folder Structure (Recommended)
```
TPMS_Verification/
│── README.md                # Project documentation
│── test_cases/              # Contains detailed test cases
│── scripts/                 # Automation scripts for testing
│── reports/                 # Test results and analysis
│── docs/                    # Additional reference materials
```
## Conclusion
The **Software Verification for TPMS** project ensures that Hyundai's TPMS system operates reliably under all driving conditions. Through automated and requirement-based testing, the project significantly improved efficiency, reduced testing time, and enhanced vehicle safety.

