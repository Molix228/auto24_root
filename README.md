# Auto24 Project Root

It's a root directory of the project. And I want to explain how to setup this project below. Project consists of microservices, that's why you should follow my installation intructions.

## Requirements

Docker & Docker Compose
Git

## Installation

Clone all of needed repositories to run project.

```bash
# root_dir
git clone https://github.com/Molix228/auto24_root
# api-gateway
git clone https://github.com/Molix228/api-gateway
# auth-service
git clone https://github.com/Molix228/auth-service
```

Go to directory where were cloned all repositories.

```bash
cd your_local_directory_path/root_dir
```

Run docker-compsose.yaml file, that start-up all containers.

```bash
docker-compose up --build
```

## License

[MIT](https://choosealicense.com/licenses/mit/)
