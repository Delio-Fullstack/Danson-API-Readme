# Danson Backend Endpoints
`BaseUrl -> https://danson-test.herokuapp.com/`
### `Authorization * Required`
## ETA Settings Endpoints
###### `GET` GET all Orders Settings
```
https://danson-test.herokuapp.com/admin/v1/orders/settings
```
###### `POST` Add Orders Settings
```
https://danson-test.herokuapp.com/admin/v1/orders/settings
```
###### `PUT` Update Order Settings
```
https://danson-test.herokuapp.com/admin/v1/orders/settings/:id
```

##  METAFIELDS / LineItems ENDPOINTS
###### `GET` GET Single LinteItems
```
https://danson-test.herokuapp.com/admin/v1/metafields/lineitems/10523908440246
```
###### `POST` ADD lineItems/ETA
```
https://danson-test.herokuapp.com/admin/v1/metafields/lineitems/eta
```
###### `GET` Metafields for tracking
```
https://danson-test.herokuapp.com/admin/v1/metafields/tracking/
```

##  INVOICES ENDPOINTS
###### `GET` GET Single Invoice 
```
https://danson-test.herokuapp.com/admin/v1/invoices/:id
```
###### `PUT` Update Invoice
```
https://danson-test.herokuapp.com/admin/v1/invoices/:id
```
###### `GET` INVOICE PDF
```
https://danson-test.herokuapp.com/admin/v1/invoices/render/:id?pdf=1
```
###### `GET` INVOICE TEMPLATE by id
````
https://danson-test.herokuapp.com/admin/v1/invoices/render/:id?t=templateID`
````
##  TEMPLATES ENDPOINTS
 ###### `GET` GET Templates
 ```
https://danson-test.herokuapp.com/admin/v1/templates
```
###### POST Add New Template
```
https://danson-test.herokuapp.com/admin/v1/templates
```
###### `PUT` Update existing template
```
https://dansontest.herokuapp.com/admin/v1/templates/:templateID
```
###### `GET` By templateID
```
https://danson-test.herokuapp.com/admin/v1/templates/:templateID
```
###### `DELETE`  Remove Template
```
https://danson-test.herokuapp.com/admin/v1/templates/:templateID
```
