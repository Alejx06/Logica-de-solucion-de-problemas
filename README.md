🏦 App Bank – Proyecto de Lógica de Solución de Problemas

App Bank es una aplicación desarrollada en Java con Spring Boot y Maven, pensada para simular el funcionamiento de un banco.
Con esta app puedes crear clientes, abrir cuentas, hacer depósitos, retiros y transferencias fácilmente.
El proyecto fue hecho aplicando principios de programación orientada a objetos, arquitectura por capas y manejo de datos con JSON.

⸻

⚙️ Tecnologías Usadas
	•	☕ Java 17+
	•	🚀 Spring Boot
	•	🧱 Maven
	•	🧾 Springdoc OpenAPI (Swagger)
	•	⚡ Thunder Client (para pruebas de endpoints)

⸻

📂 Estructura del Proyecto
•controller
Controla las peticiones (endpoints) y conecta con el servicio.
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

📥 Descargar Visual Studio Code
📥 Descargar JDK

⸻

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






  

