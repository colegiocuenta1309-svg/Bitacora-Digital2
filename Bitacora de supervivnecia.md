# Bitácora de supervivencia — CitasSalud+

**Estudiante:** Jeremy Sandigo
**Sección:** 11-6
**Fecha:** 27/08/26

## Escenario

Durante la ejecución de la prueba de performance (JMeter, listado de citas con
500 registros simulados — ver Anexo 1), el servidor principal de CitasSalud+
se satura y queda fuera de línea.

## 1. Identificación

<!-- ¿Cómo se detectó que el servidor había caído? ¿Qué señal o dato lo evidenció? -->

Verificando detenidamente los puertos del servidor para comprobar las anomalias

## 2. Contención

<!-- ¿Qué acción se tomó de inmediato para limitar el impacto? -->

Una medida de Seguridad que pueda restaurar el sistema sin perdida de datos


## 3. Recuperación

<!-- ¿Qué acción concreta permitió que la aplicación siguiera operando para
     citas de emergencia? Esta acción debe reflejarse en un commit de este
     repositorio con un mensaje descriptivo. -->


**Commit de recuperación:** (git revert abc123)

## 4. Aprendizaje / mejora

<!-- ¿Qué estrategia complementaria (respaldo, redundancia o monitoreo)
     hubiera anticipado este resultado, en relación con el criterio de
     performance del Anexo 1 (listado de citas en menos de 3 segundos)? -->

Un respaldo y monitoreo de todo el sistema en caso de un fallo grave
