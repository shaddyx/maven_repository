# maven_repository
To add this repo to gradle build:  
MicroTools:  
```gradle
repositories {
     maven { url "https://github.com/shaddyx/maven_repository/raw/master/" }
}

dependencies {
    compile "ua.org.shaddy:microtools:1.0.2-SNAPSHOT"
    compile "ua.org.shaddy:anion:1.0.2-SNAPSHOT"
}
```

