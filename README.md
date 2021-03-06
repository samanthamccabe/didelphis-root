# Didelphis Root
The base Didelphis project configuration shared by all core tools.

This module specifies common dependencies for testing, logging, and annotations.

### Changelog

#### version 0.4.0
 - Added Log4J 2
 - Removed Maven Surefire plugin from common build configuration

#### version 0.3.3
 - Updated dependency versions
 - Corrected license descriptor in project POM
 
#### version 0.3.2
 - Updated dependency versions
 - Changed license to [GPL 3.0](https://www.gnu.org/licenses)
 
#### version 0.3.1
 - Updated dependency versions
 - Returned to using dependency management
 - Removed deprecated dependency on `junit-platform-surefire-provider`

#### version 0.3.0
 - Updated dependency versions    
 - Added Lombok annotation processor to Maven plugin configuration

#### version 0.2.0
 - Removal of dependency management from configuration; deemed unnecessary for
   now
 - Upgraded JUnit to use `5.0.0RC2`
 - Changed ancillary dependencies to use `LATEST`
 - Added dependencies on [Project Lombok](https://projectlombok.org/)

#### version 0.1.0
 - Create of project root

