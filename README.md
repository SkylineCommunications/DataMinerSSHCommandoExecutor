# DataMiner SSH Commando Executor
This application package will install an automation script on DataMiner.
With the script you'll be able to setup an SSH connection to a remote server and execute a single command.

## Parameters
To run the automation script some parameters are needed:

- host : hostname or ip of the server you want to execute the command on
- port : ssh port that is configures (standard this is 22)
- username : username that has SSH rights
- password : password of the username
- command : command you want to execute

## DLL Reference
To run the automation script an existing opensource dll was used, SSHNET. The dll is embedded in the app package and automatically installed with the automation script.