# http-client

Extendable axios http client

## Usage

```
const { HttpClient } = require("@ecbf/http-client");

const baseURL = "https://jsonplaceholder.typicode.com";
const { instance } = new HttpClient(baseURL);

instance.get("/todos/1").then((response) => {
  console.log(response.data);
});
```

## Built with

- [Axios](https://axios-http.com/)

## Author

Edwin Carl Flores
