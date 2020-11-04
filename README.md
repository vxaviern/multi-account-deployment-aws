# Despliegue Multicuentas

Estos scripts configuran las cuentas de los clientes

Any code changes done to the lambda function (index.ts) will be picked up by the pipeline and a **build will be triggered automatically**

## Pre-Requisites
1. Cuenta de arranque con:
2. Un repositorio de CodeCommit3
3. Una s3 bucket como repositorio de artefactos
4. Cuenta de AWS del primer inquilino/cliente
5. Cuenta de AWS del segundo inquilino/cliente
6. Git instalado
7. Git configurado con AWS CLI
