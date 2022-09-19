# Registration and Login system using Python, file handling
#Stage -- 1 
#Registration
When the user chooses to Register
---> email/username should have "@" and followed by "."
it should not start with special characters and numbers eg:- 123#@gmail.com
---> password (5 < password length > 16)
              Must have minimum one special character,
              one digit,
              one uppercase, 
              one lowercase character 
#Stage 2 
  Once the username and password are validated, store that data in a file
#Stage 3
#Login
When the user chooses to Login, check whether his/her credentials exist in the file or If it doesn’t exist then ask them to go for Registration or 
If they have chosen forget password you should be able to retrieve their original password
