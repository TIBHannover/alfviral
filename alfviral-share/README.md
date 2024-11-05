# Alfresco Share Module

This module provides an easy way to manage **Alfresco Share** in a Docker environment. Use the commands below to start, stop, monitor, and clean up the Alfresco Share service.

## Prerequisites
Make sure Docker and Docker Compose are installed on your system.

## How to Use

> **Important:** Before running Alfresco Share, make sure to start the **alfviral-platform** service. Alfresco Share requires **alfviral-platform** to be running to enable communication between the two services. see: [README.md](../alfviral-platform/README.md)


1. **Navigate to the Project Directory**:
   ```shell
   cd alfviral-share/
    ./run.sh <command>
   ```
Where `<command>` can be one of the following:

1. `start`: Launch the Alfresco Share service in Docker.
2. `stop`: Stop the running Alfresco Share container.
3. `purge`: Remove all Alfresco Share containers and clean up associated resources (volumes, networks).
4. `tail`: Follow the logs for Alfresco Share, displaying real-time activity.