## Task text:

Luckily, we were able to trace multiple attacks on our servers during the election campaign back to the hacker group. Now you have to hack their website and figure out who they are and whom they are working for. Here is their website:

- http://timehackers.ctf-zone.org:80/
- http://timehackers.ctf-zone.org:8080/

## How to run task using docker container:

1. Create image

    ```
    docker build --tag=timehackers --no-cache .
    ```

2. Run docker image

    ```
    docker run -p 8080:8080 -p 80:80 timehackers
    ```

3. Edit /etc/hosts

    ```
    $SERVER_IP$	timehackers.ctf-zone.org
    ```

   Where **$SERVER_IP$** - IP of your host server. 


## Writeups:

https://blog.veryhax.ninja/blog/ctfzone-2017-timehackers/
https://docs.google.com/document/d/1Oj8fzdzMjbP32598onO9NyKLOexdiQLDGCLR8DDAeyM/edit
