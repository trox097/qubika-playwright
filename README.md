# Qubika Sports Club Management — E2E Automation with Playwright

**Exercise for QA Automation Engineer Position**

---

## 🚀 Project Overview

This repository contains an end-to-end test suite (TypeScript + Playwright) for the Qubika Sports Club Management System.  
The test demonstrates a hybrid API/UI flow:

1. **Seed Data via API**  
   Creates a new user using the Swagger-documented endpoint.  
2. **UI Automation**  
   - Validates the login page UI.  
   - Logs in with the newly created user.  
   - Navigates to the Categories page.  
   - Creates a root category and a subcategory, then verifies each.

---

## 📋 Prerequisites

- **Node.js** v16+  
- **npm** (bundled with Node.js)  
- Internet access to the QA endpoints:  
  - UI: `https://club-administration.qa.qubika.com`  
  - API: `https://api.club-administration.qa.qubika.com`

---

## 🔧 Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/qubika-playwright.git
   cd qubika-playwright
