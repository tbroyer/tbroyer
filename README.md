I maintain projects in a few _categories_ below. All of those, except for the JavaScript ones, are used in production.

I have many more projects that I no longer maintain, but feel free to explore them in the [Repositories](https://github.com/tbroyer?tab=repositories&type=archived "Archived repositories") tab.
I also contribute to other projects, which you'll find in my contribution activity below.

## OpenID Connect and OAuth for JVM projects

* [OIDC-Servlets](https://github.com/tbroyer/oidc-servlets/) to add OpenID Connect to your servlets-based application, with support for JAX-RS.
* [OAuth-Servlets and OAuth-RS](https://github.com/tbroyer/oauth-servlets/) to add OAuth 2 to your servlets-based or JAX-RS Web APIs.

## Gradle plugins, and related

* [`net.ltgt.errorprone`](https://github.com/tbroyer/gradle-errorprone-plugin/) and its companion [`net.ltgt.nullaway`](https://github.com/tbroyer/gradle-nullaway-plugin/) to seamlessly use Google's [Error Prone](https://errorprone.info) and Uber's [NullAway](https://github.com/uber/nullaway/) in your Gradle builds.
* [`net.ltgt.flyway`](https://github.com/tbroyer/gradle-flyway-plugin/) to get [Flyway](https://github.com/flyway/flyway/) tasks like `flywayMigrate`; lighterweight than the official plugin, with easier control (and isolation) on its dependencies.
* [`net.ltgt.jooq` and `net.ltgt.jooq-kotlin`](https://github.com/tbroyer/gradle-jooq-plugin/) to run the [jOOQ code generator](https://www.jooq.org/doc/3.20/manual/code-generation/) against your database, in order to commit the generated files; lighterweight than the official plugin, with easier control (and isolation) on its dependencies; works well with the `net.ltgt.flyway` plugin.
* [Gradle IncAP Helper](https://github.com/tbroyer/gradle-incap-helper/): an annotation processor to help declare your own annotation processor's support for Gradle's incremental annotation processing.
* [Gradle Kotlin Accessors Generator](https://github.com/tbroyer/gradle-kotlin-accessors-generator/): an annotation processor to generate Kotlin DSL type-safe accessors for your Gradle plugin's extensions (for those cases where Gradle doesn't generate ones).

## JavaScript and Web development

* [Webfeet](https://github.com/tbroyer/webfeet/): a set of libraries to help make your JS APIs (incl. custom elements) ~~swim like a duck~~ behave like native, or in other words behave closer to the _web platform_ as currently spec'd.
* [decorator-compose](https://npmx.dev/package/decorator-compose) to create decorators that _compose_ other decorators
* [parameters-decorator](https://npmx.dev/package/parameters-decorator/): a method decorator to bring parameter decorators to ECMAScript (based on the TC39 proposal)

## GWT and Maven

* [Maven Plugin for GWT](https://tbroyer.github.io/gwt-maven-plugin/) to integrate [GWT](https://gwtproject.org) tools into your Maven project
* [GWT Maven Archetypes](https://github.com/tbroyer/gwt-maven-archetypes/) a couple archetypes to get started with GWT projects using Maven
* If you're curious about using GWT with Gradle, I have [an archived repository](https://github.com/tbroyer/gwt-gradle-example/) showing how I did that.
