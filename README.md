# asyncapi-topic-registry
Simple UI for visualizing AsyncApi descriptions for existing Kafka topics

## Goals
### MVP
Having a simple UI in place reading all existing Topics from a configured Kafka-Cluster, display them and their configurations and also give the possibility to visualize an AsyncAPI Spec from a not yet decided source including that topic as "channel".
This way you have the possibility to simply lookup message formats and specifications for a message channel you are currently working with from a central documentation place.

### Additional functionalities

* Provide overview of involved topics for each specified API. Maybe check if they are existing as intended.
* Consider to extend this to a registry for openapi as well? Discover provided openapi documents within a cluster and give possibility to show visualization.
* When having a central registry for specifications one could consider extending it with capabilities of a schema registry.
