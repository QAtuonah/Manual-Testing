# 🧪 HerokuApp Manual Test Cases

**Tested URL:** https://the-internet.herokuapp.com/  
**Environment:** Desktop - Chrome
## 🔹 1. Login Page

| ID   | Title              | Steps                                                         | Expected Result                  |
|------|--------------------|---------------------------------------------------------------|----------------------------------|
| TC01 | Valid Login        | 1. Open `/login`<br>2. Enter correct creds<br>3. Click Login  | Redirected with success message  |
| TC02 | Invalid Login      | Use wrong credentials                                         | Error message appears            |

## 🔹 2. Checkboxes

| ID   | Title              | Steps                                                       | Expected Result                    |
|------|--------------------|-------------------------------------------------------------|------------------------------------|
| TC03 | Toggle Checkboxes  | Check and uncheck checkboxes                                | State toggles properly             |

## 🔹 3. Dropdown

| ID   | Title              | Steps                                                       | Expected Result                    |
|------|--------------------|-------------------------------------------------------------|------------------------------------|
| TC04 | Select Dropdown    | Select Option 2                                             | Option 2 remains selected          |

## 🔹 4. File Upload

| ID   | Title              | Steps                                                       | Expected Result                    |
|------|--------------------|-------------------------------------------------------------|------------------------------------|
| TC05 | Upload Valid File  | Upload `.txt` file                                          | Confirmation message shown         |

## 🔹 5. JavaScript Alerts

| ID   | Title              | Steps                                                       | Expected Result                    |
|------|--------------------|-------------------------------------------------------------|------------------------------------|
| TC06 | Accept Alert       | Click "JS Alert" and accept                                 | Confirmation message shown         |
