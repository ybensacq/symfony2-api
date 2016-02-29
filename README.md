# Symfony2 Kickstarter - API Edition

Contains symfony2 standard edition (currently 2.8) stripped and custom to json API serving.

## REMOVED
- symfony/swiftmailer-bundle
- sensio/framework-extra-bundle
- sensio/distribution-bundle

## ADDED
- **kleijnweb/swagger-bundle** [repository](https://github.com/kleijnweb/swagger-bundle)
	- routing configuration based on swagger.io document
	- Validate request parameters based on swagger.io document
	- Object Serialization shortcuts (with JMSSerialize)
	- format Responses
- **kleijnweb/swagger-bundle-tools** [repository](https://github.com/kleijnweb/swagger-bundle-tools)
	- Ressource Class Generator
- **jms/serializer** [repository](https://github.com/schmittjoh/serializer)
- **doctrine/migrations**

##TODO
###bundle trials

- **vlucas/phpdotenv** [repository](https://github.com/vlucas/phpdotenv)
- **fr3d/swagger-assertions**
- **doctrine/annotations**
- **kleijnweb/jwt-bundle**


## Inspiration
[https://github.com/kleijnweb/symfony-swagger-microservice-edition](https://github.com/kleijnweb/symfony-swagger-microservice-edition)