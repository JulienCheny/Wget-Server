# Wget-Server


## Wget command

```
wget http://my-server:9090/test.zip
```

## Zip encryption commands

### Encrypt

This will prompt for a password:

```
zip --encrypt file.zip files
```

This is more insecure, as the password is entered/shown as plain text:

```
zip -P (password) file.zip files
```

### Decrypt

This will prompt for a password:

```
unzip file.zip files
```

This is more insecure, as the password is entered/shown as plain text:

```
unzip -P (password) file.zip files
```
