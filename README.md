# conversorDeMonedas
💱 Conversor de Monedas en Java

Un conversor de monedas desarrollado en Java que obtiene las tasas de cambio en tiempo real desde una API externa y procesa los datos en formato JSON.

✨ Características

✅ Conversión entre múltiples monedas
✅ Datos de tipo de cambio en tiempo real
✅ Manejo de respuestas JSON
✅ Interfaz simple en consola

🛠️ Tecnologías usadas

☕ Java 8+

📦 Gson o org.json (para parsear JSON)

🌐 HttpURLConnection (o cliente HTTP)

⚙️ Instalación

Clonar el repositorio:

git clone https://github.com/tu-usuario/conversor-monedas-java.git
cd conversor-monedas-java


Compilar el proyecto:

javac -cp ".:libs/*" src/Main.java -d out


Ejecutar el programa:

java -cp ".:libs/*:out" Main

🔑 Configuración de la API

Regístrate en un proveedor de tipo de cambio como:

ExchangeRate API

CurrencyLayer

Obtén tu API Key.

Configúrala en config.properties:

API_URL=https://api.exchangerate.host/latest
API_KEY=tu_api_key

🖥️ Ejemplo de uso
Introduce la moneda base: USD
Introduce la moneda destino: EUR
Introduce el monto: 100

Resultado: 100 USD = 92.45 EUR

📂 Estructura del proyecto
conversor-monedas-java/
│── src/
│   ├── Main.java
│   ├── ApiService.java
│   ├── JsonParser.java
│── libs/              # Dependencias (ej. Gson o JSON)
│── config.properties
│── README.md

🤝 Contribuciones

¡Se aceptan contribuciones! Abre un issue o envía un pull request con mejoras.

📜 Licencia

Este proyecto está bajo la licencia MIT.
