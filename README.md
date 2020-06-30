# Get-content-from-url

We can read website html content as below :

from urllib.request import urlopen
response = urlopen('http://google.com/')
html = response.read()
print(html)
