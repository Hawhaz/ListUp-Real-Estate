# ListUp Real Estate

![Next.js](https://img.shields.io/badge/Next.js-14-black?style=for-the-badge&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=for-the-badge&logo=typescript)
![tRPC](https://img.shields.io/badge/tRPC-10-blue?style=for-the-badge&logo=trpc)
![Prisma](https://img.shields.io/badge/Prisma-5-blue?style=for-the-badge&logo=prisma)
![Supabase](https://img.shields.io/badge/Supabase-latest-green?style=for-the-badge&logo=supabase)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3-blue?style=for-the-badge&logo=tailwindcss)

Una aplicación SaaS moderna para la gestión y publicación de propiedades inmobiliarias, construida con el T3 Stack (Next.js, TypeScript, tRPC, Prisma) y Supabase.

## 🚀 Características

- ✅ Generación automática de descripciones de propiedades con formato profesional
- ✅ Editor de texto avanzado con soporte para estilos Unicode
- ✅ Gestión de imágenes con vista previa y galería
- ✅ Autenticación y autorización con Supabase
- ✅ API tipada y segura con tRPC
- ✅ Diseño moderno y responsivo con TailwindCSS y shadcn/ui
- ✅ Modo oscuro exclusivo con estética premium

## 🛠️ Tecnologías

- **Frontend**: Next.js 14 con App Router, React 18, TailwindCSS
- **Backend**: tRPC, Prisma ORM, Supabase (PostgreSQL)
- **Autenticación**: Supabase Auth con Row Level Security (RLS)
- **Almacenamiento**: Supabase Storage para imágenes
- **Despliegue**: Vercel

## 📋 Requisitos previos

- Node.js 18.0.0 o superior
- npm o pnpm
- Cuenta en Supabase
- Variables de entorno configuradas (ver `.env.example`)

## 🚀 Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/Hawhaz/ListUp-Real-Estate.git
   cd ListUp-Real-Estate
   ```

2. Instala las dependencias:
   ```bash
   npm install
   # o
   pnpm install
   ```

3. Configura las variables de entorno:
   ```bash
   cp .env.example .env
   # Edita .env con tus credenciales
   ```

4. Inicia el servidor de desarrollo:
   ```bash
   npm run dev
   # o
   pnpm dev
   ```

5. Abre [http://localhost:3000](http://localhost:3000) en tu navegador.

## 🗄️ Estructura del proyecto

```
ListUp-Real-Estate/
├── prisma/               # Esquema de Prisma y migraciones
├── public/               # Archivos estáticos
├── src/
│   ├── app/              # Rutas de Next.js App Router
│   ├── components/       # Componentes React reutilizables
│   ├── hooks/            # Hooks personalizados
│   ├── lib/              # Utilidades y funciones auxiliares
│   ├── server/           # Lógica del servidor
│   ├── styles/           # Estilos globales
│   ├── trpc/             # Configuración de tRPC
│   └── types/            # Definiciones de tipos TypeScript
├── scripts/              # Scripts de utilidad
└── tests/                # Pruebas
```

## 📝 Scripts disponibles

- `npm run dev`: Inicia el servidor de desarrollo
- `npm run build`: Construye la aplicación para producción
- `npm run start`: Inicia la aplicación construida
- `npm run lint`: Ejecuta el linter
- `npm run test`: Ejecuta las pruebas

## 🔒 Seguridad

Este proyecto implementa:
- Autenticación segura con Supabase
- Políticas RLS para protección de datos
- Validación de entrada con Zod
- Tipado estricto con TypeScript

## 🤝 Contribución

Las contribuciones son bienvenidas. Por favor, sigue estos pasos:

1. Haz fork del repositorio
2. Crea una rama para tu característica (`git checkout -b feature/amazing-feature`)
3. Haz commit de tus cambios (`git commit -m 'Add some amazing feature'`)
4. Haz push a la rama (`git push origin feature/amazing-feature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está licenciado bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## 📞 Contacto

Para más información:
- 📲 6461322354
- 📩 ofidenciotirado@gmail.com
- 📸 Instagram: @Hawhaz

---

Desarrollado con ❤️ por el equipo de ListUp