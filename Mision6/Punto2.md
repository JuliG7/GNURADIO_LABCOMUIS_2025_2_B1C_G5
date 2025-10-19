Despues de crear el audio.wav se construyó la estructura de la señal que modula l aportadora de RF.
Se cargo el archivo de audio estéreo en GNU Radio.
Generamos la señal MPX con los respectivos bloques como se muestra en la imagen.
<img width="1600" height="858" alt="image" src="https://github.com/user-attachments/assets/de41c439-5d4a-4962-b4e8-18021788f69b" />
Incluye la señal L+R generando el tono piloto de 19kHz, laseñal de L-R  modulando una subportadora de 30kHz mediante AM
Se sumaron las tres señales obteniendo la señal MPX. 
<img width="1600" height="858" alt="image" src="https://github.com/user-attachments/assets/f810c606-5dd0-4ef2-94bd-c2e065997013" />
Despues de esto verificamos la usma de las trese señales en el analizador de espectro, se verifico la ubicación de cada una de las señales y tambien su amplitud como se muetra en la imagen
<img width="1000" height="547" alt="image" src="https://github.com/user-attachments/assets/2013ffb2-6034-4fe4-b8a8-13b894c11712" />
Verificamos la pocision del tono piloto 18.95 kHz, la señal L+R ubicada en 98.69MHz y la señal L-R ubicada en 38.24 KHz, asi como sus respectivas amplitudes relativas
