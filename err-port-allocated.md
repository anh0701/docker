# Problem
- failed: port is already allocated
# Solve
- check container what running was
- if running, execute: 
    ```sh
        docker ps
        docker stop CONTAINER_ID
    ```