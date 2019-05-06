# Election-Web-API-System
A system of an arbitrary number of API's that, when collectively invoked, self-elect a "leader" API per an internal algorithm.

A third party API (the "Coordinator") initiates the election process to be performed among the n-many "Participant" APIs (those which cast a vote).
The Participants each send their votes to the Coordinator and the Coordinator replies with the ID of the Participant that was elected as the "leader".

The purpose of electing a "leader" API service is beyond the scope of this project; this functionality can be extended to perform some arbitrary task that requires only one service.
