# SuperGTool

**SuperGTool** - Herramienta de Pentesting con Interfaz Gráfica.

SuperGTool es una aplicación de pentesting desarrollada en VB.NET que proporciona una interfaz gráfica sencilla y accesible para realizar pruebas de seguridad en sistemas propios. La herramienta integra diversas funcionalidades enfocadas en la auditoría de sistemas, búsqueda de vulnerabilidades y análisis de seguridad.

## Características

- **Integración con SQLMap**: Proporcionamos una interfaz gráfica para SQLMap, una potente herramienta de terceros para la automatización de inyecciones SQL.
- **Búsqueda de subdominios**: Enumeración automática de subdominios para un dominio objetivo.
- **Escáner de puertos**: Identificación de puertos abiertos en el sistema objetivo.
- **Herramienta de codificación/decodificación**: Soporte para formatos como Base64, Hex, Unicode, entre otros.
- **Crackeo de hashes**: Incluye funciones para ataques de diccionario sobre hashes comunes como SHA1 y MD5.
- **Buscador de paneles de administración**: Localiza interfaces de administración expuestas en sitios web.
- **OSINT**: Herramienta para verificar si tu correo electrónico ha sido expuesto en filtraciones de bases de datos públicas.
- **Buscador de WAF**: Detecta firewalls de aplicaciones web (WAF) y prueba mecanismos de evasión.
- **Recopilación de información del servidor**: Obtiene detalles como versiones de software, cabeceras HTTP, entre otros.
- **Mini Shell para administración de archivos**: Herramienta básica para gestión de archivos en sistemas remotos.

> **Nota**: Uso SuperGTool está diseñado para fines educativos y de prueba en sistemas propios. Es importante usar esta herramienta únicamente en sistemas que te pertenezcan o sobre los cuales tienes autorización expresa para realizar pruebas de seguridad.

## Requisitos

- **Sistema Operativo**: Windows
- **Python 3.x**: Para ejecutar herramientas de terceros como SQLMap.
- **SQLMap**: Instalado y operativo en el sistema para aprovechar la interfaz gráfica de SuperGTool.
- **.NET Framework**: Preinstalado en la mayoría de los sistemas Windows modernos.

### Instalación

1. **Descargar e instalar SuperGTool**: [Enlace de descarga]
2. **Instalar Python**: Asegúrate de tener instalada la versión 3.x de Python desde [python.org](https://python.org).
3. **Configurar SQLMap**: Clona e instala SQLMap desde su repositorio oficial en [sqlmap.org](https://sqlmap.org).

## Descargo de Responsabilidad

SuperGTool ha sido desarrollado exclusivamente con fines educativos. El uso de esta herramienta en sistemas sin la debida autorización está prohibido y es ilegal. El desarrollador no se hace responsable del mal uso o daño causado por la misma. Asegúrate de utilizar esta herramienta respetando las leyes y regulaciones de tu país.

## Contribuciones

Contribuciones a este proyecto son bienvenidas. Si tienes ideas o mejoras que desees sugerir, por favor abre un issue o envía una pull request.



![1_inicio](https://github.com/user-attachments/assets/becb236f-746e-4aa3-b347-49e317d2d545)
![2_inicio](https://github.com/user-attachments/assets/18889a7b-5dc2-4182-a1c3-5a9da6052fc0)
![3_inicio](https://github.com/user-attachments/assets/de298a12-9073-4d89-9a8f-bdca0df6f222)
![4_inicio](https://github.com/user-attachments/assets/431c352d-014e-4b77-bf6f-f48db08c626c)
![5_sqlmap_todo](https://github.com/user-attachments/assets/2c7042a3-87c1-4eee-b17c-c68972d281be)
![6_sqlmap_basico](https://github.com/user-attachments/assets/f9eed6f4-86df-42d4-baa8-3becbdb66fac)
![7_sqlmap_documentacion](https://github.com/user-attachments/assets/08fb7a92-dfbd-4df7-a01b-fcd69502e55d)
![8_sqlmap_objetivo_url](https://github.com/user-attachments/assets/7a774e8b-7e9b-461f-982b-4c3e2fa45891)
![9_sqlmap_objetivo_archivo](https://github.com/user-attachments/assets/ed82c4ec-f38d-41d4-a21b-b74c20aca1c1)
![10_sqlmap_objetivo_googledork](https://github.com/user-attachments/assets/e54bb8de-80cb-4458-8985-6931705c29ae)
![11_sqlmap_objetivo_conexiondirecta](https://github.com/user-attachments/assets/718767a8-f131-4ba0-9b5a-2c6a20f5dc76)
![12_sqlmap_objetivo_log](https://github.com/user-attachments/assets/dd7a5c97-ed9c-41db-94f0-3ae838885130)
![13_sqlmap_objetivo_archivoini](https://github.com/user-attachments/assets/6f2037e1-d5cf-48b5-a5d2-ce640e2ab021)
![14_sqlmap_solicitud_metodoydatos](https://github.com/user-attachments/assets/0d97531d-7462-49bf-abdb-36629699b91f)
![15_sqlmap_solicitud_encabezados](https://github.com/user-attachments/assets/00b68198-332c-4892-ba95-d1de4d443163)
![16_sqlmap_solicitud_cookies](https://github.com/user-attachments/assets/a6c4b642-e232-4753-9e41-875ebd8914fc)
![17_sqlmap_solicitud_autenticacion](https://github.com/user-attachments/assets/f700c044-d78a-4f50-b3b8-da7386adfacd)
![18_sqlmap_solicitud_proxy_proxy](https://github.com/user-attachments/assets/83722ef0-26e1-48e7-92ff-f49b35fcc7ae)
![19_sqlmap_solicitud_proxy_tor](https://github.com/user-attachments/assets/5ea58ddd-a41d-45f0-9fcd-60fa6e9c55e9)
![20_sqlmap_solicitud_errorytiempo](https://github.com/user-attachments/assets/305210fe-cb6f-4fe6-b12f-7afc2a532936)
![21_sqlmap_solicitud_seguridadymanipulacion](https://github.com/user-attachments/assets/f60287c3-4699-44f5-9935-952ff39e178f)
![22_sqlmap_solicitud_seguridadadicional](https://github.com/user-attachments/assets/27efa077-5114-4984-b2ec-a5484dd9802e)
![23_sqlmap_solicitud_manipulacionavanzada](https://github.com/user-attachments/assets/99bb08ec-de4c-48d9-ba2c-8d8a7b8ed0a9)
![24_sqlmap_optimizacion](https://github.com/user-attachments/assets/a59ecf9e-a540-46e8-a4b0-7a9ee1ac147f)
![25_sqlmap_inyeccion_prametrosyfiltrado](https://github.com/user-attachments/assets/15d7dd7d-4578-47fc-80d7-b4c203ab9a8d)
![26_sqlmap_inyeccion_basededatosysistema](https://github.com/user-attachments/assets/c293af30-74c8-44f9-a330-5fb5e660e0fa)
![27_sqlmap_inyeccion_validacionesymanipulacion](https://github.com/user-attachments/assets/5dd27c0d-d581-4c4a-95f8-613c9ec01b43)
![28_sqlmap_inyeccion_ajustesdeconsultas](https://github.com/user-attachments/assets/b9e02cfe-dae5-4e7f-aa48-12c418e99607)
![29_sqlmap_deteccion](https://github.com/user-attachments/assets/bf46120b-9c38-46c7-b191-882ad869ee9c)
![30_sqlmap_tecnicas](https://github.com/user-attachments/assets/d259d409-28dc-4259-a24c-f364787697a7)
![31_sqlmap_huella](https://github.com/user-attachments/assets/75154b78-ba33-4dfa-b432-2a795ed52273)
![32_sqlmap_enumeracion_infogeneral](https://github.com/user-attachments/assets/3506ca0f-c0b1-4dd4-87c3-460c3fbc190d)
![33_sqlmap_enumeracion_usuariosyprivilegios](https://github.com/user-attachments/assets/df185c8c-373e-43c3-ae0d-894b83c954d7)
![34_sqlmap_enumeracion_basestablascolumnas](https://github.com/user-attachments/assets/a06370b9-2879-4fc6-9b74-b11a912fc947)
![35_sqlmap_enumeracion_dump](https://github.com/user-attachments/assets/1f7ea5c6-1073-47ba-87a7-40f9ab04ea61)
![36_sqlmap_enumeracion_busquedayexclusion](https://github.com/user-attachments/assets/e404c613-adbc-4fc6-aa34-27e525ab59bc)
![37_sqlmap_enumeracion_comentariosyconsultassql](https://github.com/user-attachments/assets/2fc0b07a-ecb9-437f-a3ce-fafa8998da8a)
![38_sqlmap_enumeracion_opcioneavanzadas](https://github.com/user-attachments/assets/ef8f59b3-3bf5-4604-8d72-bb76c5bcf69a)
![39_sqlmap_fuerzabruta](https://github.com/user-attachments/assets/a8f5b27d-b072-4b9d-a7df-aa79abd440f6)
![40_sqlmap_funcionesusuario](https://github.com/user-attachments/assets/ed34648f-923a-4b17-94e4-4f89e4275250)
![41_sqlmap_archivos_leer](https://github.com/user-attachments/assets/37eeb114-dac6-4943-b8de-810815e98977)
![42_sqlmap_archivos_escribir](https://github.com/user-attachments/assets/e67de81b-c275-467b-aa27-03d871f7884e)
![43_sqlmap_archivos_escribir_shell](https://github.com/user-attachments/assets/732b68f9-0f60-477f-ad79-5355d2845eef)
![44_sqlmap_sistema](https://github.com/user-attachments/assets/44245e23-9cc9-4318-9c18-c17264a182aa)
![45_sqlmap_registro_leer](https://github.com/user-attachments/assets/0486af8d-058c-472b-a703-83252dc7c11b)
![46_sqlmap_registro_escribir](https://github.com/user-attachments/assets/9979ca5d-c126-4939-82c9-d76633116338)
![47_sqlmap_registro_borrar](https://github.com/user-attachments/assets/8f5e6ca5-931c-441d-b4fd-a835fb2d1333)
![48_sqlmap_general_sesionesyregistro](https://github.com/user-attachments/assets/b170337a-aab4-4f82-9a78-ca05a239d0f5)
![49_sqlmap_general_opcionesentradaysalida](https://github.com/user-attachments/assets/158dece5-4eda-4149-8a76-754a47f9472e)
![50_sqlmap_general_automatizacion](https://github.com/user-attachments/assets/9e8ff411-eb3d-4acd-bd63-b365bf37580f)
![51_sqlmap_general_rastreoyanalisisweb](https://github.com/user-attachments/assets/a550bb47-7087-48d3-9f01-5c1ffb248bb8)
![52_sqlmap_diagnosticoyanalisisdeerrores](https://github.com/user-attachments/assets/db23a73b-26f5-4281-9bc4-1c5f1ab85b03)
![53_sqlmap_general_seguridad_preyproprocesamiento](https://github.com/user-attachments/assets/f632b71e-8955-4982-89fe-b962296861bd)
![54_sqlmap_general_avanzado](https://github.com/user-attachments/assets/97dcf412-f3a1-45b8-a415-828de3c3438c)
![55_sqlmap_general_limpiezayreparacion](https://github.com/user-attachments/assets/4f446b83-7e39-4778-ae0d-4c575a7dc987)
![56_sqlmap_variado](https://github.com/user-attachments/assets/d6ce2f88-340b-48ab-8dd4-f756b9872aae)
![57_dumparchivos](https://github.com/user-attachments/assets/3fe20486-2267-4d85-a6ab-753143a6a757)
![58_crack_fuerzabruta](https://github.com/user-attachments/assets/e8e8b7cf-2265-4427-b223-5c422404a6d2)
![59_crack_diccionario](https://github.com/user-attachments/assets/c8c31648-61f1-4e8d-92aa-9fe70520aad9)
![60_subdominios](https://github.com/user-attachments/assets/832701f7-07d6-45d3-82ef-140b8a71e753)
![61_buscarpaneladmin](https://github.com/user-attachments/assets/d87b21a4-f482-422c-b0ef-d0520c19ba01)
![62_escanearpuertos](https://github.com/user-attachments/assets/eb371b62-f91d-4d77-8afc-e707bc2a4600)
![63_osint](https://github.com/user-attachments/assets/d7ae1945-0a22-46a2-8a69-6553b1989b9f)
![64_waf](https://github.com/user-attachments/assets/fb3ba4ce-c749-4bad-89d4-a89b63e7c62a)
![65_configuracion_basedatos](https://github.com/user-attachments/assets/e0d3ca75-f986-4b09-b1dd-052e3f366f29)
![66_configuracion_sqlmap](https://github.com/user-attachments/assets/c1570d71-61a9-4f46-8b44-0c18ef93fb3f)
![67_donaciones](https://github.com/user-attachments/assets/5d0675ab-d776-4e3c-bd0d-9fc906dca2bc)





