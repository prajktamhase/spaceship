### MongoDB Easy

<details>
  <summary>What is MongoDB?</summary>

  <p>
  1. MongoDB is the NoSQL database that provides to store large amount of unstructured data. <br/>
  2. It works over the Document and Collection concept. <br/>
  3. MongoDB stores data in flexible, JSON-like documents with dynamic schemas, a format known as BSON (Binary  JSON).<br/>
  4. The MongoDB database contains collections just like allowed to create multiple databases and multiple collections.
  </p>
</details>

<details>
  <summary>What is BSON? and How it is different from JSON?</summary>

BSON stands for Binary JSON (Javascript Object Notetion). It is used to transmit and store data across web based applications. It has similarities with JSON for instance BSON .
<br/>
For Ex.

```js showLineNumbers=true
{
"_id": ObjectId("5f5a8f8e8216b52e5e9a0374"),
"name": "John Doe",
"age": 30,
"email": "john.doe@example.com",
"isStudent": false,
"grades": [85, 92, 78, 90],
"address": {
  "street": "123 Main St",
  "city": "Anytown",
  "zipcode": "12345"
}
}

```

**Difference between JSON and BSON**

JSON :

 <p>
 1. JSON files are written in text format. <br/>
 2. It is use to transmit of data. <br/>
 3. It is slow as compared to BSON.<br/>
 4. It has limited set of data types, including objects, arrays, strings, numbers, booleans, and null.
   </p>

BSON :

 <p>
 1. BSON files are written in binary. <br/>
 2. Databases use BSON to store data. <br/>
 3. It is Faster than JSON.<br/>
 4. It Extends JSON with additional data types such as binary data, date, regular expression, ObjectId .

   </p>

</details>

<details>
  <summary>What is `ObjectId` in MongoDB?</summary>

TODO: add question @RahulJadhav

</details>

<details>
  <summary>What is `collection` in MongoDB?</summary>

TODO: add question @RahulJadhav

</details>

<details>
  <summary>What is `document` in MongoDB?</summary>

TODO: add question @RahulJadhav

</details>
