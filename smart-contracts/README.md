# Smart Contracts

Este directorio contendrá el proyecto Foundry del equipo.

## 1. Instalar Foundry

```bash
curl -L https://foundry.paradigm.xyz | bash
foundryup
```

Comprueba la instalación:

```bash
forge --version
```

## 2. Inicializar el proyecto

Desde este directorio:

```bash
forge init . --force --no-git
```

`--no-git` evita crear un repositorio Git dentro del repositorio principal.

## 3. Comprobar el proyecto

```bash
forge build
forge test
```

A partir de aquí podéis adaptar la estructura y eliminar los ejemplos generados por Foundry.