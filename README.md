These are some of the challenges for the OWASP Manchester and Manchester Grey Hats 2018 CTF.

A VM with the SSH challenge can be found here: https://drive.google.com/open?id=1Ip-N0IUhTI8Es5A72hpohj73JFaFZ1jf

Juice Shop can be run in CTF mode using docker:

`docker pull bkimminich/juice-shop`

`docker run -d -e "NODE_ENV=ctf" -p 3000:3000 bkimminich/juice-shop`

You can then access it in a browser on port 3000.
