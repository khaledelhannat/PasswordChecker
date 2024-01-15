# Password Checker
made by Python, is designed to assess the strength of user-provided passwords. It evaluates various criteria, such as length, inclusion of uppercase and lowercase letters, numbers, and special characters. The aim is to encourage the creation of robust and secure passwords that can withstand potential cyber threats.

## Program logic is as follows:
=> create a function that sends a request to the destination website and returns data. <br>
=> Convert our password to sha1 using hashlib library. <br>
=> Search for all compromised passwords that began with the same five characters or numbers as ours hash started with {k-anonymity}. <br>
=> We now compare the remaining hash of our password with the hash that we obtained after having a list of all the passwords that were converted to sha1 and began with the same beginning as ours. <br>
=> It will now display our password in sha1 hash format along with the number of hacks that it has experienced. <br>

## Installation
-> Download the files <br>
-> Run the Python file from the terminal by typing its name first, then the passwords you want to check (you can enter as many passwords as you want and the program will check for them all at once).
![image](https://user-images.githubusercontent.com/76536316/208256922-5369cf34-8a72-42a5-9636-630e6ecbe4ed.png)

## Employed libraries
<ul> 
  <li>requests</li>
  <li>sys</li>
  <li>hashlib</li>
</ul>
