# Historia Clínica Etológica UTE

Práctica interactiva de **Etología Animal** (Universidad UTE, Facultad de Medicina Veterinaria y Agronomía), temas 1.2 y 1.3.

## Qué hace

1. **Repaso del tema 1.2**: 8 preguntas sobre la visión científica del comportamiento (centrípetos, centrífugos y mixtos).
2. **Entrevista**: los estudiantes entrevistan a un tutor simulado por IA (6 casos: 3 caninos y 3 felinos).
3. **Redacción sin IA** de la historia clínica etológica en 8 pasos.
4. **Retroalimentación socrática** de la IA y **una revisión**.
5. **Entrega y nota sobre 10** (repaso 2 + historia clínica 8), con declaración de uso de IA.
6. **Panel docente**: importa los registros .txt de los grupos, verifica su integridad y exporta un CSV con una fila por estudiante.

Registro por grupo: paralelo, grupo e integrantes. Un intento por especie y por grupo.

## Nivel de uso de IA

IAA (uso acotado): la IA solo simula al tutor y da retroalimentación con preguntas. No redacta la historia ni clasifica las conductas.

## Cómo se usa

La versión funcional se usa como artefacto de Claude (claude.ai), porque el tutor simulado y la retroalimentación usan la cuenta de Claude de cada estudiante. Este repositorio guarda el código fuente; en GitHub Pages la página se muestra, pero la IA no funciona fuera de claude.ai.

## Tecnología

Un solo archivo `index.html` (HTML, CSS y JavaScript, sin dependencias), construido con Claude.
