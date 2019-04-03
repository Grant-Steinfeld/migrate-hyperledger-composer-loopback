## install the Loopback command line tool
```s
npm i -g @loopback/cli
```

## how to add a REST enpoint with loopback version 4
In loopback the REST crud enpoints for example POST/GET/DELETE etc
are in the controller and the type of data that is used by the controller is
in the model.

## Code Generation

### using existing swagger

What is swagger? Simply put it's the definition
of your API in a language agnostic way, usally represented in JSON or YAML. OpenAPI is

If you have an existing swagger.json url you can use the lb4 tool

```sh
lb4 openapi --url http://<<ipaddress/hostname>>/swagger.json --validate true
```

[details on using loopback OpenAPI code generation](./docs/SWAGGER-CODEGEN.md)



### Additional Resources

https://loopback.io/doc/en/lb4/todo-tutorial.html


[![LoopBack](https://github.com/strongloop/loopback-next/raw/master/docs/site/imgs/branding/Powered-by-LoopBack-Badge-(blue)-@2x.png)](http://loopback.io/)
