
### Installing Dependencies
  * Gradle [https://docs.gradle.org/current/userguide/installation.html]
  * Lombok Plugins:
    * [intellij](https://plugins.jetbrains.com/plugin/6317) -- [installation guide](https://github.com/mplushnikov/lombok-intellij-plugin#installation)
    * [eclipse](http://stackoverflow.com/questions/22310414/how-to-configure-lombok-in-eclipse-luna)

### Compiling
  `gradle clean compile`
  
### Building a shadowJar (Fat Jar)
  `gradle clean build shadowJar`
  
### deploying to nexus
  * enable the javadoc documentation
  * `gradle clean build javadoc upload`
  * enable the new package on sonatype
