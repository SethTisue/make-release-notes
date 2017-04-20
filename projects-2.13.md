## Available Projects for Scala 2.13.0-M1

Library maintainers, library users, please [submit a pull request](https://github.com/scala/make-release-notes/edit/2.13.x/projects-2.13.md) and let the world know what libraries are available.

<!--
### Scaladex

Scaladex, the index of Scala libraries, now offers searching by target version:

* [Scala modules for 2.13.0-M1](https://index.scala-lang.org/search?q=keywords:scala-module)
* [Testing frameworks for 2.13.0-M1](https://index.scala-lang.org/search?q=targets%3Ascala_2.13.0-M1+AND+keywords%3Atesting)
* [Other libraries for 2.13.0-M1](https://index.scala-lang.org/search?q=targets%3Ascala_2.13.0-M1)
* [Compiler plugins for 2.13.0-M1](https://index.scala-lang.org/search?q=keywords%3Acompiler-plugin+AND+targets%3Ascala_2.13.0-M1)
* [Sbt plugins for 2.13.0-M1](https://index.scala-lang.org/search?q=keywords%3Asbt-plugin+AND+targets%3Ascala_2.13.0-M1)
-->

### Scala modules

Add in sbt using `libraryDependencies += ...`:

    "org.scala-lang.modules"           %% "scala-xml"                 % "1.0.6"

More coming in the next few days.

### Testing frameworks

Add in sbt using `libraryDependencies += ... % "test"`:

    "org.scalacheck"                   %% "scalacheck"                % "1.12.6"          % "test"
    "org.scalacheck"                   %% "scalacheck"                % "1.13.4"          % "test"
    "org.scalacheck"                   %% "scalacheck"                % "1.13.5"          % "test"

### Other libraries

Add in sbt using `libraryDependencies += ...`:

    "org.scalaz"                       %% "scalaz-core"               % "7.2.11"

### Compiler plugins

Add in sbt using `addCompilerPlugin(...)`:

(None yet! Add yours?)

<!--
    "org.scalamacros"                  %% "paradise"                   % "2.1.0"
-->

### Sbt plugins

Most plugins do not need to be re-published for 2.12, but certain plugins did require changes.

Add using `addSbtPlugin(...)`:

(None yet! Add yours?)

<!--
    "org.scala-js"                     % "sbt-scalajs"                % "0.6.13"
-->

<!--
### Pending

You can subscribe to these tickets to find out when a library you want becomes available:
-->