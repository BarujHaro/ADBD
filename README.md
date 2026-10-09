# Administración de Bases de Datos 🗄️

Este repositorio contiene el conjunto de prácticas desarrolladas durante el curso de **Administración de Bases de Datos**, enfocadas principalmente en el sistema de gestión **Oracle Database** y la base de datos NoSQL **MongoDB**.

## 📌 Contenido del Repositorio

El material está organizado en prácticas guiadas que cubren desde la arquitectura interna y la gestión de usuarios, hasta estrategias avanzadas de respaldos, recuperación ante desastres y auditoría.

### 🏛️ Fundamentos y Estructura en Oracle
*   **Práctica 2: Creación de Usuarios y Tablas**
    *   Gestión de esquemas, asignación de roles, privilegios de sistema/objetos y definición del DDL inicial.
*   **Práctica 11: Almacenamiento**
    *   Configuración y administración del almacenamiento físico y lógico (Tablespaces, Datafiles, segmentos y extensiones).

### 🛡️ Seguridad, Auditoría y Consultas Avanzadas
*   **Práctica 8: Consulta Distribuida**
    *   Configuración de conexiones entre bases de datos remotas mediante `Database Links` (DBLinks).
*   **Práctica 12: Seguridad**
    *   Implementación de políticas de acceso, control de contraseñas y perfiles de usuario.
*   **Práctica 13: Auditoría en Oracle**
    *   Monitoreo de actividades del sistema, rastreo de sentencias DML/DDL y uso de la característica de auditoría estándar.

### 💾 Estrategias de Respaldo y Recuperación (Backup & Recovery)
*   **Práctica 3: Respaldo Frío o Consistente**
    *   Copias de seguridad del sistema realizando un apagado controlado de la instancia (`SHUTDOWN`).
*   **Práctica 4: Recuperación Respaldo en Frío**
    *   Restauración de la base de datos a partir de archivos físicos en frío ante una pérdida de datos.
*   **Práctica 5: Respaldo Inconsistente o en Caliente**
    *   Configuración del modo `ARCHIVELOG` para respaldar la base de datos mientras se encuentra en producción y activa.
*   **Práctica 6: Recuperación de Respaldo en Caliente**
    *   Procedimientos de recuperación aplicando los archivos *Archive Logs* y *Redo Logs* activos.
*   **Práctica 7: Respaldo y Recuperación Lógica**
    *   Uso de utilidades de exportación e importación de datos (Data Pump: `expdp` e `impdp`).

### 🛠️ Herramientas y Entornos de Desarrollo
*   **Práctica 14: IDEs para BDs y PostgreSQL**
    *   Evaluación e instalación de entornos de desarrollo integrados (como DBeaver o pgAdmin) y primeros pasos en el ecosistema PostgreSQL.

### 📊 Bases de Datos NoSQL (MongoDB)
*   **Práctica 15: Instalación y Creación de Usuarios en MongoDB**
    *   Despliegue del motor de base de datos orientado a documentos, configuración del demonio `mongod` y gestión de roles/usuarios.
*   **Práctica 16: Respaldo y Recuperación en MongoDB**
    *   Administración de copias de seguridad lógicas utilizando las herramientas nativas `mongodump` y `mongorestore`.

---

## 🛠️ Tecnologías Utilizadas
*   **RDBMS:** Oracle Database (Modo Arquitectura Multitenant / Standard)
*   **NoSQL:** MongoDB