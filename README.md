# ShadowSec Labs

![Cloudflare](https://img.shields.io/badge/Cloudflare-WAF-orange)
![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-black)
![Status](https://img.shields.io/badge/Status-Active-success)

Laboratorio práctico enfocado en la implementación y configuración de un **Web Application Firewall (WAF)** utilizando Cloudflare para proteger aplicaciones web publicadas mediante GitHub Pages.

## Sitio Web

**URL del laboratorio:**

https://shadowseclabs.xyz

## Objetivos

Este laboratorio tiene como finalidad:

- Configurar un dominio real.
- Integrar el dominio con Cloudflare.
- Implementar HTTPS mediante SSL/TLS.
- Configurar reglas WAF para protección web.
- Aplicar controles de seguridad contra ataques comunes.
- Analizar eventos de seguridad generados por Cloudflare.

## Tecnologías Utilizadas

- HTML5
- CSS3
- JavaScript
- GitHub Pages
- Cloudflare DNS
- Cloudflare WAF
- SSL/TLS
- OWASP Top 10

## Controles de Seguridad Implementados

### Cloudflare Managed Rules

- Protección automática contra amenazas conocidas.
- Mitigación de ataques web comunes.

### OWASP Ruleset

Protección contra:

- SQL Injection (SQLi)
- Cross Site Scripting (XSS)
- Remote Code Execution (RCE)
- Local File Inclusion (LFI)

### Reglas Personalizadas

- Bloqueo de patrones SQL Injection.
- Bloqueo de intentos XSS.
- Rate Limiting para rutas sensibles.
- Restricciones geográficas.
- Bloqueo de User-Agents sospechosos.

## Arquitectura

```text
Usuario
   │
   ▼
Cloudflare DNS
   │
   ▼
Cloudflare WAF
   │
   ▼
GitHub Pages
```

## Evidencias

### Cloudflare Dashboard

Agregar capturas de:

- DNS Records
- SSL/TLS
- WAF Rules
- Security Events

## Despliegue

1. Clonar repositorio

```bash
git clone https://github.com/shadowsec-labs/shadowseclabs.git
```

2. Entrar al directorio

```bash
cd shadowseclabs
```

3. Editar archivos HTML.

4. Realizar commit y push.

```bash
git add .
git commit -m "Actualización del laboratorio"
git push origin main
```

## Aprendizajes

Durante este laboratorio se trabajó con:

- Gestión de DNS.
- Configuración de Cloudflare.
- Protección de aplicaciones web.
- Hardening básico.
- Implementación de HTTPS.
- Seguridad perimetral.


## Aviso

Este proyecto tiene fines exclusivamente educativos y de aprendizaje en ciberseguridad defensiva.
