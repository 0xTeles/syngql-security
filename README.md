# syngql security queries

This repository contains a collection of useful SYNGQL queries that reference interesting functions within JavaScript code.

# What is SYNGQL

According SYNGQL developers, YNG is like grep but for JavaScript source code: it searches files for a statement, like a function call with specific arguments, based on syntax rather than text. Or, based on structure rather than format.

## Queries
- [postMessage](https://github.com/0xTeles/syngql-security/tree/main#postmessage)
- [new URL](https://github.com/0xTeles/syngql-security/tree/main#new-url)
- [addEventListener](https://github.com/0xTeles/syngql-security/tree/main#addEventListener)
### postMessage 

~~~
(call (mem postMessage _))
~~~
![image](https://github.com/0xTeles/syngql-security/assets/23142366/39673255-79a5-481f-86fb-d99475f30528)

### new URL
~~~
(of URL)
~~~
![image](https://github.com/0xTeles/syngql-security/assets/23142366/2cdff8f5-08ff-41bd-93cf-30357445ec22)

### addEventListener
~~~
(call (mem addEventListener _))
~~~
![image](https://github.com/0xTeles/syngql-security/assets/23142366/fcaf2a73-d54a-4121-bda6-dd2365e8035e)

## References
- https://syng.dev/docs/manual/
