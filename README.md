# CraftingLib
Simple library for creating custom craftings.

### Changes
Fork changes java source version from 11 to 8 to support ancient bukkit versions.

Maven:
```
<repository>
  <id>eternalcode-reposilite</id>
  <name>EternalCode Repository</name>
  <url>https://repo.eternalcode.pl/</url>
</repository>
```
```
<dependency>
  <groupId>dev.piotrulla</groupId>
  <artifactId>CraftingLib</artifactId>
  <version>2.0.0</version>
</dependency>
```

Gradle:
```
maven {
    url = uri("https://repo.eternalcode.pl/")
}
```
```
implementation("dev.piotrulla:CraftingLib:2.0.0")
```
