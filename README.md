# angularjs-first-app

> [Angular tutorial - the First Angular app]([Angular tutorial - the First Angular app](https://angular.io/tutorial/first-app))

## commands

>### Testear la aplicacción por defecto  
>> Construcción del proyecto:
>> - navegar al directorio principal
>> - `npm install`
>>
>> Arrancar el servidor
>> - navegar all directorio principal
>> - `ng serve`
>>
>> Comprobar
>>> En el navegador abrir [http://localhost:4200](http://localhost:4200) 

>### Creación de un componente *HomeComponent*  
>> - navegar al directorio principal  
>>   ``ng generate component Home --standalone --inline-template --skip-tests``

>### Creación de una interfaz *HousingLocation*
>> - navegar al directorio principal  
>>   ``ng generate interface housinglocation``

>### Creación de un servicio *HousingService*
>> - navegar al directorio principal  
>>   ``ng generate service housing --skip-tests``

>### Generar mock para método *GET*
>> - instalar el json-server  
>>   ``npm install -g json-server``
>> - levantar el *mock* con los datos de prueba del fichero **db.json**  
>>   ``json-server --watch db.json``
