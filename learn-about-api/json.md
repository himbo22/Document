# JSON - Introduction

JSON stands for JavaScript Object Notation

JSON is a text format for storing and transporting data

JSON is "self-describing" and easy to understand

# JSON Example

> `'{"name":"John", "age":30, "car":null}'`

It defines an object with 3 properties:

* name
* age
* car

Each property has a value.

# What is JSON?

* JSON stands for JavaScript Object Notation
* JSON is a lightweight data-interchange format
* JSON is plain text written in JavaScript object notation
* JSON is used to send data between computers
* JSON is language independent *

# JSON syntax rules

JSON syntax is derived from JavaScript object notation syntax:

* Data is in name/value pairs
* Data is separated by commas
* Curly braces hold objects
* Square brackets hold arrays

# JSON Data - A Name and a Value

JSON data is written as name/value pairs (aka key/value pairs).

A name/value pair consists of a field name (in double quotes), followed by a colon, followed by a value:

> EXAMPLE
> `"name":"John"`

JSON names require double quotes.

# JSON Values

In JSON, values must be one of the following data types:

* a string
* a number
* an object
* an array
* a boolean
* null

In JavaScript values can be all of the above, plus any other valid JavaScript expression, including:

* a function
* a date
* undefined

# JSON vs XML

Both JSON and XML can be used to receive data from a web server.

The following JSON and XML examples both define an employees object, with an array of 3 employees:

JSON Example

```json
{"employees":[
  { "firstName":"John", "lastName":"Doe" },
  { "firstName":"Anna", "lastName":"Smith" },
  { "firstName":"Peter", "lastName":"Jones" }
]}
```

XML Example
```xml
<employees>
  <employee>
    <firstName>John</firstName> <lastName>Doe</lastName>
  </employee>
  <employee>
    <firstName>Anna</firstName> <lastName>Smith</lastName>
  </employee>
  <employee>
    <firstName>Peter</firstName> <lastName>Jones</lastName>
  </employee>
</employees>
```

**JSON is Like XML Because**

* Both JSON and XML are "self describing" (human readable)
* Both JSON and XML are hierarchical (values within values)
* Both JSON and XML can be parsed and used by lots of programming languages
* Both JSON and XML can be fetched with an XMLHttpRequest

**JSON is Unlike XML Because**

* JSON doesn't use end tag
* JSON is shorter
* JSON is quicker to read and write
* JSON can use arrays

**The biggest difference is:**

XML has to be parsed with an XML parser. JSON can be parsed by a standard JavaScript function.

**Why JSON is Better Than XML**

XML is much more difficult to parse than JSON.
JSON is parsed into a ready-to-use JavaScript object.