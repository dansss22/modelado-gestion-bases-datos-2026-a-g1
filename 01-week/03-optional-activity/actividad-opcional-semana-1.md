# Actividad Opcional – Semana 1

## 1. ¿Qué criterios usaría para decidir cuándo migrar de archivos planos a un SGBD?

Para determinar si es necesario migrar de archivos planos a un Sistema de Gestión de Bases de Datos (SGBD), consideraría los siguientes criterios:

1. **Crecimiento del volumen de datos:**  
   Cuando el tamaño de los archivos comienza a dificultar su manejo, procesamiento o almacenamiento eficiente.

2. **Necesidad de consultas complejas:**  
   Si se requiere realizar búsquedas avanzadas, combinaciones de datos o reportes estructurados que los archivos planos no permiten manejar adecuadamente.

3. **Problemas de integridad o consistencia:**  
   Si existen registros duplicados, inconsistencias o errores provocados por la edición manual de los datos.

4. **Acceso concurrente por múltiples usuarios:**  
   Cuando varias personas necesitan consultar o modificar los datos al mismo tiempo, algo que los archivos planos no soportan sin riesgo de corrupción.

5. **Requerimientos de seguridad:**  
   Si es necesario implementar controles de acceso, autenticación o auditorías que permitan proteger la información.

6. **Escalabilidad del sistema:**  
   Cuando la aplicación debe crecer, integrar nuevos módulos o manejar un volumen mayor de información, lo cual resulta difícil de lograr con archivos planos.

7. **Facilidad de mantenimiento:**  
   Un SGBD ofrece respaldo, recuperación y administración automatizada, aspectos que no se pueden manejar adecuadamente con archivos planos.

---

## 2. ¿Qué tipo de SGBD (relacional o NoSQL) parece más adecuado para este contexto y por qué?

Para una migración desde archivos planos, el tipo de SGBD más adecuado generalmente es un **SGBD relacional**, debido a las siguientes razones:

- Los datos suelen estar estructurados y se pueden organizar en tablas con relaciones definidas.
- Los SGBD relacionales garantizan integridad y consistencia mediante restricciones, claves primarias y foráneas.
- Permiten realizar consultas complejas mediante SQL.
- Ofrecen herramientas maduras para la administración, seguridad y manejo de transacciones.
- Son ampliamente utilizados en entornos académicos y empresariales.

### ¿Cuándo se usaría NoSQL?
Un SGBD NoSQL sería adecuado solo si los datos fueran poco estructurados, altamente variables o crecieran de forma masiva, como en casos de documentos JSON, redes sociales, sensores o sistemas distribuidos.

### Conclusión  
En un proceso de migración tradicional desde archivos planos, la opción más apropiada es un **SGBD relacional**, ya que facilita la organización, el control y la integridad de los datos en un entorno estructurado.

