Gatling's SBT plugin demo
=========================

A simple project showing how to configure and use Gatling's SBT plugin to run Gatling simulations. A changed from 
https://github.com/gatling/gatling-sbt-plugin-demo 

Run a single simulation
-----------------------

```bash
> gatling:testOnly computerdatabase.BasicLocal
```

List all tasks
--------------------

```bash
> tasks gatling -v
```

> sbt "gatling:testOnly computerdatabase.BasicLocal"
