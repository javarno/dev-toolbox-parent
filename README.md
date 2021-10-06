<!--
  - MIT License
  -
  - Copyright © 2020 dev-toolbox.org
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
- v1.8.0 2021/10/06 : jdk11 branch, downgraded slf4j-api to v1.7.32, logback to v1.2.6 / upgraded junit to v 5.8.1
- v1.7.3 2020/12/04 : upgrade javafx to 14.0.2.1, junit-jupiter to 5.7.0, surefire and failsafe plugins to 3.0.0-M5
- v1.7.2 2020/04/29 : define surefire and failsafe plugins version and override asm version for java 14 compatibility
- v1.7.1 2020/04/21 : fix version parameter name
- v1.7.0 2020/03/18 : java 14 and upgrade maven javadoc plugin to 3.2.0
- previous versions : history lost :)