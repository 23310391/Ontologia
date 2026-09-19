# README

## ¿Qué es una ontología?

En el contexto de la ingeniería del conocimiento, una **ontología** 
es una representación formal de un dominio de conocimiento: define 
los **conceptos** (clases) que existen en ese dominio, sus 
**propiedades** (atributos), y las **relaciones** que los conectan 
entre sí (jerarquías, composiciones, dependencias causales, etc.).

A diferencia de un simple glosario o mapa mental, una ontología 
busca capturar la estructura semántica del dominio: no solo *qué es* 
cada concepto, sino *cómo se relaciona* con los demás, permitiendo 
razonar sobre el conocimiento de forma sistemática.

## ¿Cómo funciona este sistema de notas?

Este repositorio de notas está organizado como una ontología en 
formato de **grafo de conocimiento**, donde:

- **Cada nota (nodo)** representa un concepto individual del dominio.
- **Los enlaces entre notas** (`[[dobles corchetes]]`) representan 
  las relaciones semánticas entre esos conceptos —pertenencia, 
  composición, causalidad, dependencia, entre otras.
- **El grafo resultante** permite visualizar de manera intuitiva 
  cómo se conecta el conocimiento del dominio, en lugar de leerlo 
  de forma lineal como en un documento tradicional.

## Estructura general

- Un nodo de **Inicio** funciona como punto de entrada, explicando 
  el propósito general del proyecto.
- Los demás nodos se van enlazando entre sí conforme se detallan 
  los conceptos, sus atributos y sus relaciones con otros nodos.
- Las relaciones no son solo visuales: buscan reflejar relaciones 
  ontológicas reales (por ejemplo, "es un tipo de", "es componente 
  de", "desencadena", "previene").

## Propósito de este README

Este documento sirve como guía metodológica: explica *cómo* está 
construida y *cómo navegarse* esta ontología, sin entrar en el 
contenido específico del dominio que se está modelando. Para el 
contexto particular de este proyecto, consulta el nodo [[Inicio]].