# Swift Language Resources

This url database is used to power:
http://www.h4labs.com/dev/ios/swift.html

## Create db.go file

```
#bin/gen_go_var.sh > db.go; # tsv file must be in /tmp until I fix code
./doit.sh; # New way
```


## Google's App Engine fails if this file contains non-UTF8 characters.
Look for them with this grep: grep -av '^.*$' swift_urls.tsv
