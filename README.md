# Crisman Andrey Mena Gómez

**Director de Tecnologías de Información** · Colegio de Profesionales en Informática y Computación (CPIC), Costa Rica
**Socio** · [WebCom Costa Rica](https://webcomcr.com) — departamento de investigación en ciberseguridad y gobernanza

[![webcomcr.com](https://img.shields.io/badge/webcomcr.com-sitio-4D5BFF)](https://webcomcr.com) [![Test de Exposición](https://img.shields.io/badge/Test_de_Exposici%C3%B3n-NIST_CSF_2.0-E30613)](https://webcomcr.com/test) [![Quién está detrás](https://img.shields.io/badge/perfil-%2Fcrisman-2BD9A8)](https://webcomcr.com/crisman)

Desarrollador web desde los 15 años. Profesional desde 2015. En los últimos años, mi carrera giró de escribir código a construir equipos y liderar en innovación tecnológica.

---

## Lo que hago hoy

Dirijo el departamento de TI del CPIC — el colegio profesional que agremia a los informáticos de Costa Rica. Lidero un equipo multidisciplinario de 6 personas (desarrollo backend/frontend, procesos, redes, soporte) y coordino con áreas como Comunicación, Dirección Ejecutiva y Servicios.

https://github.com/cloorus es mi trabajo mas reciente, una IA automona que maneja mis workflows de desarrollo.

**Algunas cosas que hemos logrado:**

- Migración de ERP legacy (Softland/SQL Server) a Odoo 19 Enterprise, incluyendo sincronización bidireccional en tiempo real con stored procedures y XML-RPC
- Implementación de CRM 
- Diseño de arquitectura de observabilidad y arquitectura basada en datos y seguridad
- Integración de IA como herramienta operativa del departamento — no como experimento, sino como parte del flujo diario
- Direccion de desarrollo de proyectos internos donde se usa IA de forma productiva
- Pipeline de firma digital certificada BCCR para Odoo (en desarrollo)
- 78+ proyectos gestionados, 46 completados, 225-325 tickets/mes con respuesta promedio de 5-10 minutos

## WebCom Costa Rica y la fábrica

Cuando no estoy en la dirección de TI, colaboro como socio en el **departamento de investigación de WebCom Costa Rica**: ciberseguridad y gobernanza para organizaciones que necesitan responder con números. La regla de la casa: *si no lo corremos nosotros, no te lo vendemos.*

Y para construir, uso **la fábrica**: un método donde **el humano define y decide, y los agentes de IA ejecutan detrás de compuertas**. Nada entra a `main` sin CI, sin revisión del dueño del código y sin evidencia. Un ítem se cierra con evidencia, no con ejecución.

**Lo que salió de la fábrica en un fin de semana (octubre 2026):**

- [webcomcr.com](https://webcomcr.com): sitio en Next.js 16 con CI/CD de punta a punta. Cada merge se construye fuera del servidor, se despliega con una llave de comando forzado y vuelve atrás sola si no pasa el chequeo de salud
- [Test de Exposición](https://webcomcr.com/test): autoevaluación de ciberseguridad basada en **NIST CSF 2.0** y **CIS Controls v8**, con radar por función e informe por correo
- Tablero de **indicadores de gestión con contrato** (numerador, denominador, ventana, fuente y custodio): un KPI sin contrato es una opinión
- Accesibilidad **WCAG AA verificada** (axe-core sin violaciones), SEO y visibilidad en IA (`llms.txt`, JSON-LD)
- Entregabilidad de correo resuelta: migración de DNS a Cloudflare con espejo verificado registro por registro, relay de envío y SPF, DKIM y DMARC alineados
- Endurecimiento de un servidor de producción siguiendo una **ruta de remediación con expediente y bitácora**: SSH solo con llave, servicios internos fuera de internet, fail2ban, 2FA y cierre de un incidente con análisis forense
- Almacenamiento propio con **Nextcloud** para reemplazar una nube de terceros

## Stack actual

```
Gestión:       Odoo 19 · Proyectos · RRHH · CRM · Knowledge · E-learning
Frontend:      Next.js 16 · React 19 · TypeScript · Tailwind CSS 4 · Vitest
Backend:       Python · Node.js · PHP (Yii2) · SQL Server · PostgreSQL · MySQL
Infra:         DigitalOcean · Azure · Cloudflare (DNS, Zero Trust, Email) · Docker Compose · Nginx
Seguridad:     NIST CSF 2.0 · CIS Controls v8 · fail2ban · SSH hardening · SPF/DKIM/DMARC · WCAG 2.2
CI/CD:         GitHub Actions · GHCR · despliegue con rollback verificado por salud
IA aplicada:   Claude Code · Pi · OpenClaw · MCP · agentes con compuertas y evidencia
Integraciones: XML-RPC · REST APIs · Deepgram · ElevenLabs
```

## Trayectoria

| Etapa | Rol | Contexto |
|---------|-----|----------|
| Desde los 15 años | Desarrollador autodidacta | PHP, MySQL, proyectos propios |
| IGD Online (5 años) | Desarrollador web profesional | Mi primer trabajo al salir de la universidad |
| En paralelo, los últimos 3 años en IGD | Cofundador | Mi primera empresa, con compañeros de la universidad; la cerramos al terminar esa etapa |
| Emprendimiento con mi hermana | Cofundador | Sistemas comerciales para empresas retail; el camino que me llevó a WebCom al salir de IGD |
| WebCom Costa Rica | Desarrollador → **socio** | Sistemas a medida, Yii2, arquitecturas PHP; hoy en el departamento de investigación |
| 2023–presente | Director de TI | CPIC — gestión de equipos, transformación digital, IA institucional |

## En qué estoy trabajando

- Sincronización ERP↔Odoo con procedimientos almacenados y módulos custom
- Integración de firma digital certificada (BCCR) en flujos Odoo
- Observabilidad y ciberseguridad institucional
- Diseño de cursos e-learning sobre IA y ciberseguridad para profesionales
- Un artículo académico sobre LLM + MCP para gobernanza de TI (coautoría, IEEE)
- La fábrica: desarrollo de software con humanos y agentes, con compuertas verificables
- WebCom Costa Rica: medición de exposición, gobernanza con indicadores y almacenamiento propio

## Lo que me importa

Creo que la tecnología tiene que resolver problemas reales, no crear demos bonitas. Me interesa la intersección entre gestión de TI, ética profesional e inteligencia artificial — especialmente en contextos donde los recursos son limitados y las decisiones tienen impacto institucional.

Trabajo en un país donde la transformación digital del sector público avanza lento. Mi apuesta es demostrar que un equipo pequeño, bien coordinado, puede mover una institución entera. No con presupuesto, sino con criterio.

## Áreas de mejora (porque nadie es perfecto)

La comunicación ha sido mi punto más bajo en evaluaciones de desempeño recientes — tanto de mi jefe directo como de mi equipo. Tiendo a asumir que el contexto es obvio, y no siempre lo traduzco bien para audiencias no técnicas. Es algo en lo que trabajo activamente.

También reconozco que la delegación no me sale natural. Estoy aprendiendo a soltar proyectos y confiar en que el equipo puede tomar decisiones sin que yo esté encima.

## Contacto

- 📧 crisman.mena@cpic.or.cr
- 🏢 [CPIC Costa Rica](https://www.cpic.or.cr)
- 🌐 [webcomcr.com](https://webcomcr.com) · [quién está detrás](https://webcomcr.com/crisman)
- 📍 San José, Costa Rica

---

*Última actualización: octubre 2026*
