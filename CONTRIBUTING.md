# Guía de Contribución

¡Gracias por tu interés en contribuir a ListUp Real Estate! Este documento proporciona las pautas y los pasos a seguir para contribuir al proyecto.

## Código de Conducta

Al participar en este proyecto, te comprometes a mantener un ambiente respetuoso y colaborativo. Esperamos que todos los contribuyentes:

- Sean respetuosos y considerados con los demás
- Acepten críticas constructivas
- Se centren en lo que es mejor para la comunidad
- Muestren empatía hacia otros miembros de la comunidad

## ¿Cómo puedo contribuir?

### Reportando Bugs

Los bugs se rastrean como issues en GitHub. Cuando reportes un bug, por favor incluye:

- Un título claro y descriptivo
- Pasos detallados para reproducir el problema
- Comportamiento esperado vs. comportamiento actual
- Capturas de pantalla si es posible
- Información sobre tu entorno (navegador, sistema operativo, etc.)

### Sugiriendo Mejoras

Las sugerencias de mejora también se rastrean como issues en GitHub. Cuando sugieras una mejora, por favor incluye:

- Un título claro y descriptivo
- Una descripción detallada de la mejora propuesta
- Cualquier contexto o capturas de pantalla relevantes

### Pull Requests

1. Asegúrate de que tu código sigue las convenciones de estilo del proyecto
2. Actualiza el README.md con detalles de los cambios si es necesario
3. El PR será revisado por los mantenedores del proyecto
4. Asegúrate de que todas las pruebas pasen

## Proceso de Desarrollo

1. Haz fork del repositorio
2. Crea una rama para tu característica (`git checkout -b feature/amazing-feature`)
3. Haz commit de tus cambios (`git commit -m 'Add some amazing feature'`)
4. Haz push a la rama (`git push origin feature/amazing-feature`)
5. Abre un Pull Request

## Convenciones de Estilo

### Commits

Usamos [Conventional Commits](https://www.conventionalcommits.org/) para los mensajes de commit:

```
<tipo>(<alcance opcional>): <descripción>

[cuerpo opcional]

[pie opcional]
```

Tipos comunes:
- feat: Nueva característica
- fix: Corrección de bug
- docs: Cambios en la documentación
- style: Cambios que no afectan el significado del código
- refactor: Cambio de código que no corrige un bug ni añade una característica
- test: Añadir o corregir pruebas
- chore: Cambios en el proceso de build o herramientas auxiliares

### Código

- Usamos ESLint y Prettier para mantener la consistencia del código
- El código TypeScript debe ser tipado estrictamente
- Los componentes React deben ser funcionales y usar hooks
- Seguimos los principios de arquitectura limpia y SOLID

## Recursos Adicionales

- [Documentación de Next.js](https://nextjs.org/docs)
- [Documentación de tRPC](https://trpc.io/docs)
- [Documentación de Prisma](https://www.prisma.io/docs)
- [Documentación de Supabase](https://supabase.io/docs)

¡Gracias por contribuir a ListUp Real Estate!