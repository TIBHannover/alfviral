# Alfviral Antivirus Module

This module enables the deployment and management of **ClamAV** within a Docker container. With simple commands, you can
start, stop, monitor, and clean up your ClamAV service.

### Prerequisites

Ensure that Docker and Docker Compose are installed on your system.

### How to Use

1. **Navigate to the Project Directory**:
   ```shell
   cd alfviral-antivirus/
   ```
2. Run Commands: Use the following commands with script_name.sh to manage the ClamAV container:
   ```shell
     ./script_name.sh <command>
    ```

Where `<command>` can be one of the following:

1. `start`: Launch the ClamAV service in Docker.
2. `stop`: Stop the running ClamAV container.
3. `purge`: Remove all ClamAV containers and clean up associated resources (volumes, networks).
4. `tail`: Follow the logs for ClamAV, displaying real-time scanning activity.

