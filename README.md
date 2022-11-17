# DataMiner SSH Commando Executor
This application package will install an Automation script on DataMiner.
With the script you'll be able to set up an SSH connection to a remote server and execute a single command.

## Parameters
To run the Automation script, some parameters are needed:

- **host**: The hostname or IP of the server you want to execute the command on.
- **port**: The SSH port that is configured (default: 22).
- **username**: A username that has SSH rights.
- **password**: The password that corresponds with the username.
- **command**: The command you want to execute.

## DLL Reference
To run the Automation script, an existing open-source DLL was used, SSHNET. The DLL is embedded in the app package and automatically installed with the Automation script.
