# docker-wp
Nginx+MySQL+WordPress  
Example image:)

## Install

### Step.1
Clone repository.
```
$ git clone https://github.com/cep3d/docker-wp.git
```

### Step.2
go to the directory.
```
$ cd docker-wp
```

### Step.3
Create .env file.
```
$ nano .env
```

Edit `.env` file as below.
```
WP_WORKING_THEME_DIR=./themes/custom
WP_THEME_DIR=wp-content/themes/custom
```

## Run
```
$ docker-compose up -d
```