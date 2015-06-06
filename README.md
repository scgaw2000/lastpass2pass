# lastpass2pass
a ruby script used to converted lastpass cvs data to pass format.

---

The file is based on the lastpass2pass.rb, which can be found in http://git.zx2c4.com/password-store/tree/contrib/importers/lastpass2pass.rb.

This file is modified for bettering grouping fitting my needs. 
If you have three accounts in two different domains, the structure of output files of this script is:

```
example.com/account1
example.com/account2
google.com/test@gmail.com
```

The content of each of the files will be:

```
password: P@ssw0rd
if there is any extra info, the info will be listed here
```