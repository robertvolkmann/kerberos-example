# kerberos-example
Create keytab via:
```
$ ktutil
ktutil: add_entry -password -p HTTP/httpd.example.com@EXAMPLE.COM -k 1 -e aes256-cts-hmac-sha1-96
Password for HTTP/httpd.example.com@EXAMPLE.COM: password
ktutil: write_kt krb5.keytab
```
