## What's in the box?

This is the ground floor docker config for our collection of icmib services. The `docker-compose.yml` file is the main entry point for the services. Each relevant service will have it's own name appropriate directory that will contain a `devcontainer.json` file for use with VSCode's Remote Containers extension.

## Why do I need this?

This is a quick way to get up and running with the services we use. It's also a way to ensure that everyone is using the same versions of the services and tools we use. This is also an incredibly convinient way for all of our VSCode extensions to be in sync, as well as allowing us to lint all of the code without needing to install anything on our local machines.

## How do I use it?

1. Install Docker
2. Install the Remote Development extension for VSCode
3. Open a new window in VSCode, select this repo as the folder
4. Open the command palette(F1) and run `Reopen in Container`
5. From the dropdown, select the service you want to open in a container
6. Repeat stes 3-5 for each service you want to work on

## Is this your first time? ##
Howdy!  Check here --> https://github.com/Material-Dev/icmib-handbook/blob/master/files/onboarding_new_dev_environment.md
## Misc

* VSCode extention - https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack
* Rubymine stuff - https://www.jetbrains.com/help/ruby/connect-to-devcontainer.html#start_container_from_product
