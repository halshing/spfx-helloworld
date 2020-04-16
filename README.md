## SPFx Hello World

### Building the code

```bash
git clone https://github.com/halshing/spfx-helloworld.git
npm i
npm i -g gulp
gulp serve
```

This package produces the following:

* lib/* - intermediate-stage commonjs build artifacts
* dist/* - the bundled script, along with other resources
* deploy/* - all resources which should be uploaded to a CDN.
