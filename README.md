[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=7773534&assignment_repo_type=AssignmentRepo)
# Primer Trabajo de Actuación en Clase
## Consigna

Encontrar los errores en el código de Terraform y corregirlos. El código despliega los siguientes objetos:

* Un VPC
* Dos subnets
* Una instancia EC2
* Una Route Table
* Un Internet Gateway
* Un LoadBalancer, target groups y rules.

## Definición de terminado

El resultado debe ser la web de "Caffé" visualizada desde la url del LoadBalancer obtenida del OUTPUT. 

![caffe img](./img/caffe.png)

_Trabajo actuacion en clase_

Lucas Pereyra / Alexander Ortega / Pablo Gonzalez

**Solucion**

1. SG cambio al ac1-lb-sg
2. Se cambió el ingress del 88 al 80
3. En la isntancia le agregamos la subnet
4. Cambiamos el archivo del private key
5. Se modificó el Route Table (0.0.0.0/0)
