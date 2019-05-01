# Wildcat Bluff Disc Golf Course link redirects
redirect.wildcatbluffdgc.cc is used to forward the static URLs in the QR codes on tee signs to their target pages.
Using redirects allows for updating these target pages in the future without having to change the permanent QR codes.

## Usage
**redirect.html** performs the redirects. Send a request for this file and indicate the target name at the end of the URL using query parameter:
```
?sendto=target name
```
**redirects.js** controls the target URLs matched from the "sendto" query parameter.  Edit or add key pairs in this file to define redirect target names with target URLs.

**index.html** (default page) displays a table of the defined URLs to redirect matched with their target URLs.

## Contact
Report issues or updates at: wildcatbluffdgc@gmail.com
