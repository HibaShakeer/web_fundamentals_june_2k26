### API 
---
```Application programming interface that enables communication bw different applications```


### Webfundamentals
---

## client server architeture
    ```client sends an http request to server, server process the http request and send back http response ```

### http_methods
---
`GET` => fetch all resources  
`POST` => create an new resource  
`PUT` => update a resource  
`PATCH` => UPDATE a resource (partial update)  
`DELETE` => delete a resource  


### http_request_format
---

`url`  
`http_method`  
`Authorization`  
`body`  

### sample api end point
---

```
Employee

id  name    age   department  salary

1   haris    23          hr      25000
2   vipin    23          qa      25000
3   jithn    23          it      25000
4   rahul    23          hr      25000

```

```
http_request for adding employee

url: localhost:8000/employee/
method:POST
body:{
    "name":"vysak",
    "age":24,
    "department":"hr",
    "salary":45000
}



```
---
```
http_request for listing employee

url:localhost:8000/employee/
method:GET

```

---
```
http_request for fetching specific employee detail

url : localhost:8000/employee/4/
method:GET

```

```
http_request for updating an employee 

url:localhost:8000/employee/4/
method:PUT
body:{
    "name":"Rahul",
    "age":24,
    "department":"hr",
    "salary":30000
}

```

```
http_request for deleting  specific employee 

url:localhost:8000/employee/4/
method:DELETE
```

### Movie task

```
Movie

id      title      year     language        run_time


1          kgf1      2008      kannada           160
2          kgf2      2020      kannada           165
3          kgf3      2026      kannada           167
4          kgf4      2028      kannada           168
5          kgf5      2030      kannada           169

```

`http_request for adding new movie`

url:localhost:8000/movie/
method:POST
body:{
"title":"kgf",
"year":2026,
"language":"malayalam",
"run_time":167
}

`http_request for list all movie`
```
url:localhost:8000/movie/
method:GET
```

`http_request for fetching movie detail`
```
url:localhost:8000/movie/4/
method:GET
```
`http_request for update movie`
```
url:localhost:8000/movie/4/
method:PUT
body:{
"title":"Athiradi",
"year":2026,
"language":"malayalam",
"run_time":160
}
```

`http_request for delete movie`
```
url:localhost:8000/movie/
method:DELETE
```

### HOSPITAL REGISTER MANAGEMENT TASK
```
id   patient_name  phone_no    assigned_doc      consultation_fee


1          cassie   9746756743      jude           160
2          michael  8757389874      cardan         200
3          sloane   7467393746      sam            800
4          lia      9837647374      rowan          450
5          dan      8736541537      aelin          180

```
`http_request for adding new patient`
```
url:localhost:8000/patient/
method:POST
body:{
    "patient_name":"celena",
    "phone_no":7635268289,
    "assigned_doc":"sam",
    "consulatation_fee":240
}
```
`http_request for list all patient`
```
url:localhost:8000/patient/
method:GET
```

`http_request for fetching patient detail`
```
url:localhost:8000/patient/2
method:GET
```

`http_request for update patient`
```
url:localhost:8000/patient/5
method:PUT
body:{
    "patient_name":"dan",
    "phone_no":7985268289,
    "assigned_doc":"sam",
    "consulatation_fee":240
}
```
`http_request for delete patient`
```
url:localhost:8000/patient/5
method:DELETE
```
