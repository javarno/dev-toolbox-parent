<!--
  - MIT License
  -
  - Copyright © 2020-2024 dev-toolbox.org
  -
  - Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files
  - (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish,
  - distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the
  - following conditions:
  -
  - The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
  -
  - THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
  - MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
  - CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE
  - OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
  -->

dev-toolbox-parent
==================

Parent pom for dev-toolbox.org projects.

history
-------
- v2.1.1 2023-09-23 : versions upgrade
  * slf4j-api 2.0.9 -> 2.0.12
  * logback-classic 1.4.11 -> 1.5.3
  * junit.jupiter 5.10.0 -> 5.10.2
  * maven-clean-plugin 3.3.1 -> 3.3.2
  * maven-compiler-plugin 3.11.0 -> 3.12.1
  * maven-dependency-plugin 3.6.0 -> 3.6.1
  * maven-failsafe-plugin.version 3.1.2 -> 3.2.5
  * maven-javadoc-plugin 3.5.0 -> 3.6.3
  * maven-surefire-plugin 3.1.2 -> 3.2.5
  * updated copyrights
- v2.1.0 2023-09-23 :
  * java 21
  * upgraded javaFX to v21
  * updated copyrights
- v2.0.8 2023-09-20 : upgraded javaFX to v17.0.8, slf4j-api to v2.0.9, logback to v1.4.11 and junit to v5.10.0
- v2.0.7 2023-07-16 : plugin versions upgrade, and slf4J / logback / junit
- v2.0.6 2023-01-29 : plugin versions upgrade, and slf4J / logback / junit
- v2.0.5 2022-10-21 : plugin versions upgrade, and slf4J / logback / junit
- v2.0.4 2022-05-14 : upgraded javaFX to v17.0.2, slf4j-api to v2.0.0-alpha7 and logback to v1.3.0-alpha15
- v2.0.3 2021-12-15 : upgraded javaFX to v17.0.1, JUnit to v5.8.2
- v2.0.2 2021-10-06 : fixed deployment, upgraded asm to 9.2
- v2.0.0 2021-10-06 : java 17, upgraded slf4j-api to v2.0.0-alpha5, logback to v1.3.0-alpha10 and junit to v5.8.1
- v1.8.3 2021-10-06 : fixed java version / deployment
- v1.8.0 2021-10-06 : jdk11 branch, downgraded slf4j-api to v1.7.32, logback to v1.2.6 / upgraded junit to v 5.8.1
- v1.7.3 2020-12-04 : upgrade javafx to 14.0.2.1, junit-jupiter to 5.7.0, surefire and failsafe plugins to 3.0.0-M5
- v1.7.2 2020-04-29 : define surefire and failsafe plugins version and override asm version for java 14 compatibility
- v1.7.1 2020-04-21 : fix version parameter name
- v1.7.0 2020-03-18 : java 14 and upgrade maven javadoc plugin to 3.2.0
- previous versions : history lost :)