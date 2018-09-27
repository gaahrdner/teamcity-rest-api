# teamcity-rest-api

TeamCity 2018.1 REST API documentation generated from `swagger-codegen`.

Browsable at: https://gaahrdner.github.io/teamcity-rest-api/

Regenerate via:

```
curl https://teamcity.example.com/app/rest/swagger.json > teamcity.json
swagger-codegen generate -i teamcity.json -l html -o .
```

### NOTE:

I initially encountered all sorts of `OutOfMemory` execptions from `swagger-codegen` version `2.3.1`, which is available via homebrew.  The `3.0.0` version seems to work fine but you'll need to manually build it, until myself or someone else updates the homebrew bottle definition.