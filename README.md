# [Maven statistics](https://github.com/frido/mvn-statistics)

<p>
  <img align='left' height="110px" src="http://petrzalka.info/mvn-statistics/charts/ciManagement.png">
</p>

Java multithreaded application that aims to analyze pom files from the central maven repository

It analyze 229,267 `pom.xml` files for the latest version of each maven project in the central maven repository. 

You can find the resulting statistics on the [github pages](http://petrzalka.info/mvn-statistics/).

# [Projects in Petržalka](https://github.com/frido/petrzalka-11ty)
<p>
  <img align='left' height="110px" src="http://petrzalka.info/img/logo-m.png">
</p>

Web page about development projects in Petržalka

The page contains open information collected from Slovak government pages: plans, deadlines, government resolutions, etc. are summarized and displayed in an elegant and concise way.

You can access the page on [petrzalka.info](http://petrzalka.info/) or [frido.github.io](https://github.com/frido/frido.github.io)

# [Government](https://github.com/frido/government)

Page with resolutions of the Petrzalka City Council

You can see the list of resolutions with very detailed information like voting, budget, and people's responsibilities.

The ambition was to experiment with and compare similar technologies. Here is the [list of comparisons](https://petrzalka.info/government/) with short descriptions of my preferred choices. I have been working on a related web about [the used technologies and their alternatives](https://petrzalka.info/government-page/).

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=frido%3Asamosprava&metric=alert_status)](https://sonarcloud.io/dashboard?id=frido%3Asamosprava), [![codebeat badge](https://codebeat.co/badges/796fdd58-d3cb-4e82-b8a9-7e8765e8b3d8)](https://codebeat.co/projects/github-com-frido-government-master), 
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/f7099cd093f6431eb759942b43f08dce)](https://www.codacy.com/app/frido/government?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=frido/government&amp;utm_campaign=Badge_Grade)
[![CircleCI](https://circleci.com/gh/frido/government.svg?style=svg)](https://circleci.com/gh/frido/government)

# [Samosprava](https://github.com/frido/samosprava)

Web-based management tool for the data used by the *Government* page

I used [JHipster](https://www.jhipster.tech/) as the development platform. The backend is built on [Spring Boot](https://spring.io/projects/spring-boot). The frontend is an [Angular](https://angular.io/) application. The data were stored in [MongoDB](https://www.mongodb.com/) provided by [mLab](https://mlab.com/). The application was deployed on [Heroku](https://www.heroku.com/home#). Due to newly introduced restrictions I was forced to remove the data.

# MvnRepo

Indexer of `pom.xml` files in mvn repositories

You can search for java artifacts located in the [Central Maven Repository](https://repo1.maven.org/maven2/). The project was inspired by [mvnrepository](mvnrepository.com).

My ambition was to try (at that given point bleeding edge) technologies such as [Kotlin](https://kotlinlang.org/), [Gradle](https://gradle.org/), and [Angular-CLI](https://cli.angular.io/). The application was running on [Heroku](https://www.heroku.com/home#).

This project made me experiment with cloud IDEs. My favorites turned out to be [Cloud9](https://aws.amazon.com/cloud9/) and [Codenvy](https://codenvy.com/)

**repositories**:

**[mvnrepo-indexer](https://github.com/frido/mvnrepo-indexer)**: [Java](https://www.java.com/en/) crawler to download all `pom.xml` files from the repository

**[mvnrepo-backend](https://github.com/frido/mvnrepo-backend)**: [Spring Boot](https://spring.io/projects/spring-boot) application written in [Kotlin](https://kotlinlang.org/) which provides REST-API backend

**[mvnrepo-frontend](https://github.com/frido/mvnrepo-frontend)**: [Angular-CLI](https://cli.angular.io/) web application simply to displays search results of Java artifacts
