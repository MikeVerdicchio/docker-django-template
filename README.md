Toast Chest
===========

This repository contains template files for running a Django application with a PostgreSQL database on Nginx, using Docker. These files are meant to be used as a starting point for a new Django application, and will not run out of the box.



Environment Setup
-----------------
1. Rename **.env-example** to **.env** and adjust variables as needed
2. Install Docker and Docker Compose
3. Run the following command to run a debug environment:
    ```
    docker-compose up
    ```

4. Run the following command for a production environment:
    ```
    docker-compose -f docker-compose.prod.yml up
    ```



License
-------
The material in this repository is released under a GNU General Public License v2.0.

Copyright (c) 2018.