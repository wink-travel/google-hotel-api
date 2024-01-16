# Google Hotel APIs Java SDK
Java objects from [Google Hotel APIs](https://developers.google.com/hotels) based on their publicly available [Schema files](https://developers.google.com/hotels/hotel-prices/dev-guide/schemas)

This supports Google Hotel APIs's version: NA

## Instructions
Java objects were created using the jaxb-maven-plugin and Java 21.

## Install
Grab library from Maven repo

~~~ xml
<dependency>
    <groupId>travel.wink</groupId>
    <artifactId>google-hotel-apis</artifactId>
    <version>{{ VERSION }}</version>
</dependency>
~~~

## Development
Generate library
`mvn clean compile`

Test library
`mvn clean test`
