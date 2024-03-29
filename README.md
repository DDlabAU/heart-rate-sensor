# Heart Rate Sensor

![](/assets/heart-rate-sensor.jpg)

I lab'et har vi to eksemplarer af [dette heart rate eller pulssensor kit fra Adafruit og Polar](https://www.adafruit.com/product/1077). Kit'et består af en pulsmåler der spændes om brystkassen og en trådløs modtager der forbindes til en arduino.

## Opsætning
Forbind den trådløse modtager som på billedet nedenfor. Den sorte ledning går til GND, den røde til 5V og den grønne går til et digital input, pin 7 hvis du bruger koden der ligger i dette repository. Hvis du har brug for hjælp til at orientere ledningerne i forhold til modtageren, kan du vende denne om og se at der ud for en af dens pins står skrevet "GND", hvor du skal forbinde den sorte ledning.

![](/assets/opsætning.jpg)


## Kode
Parallax har skrevet et stykke arduinokode, der let lader os komme i gang med at modtage værdier fra sensoren. Når du kører dette kode, oprettes der først forbindelse til pulssensoren og udskrives så ```"Beat"``` i serielmonitoren, hver gang sensoren registrerer en puls og sender denne til den trådløse modtager.
Vi har uploadet dette kode til mappen ```heart-rate-sensor-arduino```. Du kan også finde det på [parallax' egen hjemmeside](http://learn.parallax.com/KickStart) som  ```28048-Polar-HeartRate-Receiver-KickStart.zip```.
