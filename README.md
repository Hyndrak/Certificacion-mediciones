<h1 align="center">Certificación de Cableado Estructurado</h1>

<p align="center">
  <img src="https://raw.githubusercontent.com/TuAmigoPapilla/Imagenes/6fe59a19ce5dced8ef2c19d621ac215732c0c225/Portada.png" width="600">
</p>
  
## 📌 Descripción general 

<p align="justify">
Este repositorio contiene el registro y análisis de un laboratorio de pruebas sobre infraestructura de red UTP. Se realizaron mediciones en distintos puntos de red utilizando el certificador <strong>Net Chaser TNC950</strong>, con el objetivo de verificar el correcto funcionamiento del cableado y su cumplimiento con los estándares de instalación. Las pruebas incluyeron wiremap, longitud, SNR, detección de puertos activos y medición de PoE.
</p>
 

## 🎯 Objetivos 

- Ejecutar pruebas de certificación en puntos de red físicos. 

- Verificar cumplimiento de normas **TIA/EIA-568**. 

- Documentar resultados usando Git y Markdown. 

 

## 📂 Contenido 

- `parametros.md`: Definiciones técnicas. 

- `equipo.md`: Funciones de la certificadora. 

- `pruebas.md`: Resultados y análisis. 

 

## 🛠️ Desarrollo 

Se seleccionaron distintos puntos de red del laboratorio para realizar pruebas de certificación. 

 

Se verificó: 

- Estado del cableado 

- Conexiones correctas 

- Ausencia de interferencias 

- Conectividad 

 

## 📸 Fotos de cables usados 

Estas fotos demuestran el buen estado de los cables: 

<div align="center">
  <img src="https://raw.githubusercontent.com/TuAmigoPapilla/Imagenes/b1f3cf92b278b6242ff9c0a08ca141c8f8d7f23b/cables%20usados%20para%20la%20certificadora%201.png" width="500">
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/TuAmigoPapilla/Imagenes/b1f3cf92b278b6242ff9c0a08ca141c8f8d7f23b/cables%20usados%20para%20la%20certificadora%202.png" width="500">
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/TuAmigoPapilla/Imagenes/b1f3cf92b278b6242ff9c0a08ca141c8f8d7f23b/cables%20usados%20para%20la%20certificadora%203.png" width="500">
</div>

 

## 📸 Fotos de puntos certificados 

Se muestran los puntos analizados: 

 

<div align="center">
  <img src="https://raw.githubusercontent.com/TuAmigoPapilla/Imagenes/f94f84669410cf2efa1f6a0c3fd45318d2644029/Fotos%20de%20los%20puntos%20certificados%201.png" width="500">
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/TuAmigoPapilla/Imagenes/bcb26d8688210684c886e86fdc66f0b8dd9b4006/Fotos%20de%20los%20puntos%20certificados%202.png" width="500">
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/TuAmigoPapilla/Imagenes/f9c855d260033168a1c7ecce49f3c60d1ef95ffb/Fotos%20de%20los%20puntos%20certificados%204.png" width="500">
</div>

 

## 📊 Informe de revisión 

 

Datos obtenidos con tester: 

 

- **Toma N°12**: ❌ Par azul (pines 4–5) ruptura o corte a ~17.5 m - Posible Falla por ponchado defectuoso o deterioro.

- **Toma N°11**: ✅ Cable aprobado

- **Toma N°9**:❌ Falla por pares cruzados en el conector (error de ponchado). El cable físicamente está en buen estado, sin cortes ni abiertos — las longitudes son consistentes entre 19.7 y 20.6 m. Probable confusión entre estándar T568A y T568B.

 

## 🧩 Patch Panel 

 

![Patch Panel](https://raw.githubusercontent.com/TuAmigoPapilla/Imagenes/f9c855d260033168a1c7ecce49f3c60d1ef95ffb/Fotos%20de%20los%20patch%20panel.jpeg)

 

El patch panel es categoría **5e**, mientras que los cables son **Cat6**.   

Esto puede limitar el rendimiento del laboratorio. 

 

## 🔌 Switch 

 

![Panel Switch](https://raw.githubusercontent.com/TuAmigoPapilla/Imagenes/8f7b23a473220c229b9be615bbe6b8da6705ed7f/Panel%20Switch.png)
 

Indicadores: 

- **Naranja**: 10 Mbps 

- **Verde**: 100 Mbps 

- **Dúplex**: 

  - Encendido → Full Duplex 

  - Apagado → Half Duplex 

 

## 📖 Glosario Técnico 

 

- **Ancho de banda**: Cantidad de datos transmitidos. 

- **Atenuación**: Pérdida de señal. 

- **Diafonía**: Interferencia entre cables. 

- **RJ-45**: Conector de red. 

- **UTP**: Cable sin blindaje. 

- **STP/FTP**: Cable con blindaje. 

- **Latencia**: Tiempo de transmisión. 

- **EMI/RFI**: Interferencias eléctricas y de radio. 

- **Wiremap**: Mapa de cableado. 

- **PASS/FAIL**: Resultado de certificación. 

 

## ℹ️ Acerca de 
<p align="justify">
Información y fotos de certificación realizadas en clases.<br><br>
<strong>Institución:</strong> INACAP, La Serena<br>
<strong>Carrera:</strong> Ingeniería en Telecomunicaciones — 2° año<br>
<strong>Asignatura:</strong> Certificación de Cableado Estructurado<br>
<strong>Docente:</strong> Daniel Ruz<br>
<strong>Fecha:</strong> 16/04/2026<br><br>
<strong>Trabajo realizado por:</strong><br>
**Diego S. Rodriguez**<br>
Milovan Villalobos<br>
Juan Pablo Barraza
</p>
</p>
