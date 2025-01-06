# Password-Checker

This is a password checker application to see if your password has been used in external websites!

Request library -> make HTTP request for the Have I Been Pwned API

Haslib -> create SHA-1 hash of the password

1. The inputted password gets converted into a SHA-1 hash

2. The first 5 characters of the hash are extracted and sent to the API

3. The API responds with matched characters from the hash

4. The script checks the remaining characters and count the number of times that it shows up in the database

This system ensures that only the first 5 characters are sent to the API so that not the full password is exposed during the check.

Thank you!!




