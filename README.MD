# TAREA DE TERRAFORM

## PASO 1:

Para este primer punto ingresamos al siguiente link:
 https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0

Dentro de este link vamos al apartado de Overview y dentro de este usamos el comando que nos brindan en la sección de "How to use this provider":

```
terraform {
  required_providers {
    docker = {
      source  = "kreuzwerker/docker"
      version = "4.6.0"
    }
  }
}

provider "docker" {
  #Configuration options
}
```
Con esto Creamos el documento main.tf inicial.

