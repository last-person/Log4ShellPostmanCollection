# Log4ShellPostmanCollection
A simple postman collection to help you test for the Log4Shell Vulnerability

## Usage
- Download and install [Postman](https://www.postman.com/) 
- Download or clone this repo
- Import the Collection and Environment into Postman.  Be sure to select the environment "Log4Shells" in the environment dropdown.
- Store the url you want to test, in the "underTest" environment variable in the postman environment.
- Store your token or malicious string in the "vulnString" variable.
- Run one of the tests and wait a little while.  
- Check your token to see if it was triggered.   If it was, your mitigation/patch didn't work.
### Tokens
You can get a token from:
- https://canarytokens.org/generate (Select the Log4Shells type, and fill out the info)
  - https://twitter.com/ThinkstCanary/status/1469439743905697797
- http://dnslog.cn/ 


