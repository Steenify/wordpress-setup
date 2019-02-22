# Wordpress setup

For DigitalOcean, this will setup:
- wordpress
- phpmyadmin

### Step 1:
Create one click app on DigitalOcean. Choose:
  - Image: **Docker 18.06.1~ce~3 on 18.04**
  - Plan: **10$**
  - Region: **Singapore**
  - Additional Options: **Monitoring**
  - SSH Keys: **Select all**
  - Rename the host to remember easily.

### Step 2:
Copy 2 files: `docker-compose.yml`, `uploads.ini` to any directory of the server. (Suggest: `~/`)

### Step 3:
Open terminal and go to that directory then type:
```
docker-compose up -d
```

Wait for 30s to see if it works or not.

# Note:

- **phpmyadmin** is at port **8080**, account to login: `root` - `123456`
- **wordpress** is at port **80**

## Authors

* **tuyenhx** - From [Steenify](https://steenify.com)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
