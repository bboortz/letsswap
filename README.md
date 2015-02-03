# letsswap

Letsswap is a java webapplication offer platform with it you can swap digital items like images or texts with other users.

# used technologies

* java
* rest
* bootstrap
* mongodb
* maven


# project structure

* letsswap-web - the normal web gui (bootstrap)
* letsswap-web-admin - the admin web gui (bootstrap)
* letsswap-service-admin - the service for admin functions (REST)
* letsswap-service-registration - the service for user registration (REST)
* letsswap-service-authentication - the user authentication service (REST)
* letsswap-service-authorization - the user authorization service (REST)
* letsswap-service-userprofile - the service with user profile function (REST)
* letsswap-service-offering - a service to search and show for offerings (REST)
* letsswap-service-swap - a service to swap items (REST)
* letsswap-service-content - a service to show items (REST)


# user roles

* admin - full access
* operator - typical service functions
* user- normal user


# how to build

mvn build

# how to deploy

* cloudfoundry: cf push
