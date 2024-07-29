# SDK Repository

## Android
Maven Package Registry

|format|group|
|:-|:-|
|maven2|com.daon.sdk|

**Groovy DSL**
```
repositories {
    maven { url "https://maven.pkg.github.com/daoninc/sdk-packages/"
        credentials {
            username GITHUB_USER
            password GITHUB_TOKEN
        }}
}
```

**Kotlin DSL**
```
repositories {
    maven {
        url = uri("https://maven.pkg.github.com/daoninc/sdk-packages/")
        credentials {
            username = GITHUB_USER
            password = GITHUB_TOKEN
        }
    }
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

