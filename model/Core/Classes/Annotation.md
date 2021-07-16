# Annotation

## Summary

An assertion made in relation to one or more elements.

## Description

An Annotation is an assertion made in relation to one or more elements.

## Metadata

- name: Annotation
- SubclassOf: Element
- Instantiability: Concrete

## Properties

- annotationType
  - type: AnnotationTypeVocab
  - minCount: 1
  - maxCount: 1
- statement
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- element
  - type: Element
  - minCount: 1

