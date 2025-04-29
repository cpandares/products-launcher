
## Clonar repositorio
```bash
git clone
```

## Clonar el .env.example 
```bash
cp .env.example .env
```

## Inicializar y actualizar Sub-módulos, cuando alguien clona el repositorio por primera vez, debe de ejecutar el siguiente comando para inicializar y actualizar los sub-módulos
```
git submodule update --init --recursive
```
## Para actualizar las referencias de los sub-módulos
```
git submodule update --remote
```

## Docker
```bash
docker-compose up --build
```