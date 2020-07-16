### Projects in Petržalka

Projects in Petržalka is a web-page about development projects in Petržalka. It collects open information from government pages. Plans, deadlines, government resolutions (and next) are summarized and displayed attractively.

[petrzalka.info](http://petrzalka.info/) or [frido.github.io](https://github.com/frido/frido.github.io)

**repositories**: Current version is generated by [11ty](https://www.11ty.dev/) - see [petrzalka-11ty](https://github.com/frido/petrzalka-11ty). Older versions were generated by [Hugo](https://gohugo.io/) - see [petrzalka-hugo](https://github.com/frido/petrzalka-hugo)

### Government

It is a web page about resolutions of a city council, peoples related to the council, and city budget. A user can see a list of resolutions with very detailed information like voting, affected to budget, and people's responsibilities.

A motive was to try and compare similar technologies. There is a list of comparisons with a short description of what I would prefer - [link](https://petrzalka.info/government/). I wanted to create a web about used technologies and their alternatives, but I have never finished it - [link](https://petrzalka.info/government-page/).

Project used code analysis tools (
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=frido%3Asamosprava&metric=alert_status)](https://sonarcloud.io/dashboard?id=frido%3Asamosprava), [![codebeat badge](https://codebeat.co/badges/796fdd58-d3cb-4e82-b8a9-7e8765e8b3d8)](https://codebeat.co/projects/github-com-frido-government-master), 
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/f7099cd093f6431eb759942b43f08dce)](https://www.codacy.com/app/frido/government?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=frido/government&amp;utm_campaign=Badge_Grade)
), CI/CD tools (
[![CircleCI](https://circleci.com/gh/frido/government.svg?style=svg)](https://circleci.com/gh/frido/government), 
[buddy](https://buddy.works/)
), cloud application platforms ([heroku](https://www.heroku.com/home#), [openshift](https://www.openshift.com/)), loggers to simulate real commercial projects.

**repository**: [government](https://github.com/frido/government)

### Samosprava

The aim of this project was to provide a web-based management tool for data used by the Government page.

I used [JHipster](https://www.jhipster.tech/) as the development platform. The backend is built on [Spring Boot](https://spring.io/projects/spring-boot). The frontend is [Angular](https://angular.io/) application. Data were stored in [MongoDB](https://www.mongodb.com/) provided by [mLab](https://mlab.com/). The application was deployed on [Heroku](https://www.heroku.com/home#).

**repository**: [samosprava](https://github.com/frido/samosprava)

### MvnRepo

Application indexes `pom.xml` files in mvn repositories (like [Maven Central Repository](https://repo1.maven.org/maven2/)) to allow users to search for java artifacts. The project was inspired by [mvnrepository](mvnrepository.com)

**[mvnrepo-indexer](https://github.com/frido/mvnrepo-indexer)**: **Java** crawler to download all `pom.xml` files from the repository.

**[mvnrepo-backend](https://github.com/frido/mvnrepo-backend)**: **Spring Boot** application written in **Kotlin** provides REST-API backend.

**[mvnrepo-frontend](https://github.com/frido/mvnrepo-frontend)**: **Angular** web application simply display search results of Java artifacts. 

My motivation was to try (in that time new) technologies like Kotlin, Gradle, Angular-CLI, java.util.concurrent package and so on. The application was running on Heroku.

I was experimenting to develop on cloud IDEs. My favourites were [Cloud9](https://aws.amazon.com/cloud9/) and [Codenvy](https://codenvy.com/)

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
