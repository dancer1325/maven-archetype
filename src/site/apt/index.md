# Maven Archetype

* 👀== Maven project templating toolkit 👀
  * allows
    * creating OTHER Maven projects templates
      * / set BEST practices | your project OR organization
    * generating NEW Maven projects -- based on -- these templates
  * built-in Maven archetypes

* archetype
  * := ORIGINAL pattern or model /
    * 👀from which -> ALL OTHER things are made 👀
  * use cases
    * create a site
    * standardize J2EE development | your organization 
      * -> you -- may want to provide -- archetypes for EJBs, or WARs
  * `mvn archetype:generate`
    * create a NEW project -- based on an -- Archetype
    * see [usage](/maven-archetype-plugin/src/site/apt/usage.md)

* == SEVERAL modules

*-----------------------------------------------------------+----------------+
|| Module                                                   || Description   ||
*-----------------------------------------------------------+----------------+
| <<{{{./maven-archetype-plugin/}maven-archetype-plugin}}>> | Archetype Plugin -- to use -- archetypes + Maven,
*-----------------------------------------------------------+----------------+
| {{{./archetype-packaging/}archetype-packaging}}           | Archetype lifecycle and packaging definition,
*-----------------------------------------------------------+----------------+
| {{{./archetype-models/}archetype-models}}                 | Descriptors classes and reference documentation,
*-----------------------------------------------------------+----------------+
| {{{./archetype-common/}archetype-common}}                 | Core classes,
*-----------------------------------------------------------+----------------+
| {{{./archetype-testing/}archetype-testing}}               | Components used internally -- to test -- Maven Archetype,
*-----------------------------------------------------------+----------------+
