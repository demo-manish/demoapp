** Internal docker registry url:
    oc get svc docker-registry -n default

** Logging into docker registry:
    docker login -u `oc whoami` -p `oc whoami --show-token` <docker registry ip>:<docker registry port>

** Pull into internal docker registry:
    docker pull openjdk:8-jdk-alpine