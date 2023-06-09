#include <WiFi.h>
//#include <Arduino.h> 
//Delete comment to enable if use in other programming language

const char* ssid = "WiFiName";
const char* password = "WiFiPassword";

void setup(){
    Serial.begin(115200);
    delay(1000);

    WiFi.begin(ssid, password);
    Serial.println("\nConnecting");

    while(WiFi.status() != WL_CONNECTED){
        Serial.print(".");
        delay(100);
    }

    Serial.println("\n WiFi Connected");
    Serial.print("IP Address: ");
    Serial.println(WiFi.localIP());
}

void loop(){}