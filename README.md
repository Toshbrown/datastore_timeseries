#Timeseries Datastore

The datastore exposes data on port 8080 using hostname datastore_wirelessthings

hitting datastore_wirelessthigns:8080/api with an OPTIONS request will return more detailed instructions on how to access
* Realtime data through MQTT feeds
* Historical data through HTTP api calls
* Realtime data through HTTP api calls 

data calls to the api and MQTT feed subscriptions will not subject to validation of a macaroon which can be obtained from the broker 

components must be registered with the databox_directory as per instructions in the related repo readme in order to work with databox