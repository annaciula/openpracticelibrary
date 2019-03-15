---
title: Feature Toggles
subtitle: On/Off
date: 2018-12-18T19:02:25.307Z
authors:
  - valyonchev
area: options
perspectives:
  - product-ownership
icon: /images/karim-manjra-1136416-unsplash.jpg
jumbotron: /images/karim-manjra-1136416-unsplash.jpg
people: 2+
time: 2+ hours
difficulty: moderate
participants:
  - Product Owner
  - DevOps Team
---
## What is it?

Feature Toggles are flags/switches which are used to change the behaviour of a product by activating or deactivating certain parts of it / features. It is a practice used in software development for allowing multiple versions of a product or additional features of the product to coexist in production, but not available to the typical users. 

Toggles allow for unfinished features to be released in production and be hidden for the typical users.  

## Why use it?

Feature Toggles provide a great way to manage the behaviour of the product in order to perform experiments or safeguard the performance when releasing fresh new features. 

Feature Toggles are used to:

* **Mange the release of new features** - allow unfinished features to exist in production and be activated once ready for release to public (can be gradually. Released as well)
* **Safeguard operations** - in this case toggles are used as enabler for [Canary Deployments](https://openpracticelibrary.com/practice/canary-release/) and allow operations to turn off any new feature which does not sufficient history and may still have an adverse effect on the product performance
* **Run experiments** - this is how [A/B Testing](https://openpracticelibrary.com/practice/split-testing-a-b-testing/) or [Multivari Testing](https://openpracticelibrary.com/practice/split-testing-multivari-testing/) can be implemented with the ability to “roll-back” to the productive version
* **Implementing permissions / class of users** - these toggles allow different group of users to benefit from the use of different set of features of the product, i.e. normal and premium users

## Why & How to combine it with other practices?

The Feature Toggles can greatly complement and make easier the implementation of practices like [A/B Testing](https://openpracticelibrary.com/practice/split-testing-a-b-testing/), [Canary Release](https://openpracticelibrary.com/practice/canary-release/), [Dark Launches](https://openpracticelibrary.com/practice/dark-launches/) in which the Feature Toggle is used to activate the “new” feature or version for a certain group/part of users. It is essential to the implementation of [Design of experiments](https://openpracticelibrary.com/practice/design-of-experiments/) practice.

## Related Practices

[Blue/Green Deployment](https://openpracticelibrary.com/practice/blue-green-deployments/)

[Canary Release ](https://openpracticelibrary.com/practice/canary-release/)

[Dark Launches](https://openpracticelibrary.com/practice/dark-launches/)

[Continuous Delivery](https://openpracticelibrary.com/practice/continuous-delivery/)

## Further information

[Feature Toggles (aka Feature Flags)](https://martinfowler.com/articles/feature-toggles.html) by Martin Fowler

Image credit: Photo by [Karim MANJRA](https://unsplash.com/photos/pWlM5L6PFis) on Unsplash
