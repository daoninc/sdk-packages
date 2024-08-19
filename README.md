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
### GitHub Access Tokens
To access the repository you need a Personal Access Token. Personal access tokens are an alternative to using passwords for authentication to GitHub. See 
[Managing your personal access tokens](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens) and [Creating a classic personal access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens#creating-a-personal-access-token-classic). Use your github user name and token for username and password, e.g:

```
repositories {
    maven {
        url = uri("https://maven.pkg.github.com/daoninc/sdk-packages/")
        credentials {
            username = "mygithubusername"
            password = "ghp_VzFKNbb9XV21jvSBvUC3hTsf7W5pgXhq1Qkb"
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

