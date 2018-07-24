# ServiceNow Resources

## Table of Contents
1. [Development Resources](#development-resources)
1. [Websites](#websites)
1. [Misc](#misc)


## JavaScript Features Not Supported In ServiceNow
This is a list of JavaScript features (ES5 & ES6 & beyond) that are not supported in the ServiceNow implementation of Mozilla Rhino. 

**NOTE**: NO ES6 features are supported in ServiceNow!

- `Array.forEach`
- `=>` - arrow functions are not supported
- 


## Development Resources
- [ServiceNow Standards Framework](https://github.com/iamkalai/SNStandardsFramework) by [@iamkalai](https://github.com/iamkalai)
- [Interface Design Patterns for Script Includes](https://codecreative.io/servicenow/interface-design-patterns-for-script-includes) by [@tltoulson](https://github.com/tltoulson)
- [Glider.js](https://github.com/tltoulson/Glider.js) by [@tltoulson](https://github.com/tltoulson)
- [Script Execution Order](https://docs.servicenow.com/bundle/jakarta-servicenow-platform/page/script/general-scripting/reference/r_ExecutionOrderScriptsAndEngines.html)
- [Script evaluation of fields by data type](https://docs.servicenow.com/bundle/jakarta-servicenow-platform/page/script/general-scripting/reference/r_ScriptingOfFieldTypes.html)

### Service Portal
- [Scope in Service Portal](https://www.dylanlindgren.com/2017/10/28/service-portal-fundamentals-angularjs-scopes/)
- [Unofficial Service Portal Docs](https://github.com/newrocketinc/service-portal-docs)
- [Service Portal Best Practices](https://github.com/platform-experience/serviceportal-best-practice)
- [Widget Anatomy](https://www.youtube.com/watch?v=MllpUpcl6TI)
- [Service Portal  Training](https://developer.servicenow.com/app.do#!/trainlist/app_store_learnv2_serviceportal_jakarta_service_portal?v=jakarta)
- [Advanced Widget Development](https://developer.servicenow.com/app.do#!/creatorcon/CCW1088/creatorcon_18_CCW1088_5_sharing_data_and_events)


### Web Services
- [Sample REST HTTP Request](https://gist.github.com/bryanbarnard/1f2d9e819dfb5fad41a3)

### JavaScript
#### Online Courses
- [codecademy](https://www.codecademy.com/learn/introduction-to-javascript): **codecademy** is a great resource for learning the basics of JavaScript
- [Code School](https://www.codeschool.com/learn/javascript)
- [The Odin Project](https://www.theodinproject.com/courses/javascript-and-jquery)
- [freeCodeCamp](https://www.freecodecamp.org)


#### Books
- [Eloquent JavaScript](http://eloquentjavascript.net/) is one of my personal favorite JavaScript books
- [JavaScript Enlightenment](http://www.javascriptenlightenment.com/)
- [Learning JavaScript Design Patterns](https://addyosmani.com/resources/essentialjsdesignpatterns/book/)
- [JS Books](http://jsbooks.revolunet.com/)


#### Other Resources
- [50 Best JavaScript Resources](https://medium.com/coderbyte/50-resources-to-help-you-start-learning-javascript-in-2017-4c70b222a3b9)
- [16 JavaScript Concepts You Must Know Well](http://javascriptissexy.com/16-javascript-concepts-you-must-know-well/)
- [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)
- [JS for Cats](http://jsforcats.com/) is a great and funny introduction to JavaScript

#### Angular
**NOTE:** As of Kingston, Service Portal uses Angular 1.5.1. Angular 1.6 & 2+ features are not supported. 
##### Tutorials
- PAID - Although it's not free, this is my #1 recommendation for learning Angular 1.x for ServiceNow: [udemy](https://www.udemy.com/learn-angularjs/)
- [angularjs.org tutorial](https://docs.angularjs.org/tutorial)
- [codecademy](https://www.codecademy.com/learn/learn-angularjs)
- PAID - Tons of courses on Angular 1.x: [pluralsight](https://www.pluralsight.com/paths/angular-js)

##### Articles
- [scotch](https://scotch.io/tutorials/angularjs-1-x-fundamentals-part-1)

##### Books
- My #1 recommendation on books: [ng-book](https://www.ng-book.com/)

## Websites

- [serviceportal.io](https://serviceportal.io)

## Videos
- [Getting Started with ServiceNow Development](https://www.youtube.com/playlist?list=PL3rNcyAiDYK0maVCCzBAGKGcILgBgiP7Z)



## Misc
- If a company is using SSO and you are being redirected, try `<instance-name>.service-now.com/login.do` or `<instance-name>.service-now.com/side_door.do`


### Service Portal Structure
#### Tables
- Service Portal [`sp_portal`]
- Theme [`sp_theme`]
- Page [`sp_page`]
- Widget [`sp_widget`]
- Instance [`sp_instance`]
    - Instance of Carousel [`sp_instance_carousel`]
    - Instance with Link [`sp_instance_link`]
    - Instance with Menu [`sp_instance_menu`]
    - Instance with Table [`sp_instance_table`]
        - Instance of Simple List [`sp_instance_vlist`]
- Carousel Slide [`sp_carousel_slide`]
- Menu Item [`sp_rectangle_menu_item`]
- Header | Footer [`sp_header_footer`]
- Search Source [`m2m_sp_portal_search_source`]
- Search Group [`sp_search_group`]
- Widget Dependency [`sp_dependency`]
- Widget Dependency [`m2m_sp_widget_dependency`]
- Angular Providers [`m2m_sp_ng_pro_sp_widget`]
- Service Portal Log Entry [`sp_log`]
- Service Portal UI Formatter [`sp_ui_formatter`]
- Angular ng-template [`sn_ng_template`]
- Widget Script Include [`m2m_sp_widget_script_include`]
- Service Portal Documentation [`sp_documentation`]
- JS Includes [`m2m_sp_theme_js_include`]
- JS Include [`sp_js_include`]
- Stylesheets [`m2m_sp_theme_css_include`]
- CSS Include [`sp_css_include`]
