# Everyone Can Play! Building Great CTFs for Non-Security Folks #
## RSAC 2020 Learning Lab by [@jkuemerle](https://twitter.com/jkuemerle) ##

Materials and references for RSA 2020 talk "Everyone Can Play!"

Workshop activites require local Docker and/or free [Heroku](https://www.heroku.com) account. Local execution of utility scripts requires [Node.JS](https://nodejs.org/) 

To prepare in advance clone the this repository and the below repositories. If you will be working using local Docker you can build the CTFd Docker Compose definition.

For the report building any basic reporting tool will work. The workshop will use the [Elasticsearch, Logstash, Kibana (ELK) Docker Image](https://github.com/spujadas/elk-docker)  

## Repositories ##

### CTFd ###
Custom, Heroku ready version of CTFd: [https://github.com/jkuemerle/CTFd](https://github.com/jkuemerle/CTFd)

### OWASP Juice Shop ###
Custom, Heroku ready version of OWASP Juice Shop: [https://bitbucket.org/jkuemerle/juice-shop-rsa-2020](https://bitbucket.org/jkuemerle/juice-shop-rsa-2020)

### Utility Scripts ###
Are located in the [scripts](scripts) folder.

#### Juice Shop Challenge Extractor ####

Extracts challenges from a running Juice Shop instance.

#### YAML to Challenge Converter ####

Converts YAML document to Challenges/Flags/Hints

#### Build Script ####

Builds the CTFd instance.

### Integrated Challenge ###

Custom integrated challenge plugin for CTFd [URL TBD]

## Instructions ##