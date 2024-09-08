
# Self Hosting Joplin

Repository for self host joplin server for synchronizing note on joplin app.


## Installation

Create the dot-env file from the template file and change the variable inside. 

```bash
  cp env-app-template .env-app
  cp env-db-template .env-db
```

Run the docker compose file with command 
```bash
  docker-compose -f docker-compose.yml up -d
```
![Logo](https://imgs.search.brave.com/ZVJt1qG8EG3z8bbrBBh6Gn2fAj-yVq1N6RhZaztEHUo/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9nbG9i/YWwuZGlzY291cnNl/LWNkbi5jb20vc3Rh/bmRhcmQxNC91cGxv/YWRzL2NvemljL29w/dGltaXplZC8yWC9k/L2RhNGRhZTljYjg0/NTExMzM2YzM5N2Zk/OTliM2U1ZGIyMjRi/ZGY0NDRfMl81MDB4/NTAwLnBuZw)

