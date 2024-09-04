# Building the API Documentation
## Initial setup 

copy over the package.json
``` cmd 
run npm install
run npm audit fix --force
```

## Generate the documentation
``` cmd 
cd src-api
curl -OutFile openapi.json