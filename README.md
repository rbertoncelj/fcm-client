# FCM client

Forked from [google/fcm](https://github.com/google/gcm), but kept only the HTTP client part.

I did this, because I needed support for `content_available` and FCM, which were both added in master branch, which
has not been released yet.

```xml
<dependency>
    <groupId>com.bertoncelj</groupId>
    <artifactId>fcm-client</artifactId>
    <version>1.1.0</version>
</dependency>
```

See original project's readme for other info.