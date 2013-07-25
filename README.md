This is a [giter8](https://github.com/n8han/giter8) template for bootstrapping
a new multi-module [Unfinagled](https://github.com/novus/unfinagled) SBT project with a default Novus configuration.

* SBT 0.12.3
* Cross build against Scala 2.9.2, 2.10.1, 2.10.2
* Aggregate project with a single "core" sub project
* [Scala Test](http://www.scalatest.org/)
* Test stub spinning up a Finagle-backed Unfiltered intent and running integration tests against it
* Project `name`, `organization` and `version` customizable as variables (Novus defaults)
* Novus code formatting standards (scalariform)
* SBT plugins: [sbt-dependency-graph](https://github.com/jrudolph/sbt-dependency-graph), [sbt-idea](https://github.com/mpeltonen/sbt-idea). [sbtscalariform](https://github.com/typesafehub/sbtscalariform)
* Everything in your project's base package imported automatically in repl sessions
