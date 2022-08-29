我的第一个go自定义包

# my_pkg

[![GoDoc](https://godoc.org/github.com/syyongx/php2go?status.svg)](https://godoc.org/github.com/syyongx/php2go)
[![Go Report Card](https://goreportcard.com/badge/github.com/syyongx/php2go)](https://goreportcard.com/report/github.com/syyongx/php2go)
[![MIT licensed][3]][4]

[3]: https://img.shields.io/badge/license-MIT-blue.svg
[4]: LICENSE

Use Golang to implement PHP's common built-in functions. About 140+ functions have been implemented.

## Install
```shell
go get github.com/fanchen-zc/my-pkg
```

## Requirements
Go 1.10 or above.

## PHP Functions

### Date/Time Functions
```php
time()
strtotime()
date()
checkdate()
sleep()
usleep()
```


## LICENSE
PHP2Go source code is licensed under the [MIT](https://github.com/syyongx/php2go/blob/master/LICENSE) Licence.
