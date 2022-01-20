# Vaja8-I2C-ADS1115-STM32F0

V kategoriji Connectivity izbereva in omogočiva I2C komunikacijo.Obarvata se pina PB6 in PB7. Naša razvojna plošča omogoča 2 različni I2C komunikacij.
Za povezabo med ADS1115 modulom in STM32F0 ploščico sva izbrala naslednje pine:
 SCL(ADS1115)-PB6(STM32F0), SDA(ADS1115)-PB7(STM32F0), ADDR(ADS1115)-GND(STM32F0),ALRT(ADS1115)-ni povezan,VDD(ADS1115)-3V(STM32F0).  
 
 V Parameter  Settings protokola  I2C sva spremenila Speed  Mode na Fast.Sedaj frekvenca znaša 8MHz.
 
 KOMENTAR NA DELOVANJE:
 Naloge nama žal ni uspelo narediti, tako, kot so navodila to zahtevala. Naredila sva vse tako kot je pisalo v navodilih ampak, komunikacije nama nikakor ni uspelo vspostaviti. Koda in nastavitve periferije so pravile, tako da dopuščava da je napaka nekje v samem vezju.(Ne)Delovanje je rezvidno iz priloženega videoposnetka
