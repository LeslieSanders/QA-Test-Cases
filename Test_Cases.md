# ✅ Test Cases: SauceDemo Login

| TC ID | Title                        | Steps                                                                 | Expected Result                        | Status |
|-------|------------------------------|-----------------------------------------------------------------------|----------------------------------------|--------|
| TC01  | Login with valid credentials | 1. Go to login page<br>2. Enter valid user<br>3. Click login          | Redirect to inventory page             | Pass   |
| TC02  | Login with wrong password    | 1. Go to login page<br>2. Enter user + wrong password<br>3. Login     | Show error message "Username/password" | Pass   |
| TC03  | Empty username and password  | 1. Open login page<br>2. Leave fields blank<br>3. Click login         | Show "Username required" error         | Pass   |
