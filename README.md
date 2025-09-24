# Pruebas de regresión de Urban Routes  

## 📌 Descripción  
Urban Routes es una aplicación que permite crear rutas y calcular la duración y precio de un viaje en diferentes tipos de transporte (auto, a pie, taxi, bicicleta, scooter o auto compartido).  

En este proyecto realicé **pruebas de regresión manuales** sobre la aplicación, validando funcionalidades críticas como:  
- Campos de búsqueda ("Desde" y "Hasta")  
- Renderizado de pines en el mapa  
- Modos de visualización (Relieve, Satélite, Street View)  
- Interacción con la interfaz (mapa, zoom, pantalla completa)  

El objetivo fue garantizar que los cambios recientes en la aplicación no afectaran las funciones ya existentes y detectar errores antes de llegar a los usuarios finales.  

---

## 🛠️ Stack y herramientas utilizadas  
- **Metodología de pruebas:** Pruebas de regresión, pruebas funcionales, pruebas exploratorias  
- **Gestión de errores:** Jira  
- **Documentación de casos de prueba:** Google Sheets  
- **Entorno de prueba:** Urban Routes (Web)  

---

## 📊 Resultados  

- **Total de casos de prueba ejecutados:** 24  
- **Estado:**  
  - ✅ 20 casos **Aprobados**  
  - ❌ 4 casos **No aprobados**  

### 🐞 Errores encontrados (Bug Reports)  

| ID   | Título | Severidad | Estado |
|------|---------|-----------|--------|
| BR1  | Fallo en búsqueda de estaciones en el campo *Hasta* | 🔴 Crítico | Abierto |
| BR2  | Pin no aparece tras ingresar dirección en el campo *Desde* | 🔴 Crítico | Abierto |
| BR3  | Pin no aparece tras ingresar dirección en el campo *Hasta* | 🔴 Crítico | Abierto |
| BR4  | No se muestra información al hacer clic en el logotipo de la aplicación | 🟡 Trivial | Abierto |

📌 **Resumen:** La mayoría de las funcionalidades principales del mapa y de la interfaz se comportaron según lo esperado. Sin embargo, se detectaron **3 bugs críticos** relacionados con el renderizado de direcciones y 1 bug menor en la visualización de información.  

---

## 📎 Documentación  
📄 [[Casos de prueba y reportes en Google Sheets](https://docs.google.com/spreadsheets/d/1RFdBOuZ6npiwrX-Y-SOSJYBWljd3I2Ie/edit?usp=sharing&ouid=112657294087284506568&rtpof=true&sd=true)](#)  

---

✍️ **Autora:** Monica Vasco Dominguez – QA Engineer  
