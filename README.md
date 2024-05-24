# SDK Repository

## Android
Maven Package Registry

|format|group|
|:-|:-|
|maven2|com.daon.sdk|

**Groovy DSL**
```
repositories {
    maven { url "https://maven.pkg.github.com/daoninc/sdk-packages/" }
}
```

**Kotlin DSL**
```
repositories {
    maven(url = "https://maven.pkg.github.com/daoninc/sdk-packages/")
}
```

### Dependencies (examples)

**Groovy DSL**
```
implementation 'com.daon.sdk:face:5.3.4'
```

**Kotlin DSL**
```
implementation("com.daon.sdk:face:5.3.4")
```

