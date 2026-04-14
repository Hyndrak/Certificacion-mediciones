# 🧰 Equipo Utilizado: Certificadora de Red 

 

## 🔧 Funciones principales 

 

### ✔ Auto-Test 

Ejecuta automáticamente todas las pruebas necesarias según la categoría del cable (Cat 5e, Cat 6 etc), entregando un resultado **PASS o FAIL**. 

![Auto Test](https://raw.githubusercontent.com/TuAmigoPapilla/Imagenes/31e1d5db30c3dfa69ce0901ffe3f96ebadc559f0/Auto%20Test.png)


--- 

 

### ⚡ Verificación de PoE 

Permite comprobar si el cable puede suministrar energía a dispositivos (Power over Ethernet) y si el voltaje es adecuado. 

![PoE Test](https://raw.githubusercontent.com/TuAmigoPapilla/Imagenes/31e1d5db30c3dfa69ce0901ffe3f96ebadc559f0/PoE%20test.jpg)

 Parámetros:

- **Mode A:** La energía viaja por los pares de datos (pines 1-2 y 3-6), el método más común
Estándar 802.3af: Versión básica de PoE, suficiente para APs, cámaras y teléfonos IP
Potencia: 12.95W entregados — dentro del límite de 802.3af (máx 15.4W)
50.1V sin carga: Voltaje en reposo, sin dispositivo consumiendo
48.5V con carga: Voltaje real bajo demanda — la caída es mínima, indica buena fuente PoE

--- 


 ### 🔎 Port Discovery

La certificadora detectó un puerto activo en el switch y negoció sus capacidades automáticamente.
 
![Port Discovery](https://raw.githubusercontent.com/TuAmigoPapilla/Imagenes/31e1d5db30c3dfa69ce0901ffe3f96ebadc559f0/Port%20Discovery.jpg)

Parámetros:

- **PoE:** Sin alimentación eléctrica por el cable
- **MDI/MDI-X automático:** No importa si el cable es directo o cruzado, el puerto se adapta solo
- **Autonegociación:** El switch y el tester acuerdan velocidad/dúplex automáticamente
- **100Base-TX / Full Duplex:** Enlace a 100 Mbps, enviando y recibiendo al mismo tiempo
- **Flow Control:** Puede pausar la transmisión para evitar pérdida de paquetes
- **SNR pares 1 y 2:** ~29 dB, buena relación señal/ruido — pares 3 y 4 en 0 porque 100Base-TX solo usa 2 pares


--- 


### 🌐 Prueba de DHCP/Ping 

Verifica conectividad lógica, permitiendo comprobar si el equipo obtiene una IP automáticamente y si existe comunicación en la red. 

 ![DHCP Ping](https://raw.githubusercontent.com/TuAmigoPapilla/Imagenes/31e1d5db30c3dfa69ce0901ffe3f96ebadc559f0/Prueba%20de%20DHCP%20Ping.jpg)
 

--- 

 
### 📏 Localizador de fallas (TDR) 

Detecta la ubicación exacta de fallas en el cable, indicando la distancia donde ocurre un corte o problema. 

![Localizador](https://raw.githubusercontent.com/TuAmigoPapilla/Imagenes/d568c0d0fc3e2b155c667793d8cb383203983de5/Localizador%20de%20fallas.png)


--- 


## ⚙️ Configuración del Equipo 

 

- **Tipo de cable:** UTP   

- **Categoría:** Cat 5e   

- **Estándar:** TIA/EIA-568B
