php-sha256
==========
##使い方

###SHA256でハッシュ化する

```PHP
SHA256::make("data", [bool raw_output = false]);
```

###HMAC方式をSHA256でハッシュ化する

```PHP
SHA256::hmac("data", "key",[bool raw_output = false]);
```
