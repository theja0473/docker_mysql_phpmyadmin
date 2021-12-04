# docker_mysql_phpmyadmin
Docker-compose is an useful utility for managing multi-container docker applications. In our previous tutorial, I had discussed about the keep persistent data of MySQL docker containers using Docker volumes. Once you launched a MySQL container can be connect via terminal directly. But the phpMyAdmin lovers may need the web interface for managing databases.

   * The following command to create Docker containers using the docker-compose.yml configuration file.

      - docker-compose up -d

   * The above command will launch two Docker containers, one for MySQL database server and one for phpMyAdmin. Also a data volume will be created, which is attached with MySQL container to make data persistent.

   * Now, access the phpMyAdmin using the web browser. I am running this example on my local machine. So used host as localhost with port 8081 defined in docker compose configuration. You need to change localhost with your server ip address to access it remotely.

      - http://localhost:8081

   * if you want to make docker containers down

      - docker-compose down

