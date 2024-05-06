# Spring Security JWT

Spring Security has built-in support for JWTs using oAuth2 Resource Server. In this tutorial you are going to learn how to secure your APIs using JSON Web Tokens (JWT) with Spring Security.

- [Blog Post](https://www.danvega.dev/blog/2022/09/06/spring-security-jwt/)
- [YouTube](https://youtu.be/KYNR5js2cXE)

## Getting Started

Test with httpie:

```shell
http POST :8888/token --auth dvega:password -v
```

Which outputs a (very large) token. Then use the token with:

```shell
http :8080 'Authorization: Bearer xxx.yyy.zzz'
```

