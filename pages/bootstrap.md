Bootstrap
======================

## Summary

Bootstrap is a popular front end framework used by XD Colleagues on a large number of client projects, to develop responsive websites.

#### Pros

Bootstrap provides in-built responsive classes, jquery plugins and html components to start off building beautiful responsive web applications. It is easy, fun to learn and quick to be implemented across various backend technologies.

#### Cons

At times, one needs to tweak bootstrap's inbuilt classes and plugins which might take more time, than writing one on your own. Also, if you are not using all of bootstrap's features, then including the heavy css file on your projects might add a toll on the http requests. 

***

## Forms
#### [jQuery Validator Plugin](http://www.jqueryvalidation.org) 

**Used by** - Harish
**Project** - HCA

#### Summary
1. Plugin used for client side form validation
2. Needs jQuery
3. One of the oldest jQuery validation plugins, updated and improved constantly

#### Pros
1. Easily customizable, plug and play with any front end framework
2. Large number of inbuilt validation methods
3. Strict rules enforced for validation
4. Neat User Interaction

#### Cons
1. Learning curve needed for adding new validation methods
2. Error messages are displayed inline, some times
3. Need 'name' attribute for all the input elements requiring validation

***

#### [Bootstrap Validator Plugin](http://bootstrapvalidator.com/) 

**Used by** - Mike Gorgone
**Project** - BSC

#### Summary
1. Plugin used for client side form validation
2. Needs Bootstrap
3. Needs jQuery

#### Pros
1. Based on Bootstrap so if you're building the site using Bootstrap the plug-in is based on the framework
2. Many [examples](http://bootstrapvalidator.com/examples/) on the website
2. Settings allow you to intantiate the validator with custom error messages etc.
3. Uses validators
3. Access to the API

#### Cons
1. Since it's based on Bootstrap your forms must be structured using Bootstrap classes
2. If you have dynamic form fields that are visible/hidden and you are using other Bootstrap plug-ins in the form (ex. bootstrap select) you will run into issues. Hidden fields can be ignored so they aren't validated BUT in the case of bootstrap select the select HTML markup is hidden even though the rendered dropdown list is visible.
3. Need 'name' attribute for all the input elements requiring validation

***

## Bootstrap Themes
#### [Bootswatch](http://www.bootswatch.com) 

#### Summary
1. Bootswatch provides themes built on top of bootstrap, downloadable for free.
2. Contains a large number of themes such as flat, slate, paper, etc.
3. If you want your site to be different from the regular bootstrap site, this is a good options.

#### Pros
1. Select the theme you want and click download. It is that simple.

#### Cons
1. Difficult to customize.
2. Difficult to move to another theme after a particular one is used on the application.
