lamassu-install
===============

This will install your Lamassu Bitcoin Machine remote server.

Instructions (Ubuntu user)
------------

1. If you are running Ubuntu 15.04 you will need to make Upstart as the default service and boot manager by following the instructions here: https://wiki.ubuntu.com/SystemdForUpstartUsers#Switching_init_systems

2. Become root:
   ```
   sudo -i
   ```

3. run the following command command:

    ```
    curl -#o install \
    https://raw.githubusercontent.com/crbanman/lamassu-install/master/install && \
    bash install
    ```

4. You should be set. Just follow the instructions on the screen to open your dashboard.
