# Introduction

You are used to seeing API specifications, API fragments, and maybe even custom policies on Anypoint Exchange. This is the first place where we look for assets that we can potentially reuse. So you may ask yourself, how about my reusable logic encapsulated in flow/subflows? We can do the same! We can publish the MuleSoft project with flows on Anypoint Exchange as a MuleSoft Plugin that can be easily used in your projects by adding a dependency to the pom.xml file. 

## Description
Template project for Mule 4 common features encapsulated in (private) flows and/or subflows.
Usage and development is described in this [article](https://ambassadorpatryk.com/2018/08/sharing-flows/).

## Usage
- Open `pom.xml` file and solve all TODO comments
- Deploy to Anypoint Exchange using command `mvn clean deploy` or install it locally if you do not want to use Anypoint Exchange as a respoitory, using command `mvn clean install`.


# Release Notes
- 2022-09-07 - Added support to deploy to Anypoint Exchange as a MuleSoft Plugin asset. Updated plugins' versions.