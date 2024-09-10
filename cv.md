# Simon Skorokhodov

[E-mail][mailto] [LinkedIn][linkedin] [GitHub][github]

Software developer with more than ten years of experience. I focus on the
backend but don’t hesitate to work with UI or low-level projects.

## Skills

### Programming Languages

Rust, Clojure, Erlang, and C++.

I also have experience with ClojureScript, Java, Go, Python, SQL, Bash, Swift.

### Technologies and Frameworks

**Rust**: tokio, hyper, async-std, rustls.

**Clojure**: core.async, Datomic, ring/http-kit, re-frame.

**Erlang**: rebar, relx, cowboy, gproc, lager, RabbitMQ, Erlang ports, mnesia.

**Java**: Akka, Google Guice, OSGi (Apache Felix), JMX, Maven, RabbitMQ,
ZooKeeper.

**C++**: STL, WinAPI, MFC, Boost (some bits), ICU.

**Other**: OIDC, Earthly, Docker, Linux, KeyCloak, ESP-32, Protocol Buffers,
Open Telemetry, Nginx/Envoy, React Native.

### Soft Skills

For the first seven years, I worked in teams of 5-9 people. Most recently I
worked alone or in teams of 2-3.

I use agile tools like short iterations and regular meetings when appropriate.

While working at SUPREMATIC I supervised a bachelor thesis “Web application as a
homogeneous component of a distributed system” and a master’s degree work
“Implementation and evaluation of a message-oriented middleware for distributed
applications.”

## Professional Experience

### 2016 - present

_Software developer, SUPREMATIC Technology Arts GmbH_

- Custom CDN solution in Azure cloud. Fully automated deployment and
  stress-testing (Rust, Bicep)
- A family of Azure Container Apps. Fully automated deployment and integration
  testing (Rust, Bicep, Earthly, Docker Compose, Hurl).
    - backend for IAM needs (custom app + MS Graph API),
    - preferences storage (custom app + managed Postgres),
    - telemetry (Envoy + Grafana stack)
    - file share (Envoy + Blob Storage)
- CDN on-premise for internal software updates distribution (Rust, Earthly,
  tests in Babashka & Docker Compose).
- Portable LED-scoreboard:
    - ESP-32 software (C++, RTOS, HUB75),
    - iOS apps for tennis match tracking and updating the scoreboard’s software
      (React Native, ClojureScript).
- Rewriting the legacy Tennis Math server (Clojure, tests in Erlang, simple
  analytics with Graylog).
- Automatic deployment platform:
    - deployment server (Clojure, Datomic),
    - repository server (Clojure, PostgreSQL),
    - custom query language for system configuration (Clojure - instaparse),
    - command-line interface (Go),
    - web-UI (ClojureScript/re-frame, PatternFly).
- Distributed DNS filtering system:
    - master and worker servers (Erlang - mnesia),
    - command-line management interface (Erlang),
    - command-line tool for custom eclipse repository validation (Clojure).

### 2013 - 2016

_Software developer/Team lead/Head of development, Smilart_

Supervised the development of:

- extensible UI-box based on Raspberry PI (ClojureScript, Java)
- JS console for Smilart platform management and configuration
- Smilart platform Java API
- support for GenICam standard for camera configuration

Developed myself:

- simplified usage of industrial cameras for face detection and person
  recognition with Nvidia Tegra  (Erlang, C++)
- integration tests for Smilart Platform API (Erlang common test)
- Wiegand signal interceptor based on Raspberry Pi (Erlang, C++)
- tracing framework for a distributed face recognition platform, tools for the
  collected data analysis (Java, Clojure)
- redesign of request balancing system (Java)
- person identification and verification management system (Java)
- JSON-API for a face recognition platform (Java)
- performance analysis and memory leaks detection (Java)
- JMX-based system management (Java)
- rewriting photos selection algorithm from C++ to Java

### 2009 - 2013

_Software engineer, Severny Standart_

- design and development of a taxi service backend
- desktop applications for economics department and project management
- system operation and automation

### 2008 - 2009

_System administrator, Vologda State Technical University_

- switching a computer class from Windows XP to Gentoo Linux
- participation in deployment of diskless computer cluster
- installation and configuration of cluster software for the physics department
  research

## Education

Vologda State Technical University, Vologda, Electrical Engineering (Power
Supply), 2010.

## Personal

I try keeping a close eye on the latest IT news, follow blogs and podcasts. I
also enjoy learning new programming languages and development approaches. I’m a
happy father since 2020.

[mailto]: mailto:skorohodovsemen@gmail.com
[linkedin]: https://www.linkedin.com/in/simon-skorokhodov/
[github]: https://github.com/sskorokhodov
