# example_multiproject_sbt
Example: skeleton of a multi-project sbt build.

# Project Structure

This repository is split into subprojects:

* [subproject-0](https://github.com/malcolmgreaves/example_multiproject_sbt/tree/master/subproject-0)
  * Description
  
* [subproject-1](https://github.com/malcolmgreaves/example_multiproject_sbt/tree/master/subproject-1)
  * Description
  * Depnds on `subproject-0`

Shared build settings are located in [`project/SharedBuild.scala`](https://github.com/malcolmgreaves/example_multiproject_sbt/blob/master/project/SharedBuild.scala)

# Legal

The original author retains copyright over all material contained within this repository. Use of this code is governed under the terms of the Apache 2.0 open source software license. See the [LICENSE](./LICENSE) file for more details.

