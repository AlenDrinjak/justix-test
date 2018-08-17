# justix-test

- Terrafform will provide aws resources: ec2 instance and RDS (if needed more than one instance, copy lines to create as much backend instances as needed)
- deploy.yml will install Docker and docker-composer (if needed after aws resources deployment)
- docker-deploy-wordpress.yml will create dockerized wordpress, nginx and rds database (in this case only local database. Add aws rds endpoint for backend database)
- haproxy.yml will start HAProxy dockerized (currently no SSL proxy to backend instances - do have an idea how to provide it, but need some more time)
- python3.yml will install python3

