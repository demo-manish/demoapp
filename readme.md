**Internal docker registry url:** <br/>
`oc get svc docker-registry -n default`

**Logging into docker registry:** <br/>`
`docker login -u `oc whoami` -p `oc whoami --show-token` <docker registry ip>:<docker registry port>`

**Pull into internal docker registry** <br/>
`docker pull openjdk:8-jdk-alpinee`