# why dockerize

## References
1. https://www.globaldots.com/resources/blog/are-docker-containers-always-a-good-solution/
2. https://accesto.com/blog/when-to-use-and-when-not-to-use-docker/

## Benefits
1. Local or other env. setup is super easy no hassle of installing multiple s/w manually and no verion compatibilty issues. Docker compose can be leveraged.
2. Fast iteration to develop and deploy as focus on code and not on environment setup or version compatibility issues.
3. Much more useful in microservices based architecture as each microservice could have different tech stack and dependencies.
4. Vendor agnostic - os and cloud provider agnostic.
5. cost effective in terms of dev and ops team productivity and also switch to different cloud provider can be considered in case of high cost surges.

## Where docker might not be right fit
1. Graphics heavy app where docker container overhead might be visible.
2. Desktop/GUI based app
3. Need to persist auditable machine activity data(SOC2 compliance audit) - as docker container data is not persistent, need to setup volumes and bind mounts to ensure the data persists.
4. high security/complaince needs - security of prexisting docker images to be crosschecked thoroughly. 
