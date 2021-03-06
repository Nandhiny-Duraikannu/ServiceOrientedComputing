# 18655-Spring-2017-Team-5
# Conference management system

## Setup

What do you need to setup the project:

* SBT (http://www.scala-sbt.org/download.html)
* MySQL database (create one before running the project)
* Intellij Idea with scala plugin (or use IDE of your choice, but I don't have instructions for you then)

Open 2 intellij projects - one in `api` folder, one in `frontend` folder.

Setup your database connection in *api/conf/application_template.conf* (read the instructions in that file).
Your database credentials will not be kept in git so anyone can have any password they want.

Then try to run both projects. You can do it from console with *sbt run* or from intellij 
(right-click on *app/controllers/HomeController* - *Run play 2 app*).
Then the API should be available at *localhost:9000* and web interface at *localhost:9001*.
At the first run, it may show an error and ask to apply 'database evolution'.
Just press the button on this web page and it should work.

## [Database schema](http://goo.gl/bnac5v)

## Play

Play documentation is here:

[https://playframework.com/documentation/latest/Home](https://playframework.com/documentation/latest/Home)

## EBean

EBean is a Java ORM library that uses SQL:

[https://www.playframework.com/documentation/2.5.x/JavaEbean](https://www.playframework.com/documentation/2.5.x/JavaEbean)

and

[https://ebean-orm.github.io/](https://ebean-orm.github.io/)

## Play Bootstrap

The Play HTML templates use the Play Bootstrap library:

[https://github.com/adrianhurt/play-bootstrap](https://github.com/adrianhurt/play-bootstrap)

library to integrate Play with Bootstrap, the popular CSS Framework.
