# Login Test Cases

| Test Case | Steps | Expected Result |
|---|---|---|
| TC01 - Valid login | Enter valid email + valid password, click Login | User redirected to dashboard |
| TC02 - Wrong password | Enter valid email + incorrect (but valid format) password, click Login | Error: "Incorrect password" shown, user stays on login page |
| TC03 - Empty password field | Enter valid email, leave password blank, click Login | Error: "Password required" shown, or button stays disabled |
| TC04 - Non-existent email | Enter unregistered email + any password, click Login | Error: "Account not found" or generic "Invalid credentials" |
| TC05 - Password missing special character | Enter valid email + password without required special character, click Login | Error: "Password must contain a special character" |
| TC06 - Username starts with a digit | Enter username starting with a digit + valid password, click Login | Rejected at validation, or treated as invalid username |