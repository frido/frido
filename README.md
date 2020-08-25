## Maven statistics

<p>
  <img align='left' height="110px" src="http://petrzalka.info/mvn-statistics/charts/ciManagement.png">
</p>

Java multithreaded application that aims to analyze pom files from the central maven repository

It analyze 229,267 `pom.xml` files for the latest version of each maven project in the central maven repository. 

You can find the resulting statistics on the [github pages](http://petrzalka.info/mvn-statistics/).

**repository**: **[mvn-statistics](https://github.com/frido/mvn-statistics)**

## Projects in Petržalka
<p>
  <img align='left' height="110px" src="http://petrzalka.info/img/logo-m.png">
</p>

Web page about development projects in Petržalka

The page contains open information collected from Slovak government pages: plans, deadlines, government resolutions, etc. are summarized and displayed in an elegant and concise way.

You can access the page on [petrzalka.info](http://petrzalka.info/) or [frido.github.io](https://github.com/frido/frido.github.io)

**repositories**: **[petrzalka-11ty](https://github.com/frido/petrzalka-11ty)**: sources for [11ty](https://www.11ty.dev/) (the current version). **[petrzalka-hugo](https://github.com/frido/petrzalka-hugo)**: sources for [Hugo](https://gohugo.io/) (older versions)

## Government

Page with resolutions of the Petrzalka City Council

You can see the list of resolutions with very detailed information like voting, budget, and people's responsibilities.

The ambition was to experiment with and compare similar technologies. Here is the [list of comparisons](https://petrzalka.info/government/) with short descriptions of my preferred choices. I have been working on a related web about [the used technologies and their alternatives](https://petrzalka.info/government-page/).

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=frido%3Asamosprava&metric=alert_status)](https://sonarcloud.io/dashboard?id=frido%3Asamosprava), [![codebeat badge](https://codebeat.co/badges/796fdd58-d3cb-4e82-b8a9-7e8765e8b3d8)](https://codebeat.co/projects/github-com-frido-government-master), 
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/f7099cd093f6431eb759942b43f08dce)](https://www.codacy.com/app/frido/government?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=frido/government&amp;utm_campaign=Badge_Grade)
[![CircleCI](https://circleci.com/gh/frido/government.svg?style=svg)](https://circleci.com/gh/frido/government)

**repository**: **[government](https://github.com/frido/government)**

## Samosprava
The aim of this project was to provide a web-based management tool for data used by the Government page.

I used [JHipster](https://www.jhipster.tech/) as the development platform. The backend is built on [Spring Boot](https://spring.io/projects/spring-boot). The frontend is [Angular](https://angular.io/) application. Data were stored in [MongoDB](https://www.mongodb.com/) provided by [mLab](https://mlab.com/). The application was deployed on [Heroku](https://www.heroku.com/home#).

**repository**: **[samosprava](https://github.com/frido/samosprava)**

## MvnRepo

Application indexes `pom.xml` files in mvn repositories (like [Maven Central Repository](https://repo1.maven.org/maven2/)) to allow users to search for java artifacts. The project was inspired by [mvnrepository](mvnrepository.com).


My motivation was to try (in that time new) technologies like [Kotlin](https://kotlinlang.org/), [Gradle](https://gradle.org/), [Angular-CLI](https://cli.angular.io/). The application was running on [Heroku](https://www.heroku.com/home#).

I was experimenting to develop in cloud IDEs. My favorites were [Cloud9](https://aws.amazon.com/cloud9/) and [Codenvy](https://codenvy.com/)

**repositories**:

**[mvnrepo-indexer](https://github.com/frido/mvnrepo-indexer)**: [Java](https://www.java.com/en/) crawler to download all `pom.xml` files from the repository.

**[mvnrepo-backend](https://github.com/frido/mvnrepo-backend)**: [Spring Boot](https://spring.io/projects/spring-boot) application written in [Kotlin](https://kotlinlang.org/) provides REST-API backend.

**[mvnrepo-frontend](https://github.com/frido/mvnrepo-frontend)**: [Angular-CLI](https://cli.angular.io/) web application simply displays search results of Java artifacts. 

<!--
**frido/frido** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
