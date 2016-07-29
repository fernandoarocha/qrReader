1. Commands
-----------

```
npm install
node ./serve.js 8043 4080
```

2. Go to <https://local.helloworld3000.com:8043>
-------------

Then visit <https://local.helloworld3000.com:8043>.

Note that <http://local.helloworld3000.com:4080> will **redirect to https**.

**Note**: This points to **your localhost** but since it's very difficult to
develop, especially with HTTPS, with `127.0.0.1`, `localhost`, or `file://`,
I maintain `local.helloworld3000.com` and `local.foobar3000.com`
for examples such as this one.

**Note**: Your browser will warn you that you the server is using a bogus
certificate authority. That's okay for the purposes of this example.

Special Notes
----

**Note**: angular-example it' a directive to read qrCodes.

**Note**: index uses say_cheese and photobooth to read a qrCodes

