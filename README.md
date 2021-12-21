# An Introduction About Web MVC framework
https://docs.spring.io/spring-framework/docs/3.2.x/spring-framework-reference/html/mvc.html
I learned about this during my internship, so I think it might be useful to have a look at it:)

## Spring's web module includes many unique web support features:

Clear separation of roles. Each role — controller, validator, command object, form object, model object, DispatcherServlet, handler mapping, view resolver, and so on — can be fulfilled by a specialized object.

Powerful and straightforward configuration of both framework and application classes as JavaBeans. This configuration capability includes easy referencing across contexts, such as from web controllers to business objects and validators.

Adaptability, non-intrusiveness, and flexibility. Define any controller method signature you need, possibly using one of the parameter annotations (such as @RequestParam, @RequestHeader, @PathVariable, and more) for a given scenario.

Reusable business code, no need for duplication. Use existing business objects as command or form objects instead of mirroring them to extend a particular framework base class.


### Salma Hashem's Comment on Article
##### This is an interesting article on a sopftware advancement that I am not too familiar with. This new Spring Web MVC framework is very flecible and provides a clean division between controllers, and JavaBean models and views. It's a powerful frameworm unlike the older ones as it is more testable and is well defined.