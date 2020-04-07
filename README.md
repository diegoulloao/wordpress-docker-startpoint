# Wordpress|PHP|MySQL|phpMyAdmin setup in Docker

- **Repository:**
	- A docker full setup for wordpress development.
- **Stack:** Wordpress, MySQL, phpMyAdmin.
- **Services:** PHP, MySQL, Apache.
- **Year:** 2020.

This repository provides a complete wordpress setup enviroment.

## Step 1. Clone the repository.

Open a Terminal, browse your projects location and run:

```bash
git clone git@github.com:diegoulloao/wordpress-docker-startpoint.git project-name
```

## Step 2. Install Wordpress.

Enter in your `project-name` directory and run:

```
wget https://wordpress.org/latest.tar.gz
```

```
tar -xzvf latest.tar.gz
```

```
rm latest.tar.gz
```

## Step 3. Run the service.

Run:

```
docker-compose up
```

Open up your browser to http://localhost:8080/ and you should see your wordpress page as intended.

--

Containers created and their ports (if used) are as follows:

- **wordpress** - `:8080`
- **mysql** - `:3306`
- **phpmyadmin** - `:9090`

--

**@diegoulloao · 2020**