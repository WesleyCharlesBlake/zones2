This is a simple bash script I created to attempt to retrieve a full DNS zone file for a domain.

Sine AXFR request (Full zones transfers) are pretty locked down, I figured I would create a list of most like common subdomains
and list through that. I added some other features as well, like dig and initially included some trace as well.

To use this, I placed the script in `/usr/local/bin` and then changed perms `sudo chmod 777 /usr/local/bin`

That way, you can call the command with a domain as the parameter
eg:
`zones2 mydomain.com`

feel free to fork this project if you find it will help
