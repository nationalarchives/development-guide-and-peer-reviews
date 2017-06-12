# Development guide and peer review

## Introduction

This repository outlines an approach that will support us in delivering high quality, inclusive and maintainable digital services while achieving a good balance between innovation and effective use of our development capability. It is a living, open tool to which we should all contribute and is comprehensively reviewed each year (See details of the [2016 review](reviews/2016-review.md) here).

There is also a [presentation pack](https://docs.google.com/presentation/d/1NOJYWAzMVNe-Uj-ZyUki3PiO1lR_cm9-ZmAwdl496fQ/edit?usp=sharing) which provides a more detailed outline of the purpose, scope and components of this guide.

## What's included

1. a high level [peer review checklist](/peer-review-checklist.md) with sections covering: 
    - **design** considerations
    - **development** and pull requests
    - **testing** of accessibility and compatibility
2. a [development guide](/development-guide.md) describing the development standards for our digital services.

## Developer responsibilities

It is the responsibility of developers to: 

1. Ensure The National Archives' design patterns are reflected

2. Identify the checks relevant to the specific development activity and **ensure their development work meets all relevant standards in the development standards**

3. Ensure the **pull request takes place at a time that  allows for any necessary changes** before the product or service is made public. (Note: the progressive enhancement approach set out in this Development Guide is intentionally designed so that developers will have a good sense of the project 'health' at any given time, reducing the likelihood that substantial changes will be needed as development nears completion).

4. Where appropriate, discuss any lessons learned during a Design Team 10% meeting with a view to capturing insights that might benefit our approach to future projects

## Conducting a peer review

* The peer reviewer should clone this repository to their development machine and create a copy of ```peer-review-checklist.md```. The copy should then be added to this repository in the relevant folder. For example, a peer review of a meeting minutes template conducted in 2017 would be saved as ```peer-review-meeting-minutes.md``` within the ```2017``` directory.
* The peer reviewer should then populate the created file with the peer review comments and discuss these with the developer when completed. 
* The developer should then act on the comments and, where necessary, describe how they have addressed any issues raised.
* The merging of any code to `develop` is managed via a pull request process during which the reviewer(s) will be confirming that all development standards are met.
