# JSON
 - **JavaScript Object Notation (JSON)** : is a data-interchange format. JSON can represent numbers, booleans, strings, null, arrays (ordered sequences of values), and objects (string-value mappings) made up of these values. JSON does not natively represent more complex data types like functions, regular expressions, dates, and so on.(Date objects by default serialize to a string containing the date in ISO format, so the information isn't completely lost.) If you need JSON to represent additional data types, transform values as they are serialized or before they are deserialized.
  
```json 
   {
    "one": 2,
    "three": {
        "point_1": "point_2",
        "point_3": 3.4
    },
    "list": [
        "one",
        "two",
        "three"
    ]
}
```
