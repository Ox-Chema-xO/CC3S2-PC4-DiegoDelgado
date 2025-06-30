# PC4 Proyecto 8: Generador de manifiestos de Kubernetes parametrizado
*Nombre*: Diego Manuel Delgado Velarde

*Correo*: diego.delgado.v@uni.pe

*URL del repositorio grupal*: https://github.com/Ox-Chema-xO/Generador-de-manifiestos-de-Kubernetes-parametrizado

## Sprint 1
Me encargue de:
- Crear `service.yaml.template`
- Crear `manifest_generator.py` para generar los manifiestos a partir de `templates/` y `values.yaml`

## Sprint 2
Me encargue de:
- Desarrollar funcionalidad de validacion de `values.yaml` usando un esquema json para nuestro generador de manifiestos
- Crear `test_validar_values` donde se verifica el correcto funcionamiento de la nueva funcionalidad implementada 

## Sprint 3
Me encargue de:
- Instalar helm y crear `helm-chart/` con lo necesario para nuestro proyecto y poder compara con nuestro generador de manifiestos
- Cree un script `comparar.sh` para generar los manifiestos con nuestro generador y helm y realizar la comparacion con diff 
