# languages-and-frameworks
Notes on Languages and Frameworks I have used

## Languages

| Name       | Typing           | Memory      | Concurrency | Flavour    | Meta  | Verdict |
| ---------- | ---------------- | ----------- | ----------- | ---------- | ----- | ------- |
| C          | static           | manual      | thread      | procs      | macro | ⟹ Go
| C++        | static           | manual/auto | thread      | class      | template | ⟹ Kotlin
| C#         | static           | gc          | thread      | class      | reflect | 🕒 .Net Core
| Clojure    | dynamic+hints    | gc          | thread      | functional | macro | 👍Liberator
| Crystal    | static           | gc          | coroutine   | object     |  | 👍Kemal+small
| Dart       | static+infer     | gc          | thread      | class      |  | 👍Flutter
| Elixir     | dynamic          | gc          | actor       | functional |  | 👍Phoenix
| Elm        | inference        | gc          | -           | functional |  | 👍/⟹ TypeScript
| F#         | inference        | gc          | thread      | class/func+dsl |  | 🕒 .Net Core
| Go         | static           | gc          | coroutine   | structural | annotate+generate | 👍small/low-level
| Java       | static+infer     | gc          | thread      | class      | annotate+reflect | 👍/⟹ Kotlin
| JavaScript | dynamic          | gc          | async/wait  | prototype+class | | ⟹ TypeScript
| Julia      | dynamic+hints    | gc          |
| Haskell    | inference        | gc          |
| Kotlin     | static           | gc          | co+thread | class+dsl | annotate+reflect | 👍Android/Javalin
| Lua        | dynamic          | gc          |
| Nim        | static           | gc          |
| OCaml      | inference        | gc          |             | func/class |
| PHP        | dynamic          | gc          |
| Pony       | inference        | gc          | actor       | functional | | 🕒 framework
| Python     | dynamic          | gc          |
| Ruby       | dynamic          | gc          | co+thread | object | monkeypatch | 👍Rails
| R          | dyanic           | gc          |
| Scala      | static+infer     | gc          | thread+actor | | | ⟹ Kotlin/Clojure
| Scheme     | dynamic          | gc          | | | | 👍SICP
| Swift      | static+infer     | auto        | | | | 👍iOS
| TypeScript | dynamic+hints    | gc          | async/wait | | | 👍Vue/React

### C

C is the first compiled language that I used. It is great for low-level work and making libraries to integrate with other languages. Unless I really need the last bit of performance, I would rather choose a language with managed memory.

### C++

This is the first class-based language that I used and also exposure to templates and generic types. Some problems organize well into class hierarchies with mixed static/virtual dispatch. I haven't used newer incarnations of the language and templates. Using the Boost libraries makes the experience much better. My preference is for fully managed memory rather than autoptr and haven't needed the low-level power combined with class/template abstractions on projects.

### C#

Really only used C# in the context of Unity 3D. Very natural coming from Java. Might possibly use this again in Godot but would probably try to use GDScript first. Mono and especially .Net Core makes this interesting for cross-platform use in the future.

### Clojure

Have only used this on small personal projects. I like the opinionated take on Lisp as well as being part of the JVM ecosystem. Don't understand what lispers have against running on a popular VM. Will continue to use with either Liberator or Composure frameworks.

### Crystal
### Dart
### Elixir
### Elm
### F#
### Go
### Java
### JavaScript/ECMAScript
### Julia
### Haskell
### Kotlin
### Lua
### Nim
### OCaml
### PHP
### Pony
### Python
### Ruby
### R
### Scala
### Scheme
### Swift
### TypeScript

## Frameworks

| Name | Verdict |
| ---- | ------- |
| none | 👍small(Go)/iOS(Swift)/Android(Kotlin) |
| Amber | ⟹ Kemal/Javalin/Phoenix |
| Compojure | 👍Liberator |
| Django | ⟹ Phoenix |
| DropWizard | ⟹ Javalin |
| Elm | 👍/⟹ Vue/React |
| Flutter | 👍Android/Android+iOS |
| Javalin | 👍JDBI (Kotlin) |
| Ktor | ⟹ Javalin |
| Kemal | 👍small |
| Liberator | 👍Korma/Toucan/HoneySQL |
| Micronaut | ⟹ Spring |
| Phoenix | 👍 |
| Rails | ⟹ Phoenix |
| React | 👍/⟹ Vue |
| Spark | ⟹ Javalin |
| Spring | 👍/⟹ Javalin/Phoenix |
| Sinatra | ⟹ Phoenix |
| Vaadin | ⟹ Phoenix |
| Vue | 👍(TypeScript) |
| Web2py | ⟹ Phoenix |
| Yii | ⟹ Phoenix |
| Yii2 | ⟹ Phoenix |

### none (any) ###
### Amber (Crystal)
### Compojure (Clojure)
### Django (Python)
### DropWizard (Java)
### Elm (Elm)
### Flutter (Dart)
### Javalin (Java/Kotlin)
### Ktor (Kotlin)
### Kemal (Crystal)
### Liberator (Clojure)
### Micronaut (Java)
### Phoenix (Elixir)
### Rails (Ruby)
### React (JS/TS/ReasonML)
### Spark (Java)
### Spring (Spring)
### Sinatra (Ruby)
### Vaadin (Java)
### Vue (JS/TS)
### Web2py (Python)
### Yii (PHP)
### Yii2 (PHP)

## Databases/Datastores

| Name | Verdict |
| ---- | ------- |
| Cassandra | ⟹ CockroachDB/FDB Record(JVM) |
| Cloudant | |
| CockroachDB | 👍sharded |
| Couchbase | ⟹ Redis |
| CouchDB | |
| Elasticsearch | 👍 |
| FoundationDB Document Layer | 👍/⟹ CockroachDB/MongoDB |
| FoundationDB Record Layer | 👍(JVM) |
| Memcached | ⟹ Redis |
| MongoDB | 👍/⟹ CockroachDB/FDB Document |
| MySQL | 👍multi-master |
| PostgreSQL | 👍master/replica |
| RabbitMQ | 👍 |
| Redis | 👍 |
| RethinkDB | |
| Riak KV | |
| Riak TS | |
| Solr | |
| TiDB | |
| TiKV | |


### Cassandra
### CockroachDB
### Couchbase
### CouchDB
### Elasticsearch
### FoundationDB Document Layer
### FoundationDB Record Layer
### Memcached
### MongoDB
### MySQL
  - InnoDB
  - TokuDB
  - RocksDB
### PostgreSQL
  - proper
### RabbitMQ
### Redis
### RethinkDB
### Riak KV
### Riak TS
### Solr
### TiDB

## Proprietary Databases/Datastores

### Amazon Aurora MySQL
### Amazon Aurora PostgreSQL
### Amazon DynamoDB
### Amazon Kinesis
### Amazon SQS
### Azure Cosmos DB
### Datomic
### Google Cloud Spanner
### IBM Cloudant (CouchDB)
