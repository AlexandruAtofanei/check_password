# Project Name: Password Checker
#### Description: 
This aplication checks, using the api provided by https://haveibeenpwned.com/API/v3, if your password was in a data breach, helping an user choose a correct one. 
The SHA1 Hash is divided in two parts. To the API are sent only the first 5 characters. The given response is matched with the the last 35 characters of the hash and if there is a match, the user will be informed how many time that password was breached.
The passwords to be checked will be inserted in the 'tocheck.txt' file, so the sensible information will remain only on your computer.