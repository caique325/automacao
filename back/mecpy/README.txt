	$python -m virtualenv venv
		$pip install virtualenv
 		$pip freeze
		pip install Flask
	 1.1.1 ativando venv\Scripts\activate
	1.2


flask --app mecpy run --debug
flask --app mecpy run --debug
salvamento de pacotes : pip freeze>requirements.txt
instalar pacotes salvos : pip install -r requirements.txt
inicializando banco de dados : $ flask --app flaskr init-db



codigo micro:
/*
* https://circuits4you.com
* ESP32 Internal Temperature Sensor Example
*/

#ifdef __cplusplus
extern "C" {
#endif

uint8_t temprature_sens_read();

#ifdef __cplusplus
}
#endif

uint8_t temprature_sens_read();
//====================================================
// Setup
//====================================================
void setup() {
Serial.begin(115200);
}

//====================================================
// Loop
//====================================================
void loop() {
Serial.print("Temperature: ");

// Convert raw temperature in F to Celsius degrees
Serial.print((temprature_sens_read() - 32) / 1.8);
Serial.println(" C");
delay(1000);
}




-----Esp32------
link1: https://www.upesy.com/blogs/tutorials/esp32-pinout-reference-gpio-pins-ultimate-guide#

Adicional Board Manager
by tiago.curtinhas on 2023-12-04
https://espressif.github.io/arduino-esp32/package_esp32_index.json

Rede conexão
by tiago.curtinhas on 2023-12-11
rede: JAMES_NOTE

senha: 7vEL0769


ESP32 DHT Server: 192.168.137.25:5050
Exemplo webserver
by tiago.curtinhas on 2023-12-11
https://randomnerdtutorials.com/esp32-dht11-dht22-temperature-humidity-web-server-arduino-ide/

https://github.com/me-no-dev/ESPAsyncWebServer





