# Docker Common Configs
 Comonly used Configuration Files by me
 These configuration files are designed such that instead of installing standalone versions of software
 You could just run the configuration.
 This is especially good for Windows & Linux users as removing files and data has now become much easier

 Even though I have used Batch Format, the Method is cross-platform enough that it would be compatible with Linux OS

###CURRENT IMPLEMENTATIONS
 
1. [Postgres:Alpine](https://hub.docker.com/_/postgres "Postgres:Alpine")
    Default Password and Username set to postgres. Can be changed in Batch File
2. [Eclipse Mosquitto:latest](https://hub.docker.com/_/eclipse-mosquitto "Eclipse Mosquitto:latest")
    Used for MQTT Protocol

------------

Any new contributions need to be single line standalone commands such that the single line could be copy pasted into command line and it would stil run.
Also compulsorily, all contributors must link all sharable data with server_data volume rather than with local storage

------------

#### NOTE
 In order to use the Docker File, you need the presence of a volume named "server_data"
 This is an arbitrary name chosen by me
 To create docker volume, type in the command `docker volume create server_data`
