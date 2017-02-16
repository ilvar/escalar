# scala-elasticsearch-client

###<b>A Scala REST Client for Elasticsearch.</b>

###<b>Overview</b>

Scala-elaticsearch-client is a Scala project you can use to make requests over HTTP to your Elasticsearch cluster using 
Elasticsearch's REST API. 
This client supports a number of features of the 
[Elasticsearch REST API](https://www.elastic.co/guide/en/elasticsearch/reference/1.7/index.html).
Create indices, index documents, create and restore from snapshots, manage your cluster health, and[much more](../client/README#Documentation)using 
scala-elasticsearch-client. 

 We currently support v1.7 of the REST API, but we are currently porting our client to v5.X in the near future.
 
###<b>How-to</b>
...

###<b>Documentation</b>
...

###<b>Dependencies</b>

We use the following dependencies: 

[FasterXML jackson](https://github.com/FasterXML/jackson)
for JSON parsing.

[Jest](https://github.com/searchbox-io/Jest) is our core Java HTTP REST client for ES.
 
[Google Gson](https://github.com/google/gson) is used to serialize/deserialize Java objects to/from JSON.

###<b>License</b>
Copyright 2017 Workday, Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated
documentation files (the "Software"), to deal in the Software without restriction, including without limitation the
rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit
persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the
Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE
WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR
OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.