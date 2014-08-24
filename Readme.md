# Asciidoc-BoilerPlate

## Description

This project is a boiler plate for project intend to use asciidoc as a documentation generator.
This project is largely inspired by hibernate-search-parent.

## How to use

There are 2 steps for launching the build :

 - _mvn compile_ for generating the html doc
 - _mvn compile -Pdocbook_ for generating the pdf book

## Technical specification

This boilerplate use several main framework and plugin as :

 - *Maven* : for Integration purpose (integrate it in Hudson to build it automatically)
 - *asciidoctor-maven-plugin* : for generating the html documentation
 - *maven-jdocbook-plugin* : for generating the pdf book
 - *hibernate-jdocbook-style* : used for templating the book

## Author

Maneau 