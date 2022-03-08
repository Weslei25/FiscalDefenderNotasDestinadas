# FiscalDefenderNotasDestinadas
Inquiry Service Intended Notes

![image_2022_03_08T17_11_49_934Z](https://user-images.githubusercontent.com/76075516/157289957-3568ae16-46e9-4d4f-a649-6a2efd068d1a.png)

>status: development⚠️

### It is a desktop application developed for consultation of intended notes, where periodic screening of documents issued against the consulted CNPJ is carried out.

## The fields in the main template are:

+ Customer registration
+ company registration
+ automatic search for registered companies
+ consultation of tax documents at the national sefaz

Also, there is a user with these fields:

+ user
+ password
+ host
+ port

# Configuration file


![image_2022_03_08T17_15_33_755Z](https://user-images.githubusercontent.com/76075516/157290436-31e292ed-c842-4995-88c0-5aa378700149.png)

### Required to connect to the database
+ user: usuario
+ password: senha
+ port: porta
+ database: nome do banco

### Time for consultation notes intended
+ tempo_exec_consulta:60
### Time to catalog nfe for nfedestined
+ intervalo_dia_cataloga_notas: 10000
+ tempo_exec:60

# Install
+ To install the service, the https://nssm.cc/usage
