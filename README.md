Copyright (C) <2012> <LexisNexis Risk Data Management Inc.>

All rights reserved. This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as
published by the Free Software Foundation, either version 3 of the
License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program. If not, see <http://www.gnu.org/licenses/>.

http://hpccsystems.com

JDBC driver for HPCC platform

To build for Linux:
-------------------

1. Check out sources (for example, to directory ~/hpcc-jdbc)
2. Create a build directory
3. cd to the build directory
4. To create makefiles to build native release version for local machine, run cmake ~/hpcc-jdbc
5. To build the makefiles just created above, run make
6. class files will be built in <builddir>src/com/hpccsystems/jdbcdriver/class/
7. Jar file will be created in <builddir>/src/com/hpccsystems/jdbcdriver/hpccsystems-jdbcdriver-MAJOR.MINOR.POINT.jar