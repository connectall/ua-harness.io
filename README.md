# connectall-harness.io-adapter
ConnectAll universal adapter to sync harness.io deployment executions

The ConnectALL harness.io Adapter is developed as an extension to the Universal Adapter capability of ConnectALL. The adapter specifications will let the user start a new deployment, and retrieve the deployment status (pass or fail) back.

Please refer to https://wiki.connectall.com/ca/latest/adapters/universal-adapter for more information

# How to use

## Import specifications
* Import harness_config.zip into ConnectALL using "Install custom adapter" feature.

## Define application links
* Create an application link in ConnectALL between harness.io and another application of your choice.
* Navigate to `Configuration -> Connections` screen and create a new connection to harness using your harness.io access token.
* In the Entity mapping tab under Advanced Properties choose "Sync Type" as POLL
* In the field mapping tab add the field that you want to sync between the applications.
* Add the value for applicationId and entityId (see included screenshots in this repository).

> In order to use the harness.io adapter you will need to get the license from ConnectALL sales team. Please reach out to sales@connectall.com for licenses and quotes.

