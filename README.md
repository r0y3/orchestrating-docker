Dockerizing Flask With Compose on Ubuntu 16.04 LTS
==================================================

Getting Started
---------------

1. Install docker and docker-compose.

    ```
    sudo apt-get install docker
    sudo pip install docker-compose
    ```
    
2. Run docker-compose.

    ```
    docker-compose build
    docker-compose up -d
    ```
    
3. Create database table.

    ```
    docker-compose run web /usr/local/bin/python create_db.py
    ```
    
4. Open your browser and goto ```http://127.0.0.1:90```.

**Check out the awesome blog post here > https://realpython.com/blog/python/dockerizing-flask-with-compose-and-machine-from-localhost-to-the-cloud/**

Cheers!
