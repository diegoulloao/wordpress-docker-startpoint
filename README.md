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

--

**@diegoulloao · 2020**