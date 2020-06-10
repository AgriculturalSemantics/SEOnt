---
layout: ontology_detail
id: seont
title: SEOnt
jobs:
  - id: https://travis-ci.org/AgriculturalSemantics/seont
    type: travis-ci
build:
  checkout: git clone https://github.com/AgriculturalSemantics/seont.git
  system: git
  path: "."
contact:
  email: 
  label: 
  github: 
description: SEOnt is an ontology...
domain: stuff
homepage: https://github.com/AgriculturalSemantics/seont
products:
  - id: seont.owl
    name: "SEOnt main release in OWL format"
  - id: seont.obo
    name: "SEOnt additional release in OBO format"
  - id: seont.json
    name: "SEOnt additional release in OBOJSon format"
  - id: seont/seont-base.owl
    name: "SEOnt main release in OWL format"
  - id: seont/seont-base.obo
    name: "SEOnt additional release in OBO format"
  - id: seont/seont-base.json
    name: "SEOnt additional release in OBOJSon format"
dependencies:
- id: envo
- id: agro
- id: foodon
- id: iao
- id: pato
- id: pco
- id: uo

tracker: https://github.com/AgriculturalSemantics/seont/issues
license:
  url: http://creativecommons.org/licenses/by/3.0/
  label: CC-BY
activity_status: active
---

Enter a detailed description of your ontology here. You can use arbitrary markdown and HTML.
You can also embed images too.

