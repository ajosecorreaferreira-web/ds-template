# CLAUDE.md — DS Template

> ⚠️ Este es el template base del DS Generator de Dusty.
> Antes de usar Claude Code en este proyecto, completa los archivos de docs/
> usando el DS Generator: claude.ai → Project "DS Generator"

## Stack técnico
- React + Vite + TypeScript
- Tailwind CSS v4
- shadcn/ui (Radix UI base)
- Lucide React (stroke: currentColor, strokeWidth: 1.5)
- Geist Variable (tipografía default — cambiar según cliente)
- Storybook v10 con addon-a11y

## Estado del proyecto
- [ ] Archivos docs/ completados con DS Generator
- [ ] Tokens personalizados en src/index.css
- [ ] Componentes adicionales instalados
- [ ] Storybook configurado
- [ ] Deploy en Vercel

## Documentación
Lee siempre estos archivos antes de generar cualquier cosa:
- Producto → docs/product.md
- Voz → docs/voice.md
- Audiencia → docs/audience.md
- Decisiones → docs/design-decisions.md
- No hacer → docs/dont-do.md
- Personalidad → docs/brand-personality.md
- Motion → docs/motion.md
- Sonido → docs/sound.md
- Referencias → docs/references.md

## Filosofía
- Filosofía atómica — construir siempre sobre componentes del DS
- Sin colores hardcodeados — siempre tokens CSS
- Border-radius: usar --radius siempre
- Accesibilidad WCAG AA mínimo
- Iconos: Lucide, stroke: currentColor, strokeWidth: 1.5
