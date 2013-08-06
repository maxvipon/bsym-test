# Bower vs SymLinks

Bower 1.0.1-1.1.0 installation failed if project has symlinks.

```bash
$ git clone git@github.com:maxvipon/bsym-test.git
$ cd bsym-test
$ npm install
$ ./node_modules/.bin/bower install
> bower error Didn't get expected byte count expect: 21 actual: 19
```
