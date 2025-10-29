🏦 App Bank – Proyecto de Lógica de Solución de Problemas

App Bank es una aplicación desarrollada en Java con Spring Boot y Maven, pensada para simular el funcionamiento de un banco.
Con esta app puedes crear clientes, abrir cuentas, hacer depósitos, retiros y transferencias fácilmente.
El proyecto fue hecho aplicando principios de programación orientada a objetos, arquitectura por capas y manejo de datos con JSON.



⚙️ Tecnologías Usadas

	•	 Java 17+
	
	•	 Spring Boot
	
	•	 Maven
	
	•	 Springdoc OpenAPI (Swagger)
	
	•	 Thunder Client (para pruebas de endpoints)



📂 Estructura del Proyecto

•controller

Controla las peticiones (endpoints) y conecta con el servicio

•service

Contiene la lógica principal del negocio.

•repository

Maneja el almacenamiento de datos en archivos JSON.

•model

Define las clases (Cliente, Cuenta, Transacción, etc.).

•exception

Maneja errores personalizados del sistema.

💻 Programas Necesarios

🟦 Visual Studio Code – Editor de código
🔧 JDK (Java Development Kit) – Para ejecutar proyectos Java
📦 Maven – Para compilar y gestionar dependencias


🧩 Extensiones Recomendadas

Estas extensiones te facilitan todo el trabajo dentro de VS Code 👇

	•	☕ Extension Pack for Java
	•	🧰 Debugger for Java
	•	⚙️ Maven for Java
	•	📁 Project Manager for Java
	•	💚 Spring Boot Extension Pack
	•	🚀 Spring Boot Dashboard
	•	⚡ Thunder Client

GRACIAS AL PROFE DANIEL AGUDELO POR SU PACIENCIA Y EXPLICACION 

A continuacion las evidencias de su funcionamiento:

CREAR CLIENTE FUNCIONA EXCELENTE 

  

<img width="700" height="500" alt="Captura de pantalla 2025-10-24 130228" src="https://github.com/user-attachments/assets/1a8bb7d9-d4f4-4f43-aa8c-40a76154caf9" />

LISTAR TODOS LOS CLIENTES FUNCIONA EXCELENTE 

<img width="600" height="400" alt="Captura de pantalla 2025-10-24 130254" src="https://github.com/user-attachments/assets/0361334e-3a81-43e0-9908-83ac4b5f040e" />

BUSCAR CLIENTE POR SU ID TAMBIEN FUNCIONA 

<img width="600" height="400" alt="Captura de pantalla 2025-10-24 130116" src="https://github.com/user-attachments/assets/806eefb3-294a-473b-9282-9d6d9a06c349" />


💰 Crear Cuenta Corriente

POST /api/bank/customers/{id_cliente}/accounts

{
  "type": "CHECKING",
  "accountId": "101",
  "parameter": 500.0
}

💸 Crear Cuenta de Ahorros

POST /api/bank/customers/{id_cliente}/accounts

{
  "type": "SAVINGS",
  "accountId": "102",
  "parameter": 0.05
}

📥 Depositar Dinero

POST /api/bank/accounts/{id_cuenta}/deposit?amount={monto}

📤 Retirar Dinero

POST /api/bank/accounts/{id_cuenta}/withdraw?amount={monto}

🔁 Transferir entre Cuentas

POST /api/bank/accounts/{id_cuenta}/transfer

{
  "toAccountId": "102",
  "amount": 150
}

🧾 Consultar Transacciones

GET /api/bank/accounts/{id_cuenta}/transactions

Usando Swagger UI 

Prueba con Swagger

A CONTINUACION EVIDENCIAS DE FUNCIONAMIENTO 

1. CREAR CLIENTE 

<img width="1857" height="711" alt="Captura de pantalla 2025-10-29 164216" src="https://github.com/user-attachments/assets/f7ca8a9e-3239-419a-8544-1c8e10fc6b2a" />

2. LISTAR TODOS LOS CLIENTES 

<img width="1888" height="914" alt="Captura de pantalla 2025-10-29 165829" src="https://github.com/user-attachments/assets/1dd0b80e-7bff-400e-9021-010d0cfd3368" />

3. BUSCAR CLIENTE POR ID 

<img width="1877" height="915" alt="Captura de pantalla 2025-10-29 170131" src="https://github.com/user-attachments/assets/38f7194a-4760-4fa1-8401-29baa52bdfd5" />

4.CREAR CUENTA DE AHORROS O CORRIENTE 

<img width="1895" height="924" alt="Captura de pantalla 2025-10-29 164818" src="https://github.com/user-attachments/assets/ffd5500e-ce1e-482b-9692-2ab7fb786f7b" />

5. LISTAR CUENTAS DE UN CLIENTE 
<img width="1835" height="882" alt="Captura de pantalla 2025-10-29 170950" src="https://github.com/user-attachments/assets/4551768f-2e7e-496d-b7f1-7a0d0068b8b9" />

6. Consultar Cuenta especifica

<img width="1831" height="906" alt="Captura de pantalla 2025-10-29 171118" src="https://github.com/user-attachments/assets/e674bd64-2b19-4326-b996-fc6b219faee4" />

7. REALIZAR UN DEPOSITO 
<img width="1832" height="909" alt="Captura de pantalla 2025-10-29 171408" src="https://github.com/user-attachments/assets/6c130d00-523c-4d80-89a2-116d6b54ed41" />

8. REALIZAR UN RETIRO 
<img width="1833" height="915" alt="Captura de pantalla 2025-10-29 171525" src="https://github.com/user-attachments/assets/97c5c9bb-d3fe-4822-a0ad-9da38c0f3902" />

9. REALIZAR UNA TRANFERENCIA 

<img width="1600" height="595" alt="image" src="https://github.com/user-attachments/assets/235e082c-a23c-4bf1-a6e3-ab5d9987ed43" />

10. APLICAR INTERESES 
<img width="1823" height="846" alt="Captura de pantalla 2025-10-29 173358" src="https://github.com/user-attachments/assets/a9965d74-f29f-40ac-9ddd-a14f76de0de5" />



🧾 Créditos

💡 Proyecto desarrollado por Alejandro Benítez

📚 Parte del curso: Lógica de Solución de Problemas

📁 Repositorio: Logica-de-solucion-de-problemas







  

