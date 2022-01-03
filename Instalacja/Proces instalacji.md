# Sprawdzanie sha 
  sha1sum filename.
  
# signature check example for manjaro on mint
download plig iso.sig
```sudo apt-get install wget```
``` gpg --keyserver keyserver.ubuntu.com --search-keys Manjaro Build Server```
``` gpg --verify file.name```
