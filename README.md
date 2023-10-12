# SwaggerApiTestingByPostman

* Clone this repository.
* Open Postman
* Import collection and environment file on Postman.

## 🗃️ Newman and Report Installation Process
- Newman Install Command:
``` console
npm install -g newman
```
- Newman Html Report Install Command:
``` console
npm install -g newman-reporter-htmlextra
```
## 📜 Generate Test Report
* Run Command:
```console
newman run SwaggerUserApi.postman_collection.json -e SwaggerApiTestingEnvironment.postman_environment.json
```
* Run Command for Report:

htmlextra:
```console
newman run SwaggerUserApi.postman_collection.json -e SwaggerApiTestingEnvironment.postman_environment.json -r cli,htmlextra
```
