# Bitácora de supervivencia — TrámiteFácil+

**Estudiante:** Jeremy Sandigo
**Sección:** 11-6
**Fecha:** 28/08/26

## Escenario

Durante la ejecución de la prueba de performance (JMeter, listado de trámites
con 800 registros simulados — ver Anexo 1), el servidor principal de
TrámiteFácil+ se satura y queda fuera de línea.

## 1. Identificación

<!-- ¿Cómo se detectó que el servidor había caído? ¿Qué señal o dato lo evidenció? -->

Verificando detenidamente los puertos del servidor para comprobar las anomalias

## 2. Contención

<!-- ¿Qué acción se tomó de inmediato para limitar el impacto? -->

Una medida de Seguridad que pueda restaurar el sistema sin perdida de datos

## 3. Recuperación

<!-- ¿Qué acción concreta permitió que el sistema siguiera operando para
     trámites urgentes? Esta acción debe reflejarse en un commit de este
     repositorio con un mensaje descriptivo. -->



**Commit de recuperación:** (git revert abc123)

## 4. Aprendizaje / mejora

<!-- ¿Qué estrategia complementaria (respaldo, redundancia o monitoreo)
     hubiera anticipado este resultado, en relación con el criterio de
     performance del Anexo 1 (listado de trámites en menos de 4 segundos)? -->

