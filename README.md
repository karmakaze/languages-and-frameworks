# languages-and-frameworks
Notes on Languages and Frameworks I have used

## Languages

| Name       | Typing           | Memory      | Concurrency | Flavour    | Meta  | Verdict |
| ---------- | ---------------- | ----------- | ----------- | ---------- | ----- | ------- |
| C          | static           | manual      | thread      | procs      | macro | -> gc
| C++        | static           | manual/auto | thread      | class      | template | -> gc
| C#         | static           | gc          | thread      | class      | reflect | wait .Net Core
| Clojure    | dynamic+hints    | gc          | thread      | functional | macro | use Liberator/Compojure
| Crystal    | static           | gc          | coroutine   | object     |  | use Kemal
| Dart       | static+infer     | gc          | thread      | class      |  | use Flutter
| Elixir     | dynamic          | gc          | actor       | functional |  | use Phoenix
| Elm        | inference        | gc          | -           | functional |  | ?
| F#         | inference        | gc          | thread      | class/func+dsl |  | wait .Net Core
| Go         | static           | gc          | coroutine   | structural | annotate+generate | use small/low-level
| Java       | static+infer     | gc          | thread      | class      | annotate+reflect | -> Kotlin
| JavaScript | dynamic          | gc          | async/wait  | prototype+class | | -> TypeScript
| Julia      | dynamic+hints    | gc          |
| Haskell    | inference        | gc          |
| Kotlin     | static           | gc          | coroutine+thread | class+dsl | annotate+reflect | use Android/Javalin
| Lua        | dynamic          | gc          |
| Nim        | static           | gc          |
| OCaml      | inference        | gc          |             | func/class |
| PHP        | dynamic          | gc          |
| Pony       | inference        | gc          | actor       | functional | wait
| Python     | dynamic          | gc          |
| Ruby       | dynamic          | gc          | fibre+thread | object | monkeypatch | use Rails
| R          | dyanic           | gc          |
| Scala      | static+infer     | gc          | thread+actor | | | -> Kotlin/Clojure
| Scheme     | dynamic          | gc          | | | | use SICP
| Swift      | static+infer     | auto        | | | | use iOS
| TypeScript | dynamic+hints    | gc          | async/wait | | | use

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

### Composure (Clojure)
### Django (Python)
### DropWizard (Java)
### Elm (Elm)
### Javalin (Java/Kotlin)
### Ktor (Kotlin)
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

### CockroachDB
### Couchbase
### CouchDB
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

## Proprietary Databases/Datastores

### AWS Aurora MySQL
### AWS Aurora PostgreSQL
### AWS DynamoDB
### AWS Kinesis
### AWS SQS
