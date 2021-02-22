Netrunner Encryption

Este es el codigo desarrollado para la captura de bandera de Tenable 2021.
El servidor montaba el codigo crypto.php, sobre el cual no se visualizaba la key, pero con el codigo fuente se podía reconocer el uso de AES128ECB.
Aprovechando al debilidad, se desarrolla el codigo de pruebas en Python, el cual ejecuta prueba de comparaciones, ingresando cada digito hacia el servidor.

AES128ECB_Padding-Attack
CTF Tenable
