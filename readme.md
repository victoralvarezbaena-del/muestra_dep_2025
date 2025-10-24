# 🏆 Plataforma de Torneos Deportivos - Muestra Deportiva 2025

Plataforma web unificada para gestionar y visualizar torneos multideportivos estudiantiles.

## 🎯 Características Principales

- **Sistema Multi-deporte**: Fútbol, Basquetbol, Voleibol, Handball, Beisbol, Softbol
- **Separación por disciplinas**: Cada deporte con su sistema especializado
- **Doble interfaz**: Panel de administración + Vista pública
- **Diseño responsive**: Optimizado para desktop y móvil
- **Tiempo real**: Resultados actualizados automáticamente
- **Gestión independiente**: Cada torneo funciona de forma autónoma

## 🚀 Uso Rápido

### Portal Principal
Accede al [portal principal](index.html) para ver todos los deportes disponibles.

### Para Administradores
1. **Beisbol**: [`beisbol/admin.html`](beisbol/admin.html)
2. **Softbol**: [`softbol/admin.html`](softbol/admin.html)
3. **Fútbol**: [`futbol/admin.html`](futbol/admin.html)
4. **Basquetbol**: [`basquetbol/admin.html`](basquetbol/admin.html)
5. **Voleibol**: [`voleibol/admin.html`](voleibol/admin.html)
6. **Handball Varonil**: [`handball/admin.html`](handball/admin.html)
7. **Handball Femenil**: [`handballf/admin.html`](handballf/admin.html)

### Para Público General
1. **Beisbol**: [`beisbol/index.html`](beisbol/index.html)
2. **Softbol**: [`softbol/index.html`](softbol/index.html)
3. **Fútbol**: [`futbol/index.html`](futbol/index.html)
4. **Basquetbol**: [`basquetbol/index.html`](basquetbol/index.html)
5. **Voleibol**: [`voleibol/index.html`](voleibol/index.html)
6. **Handball Varonil**: [`handball/index.html`](handball/index.html)
7. **Handball Femenil**: [`handballf/index.html`](handballf/index.html)

## 📁 Estructura del Proyecto

```
muestra-deportiva-2025/
│
├── index.html                      # Portal principal multideportivo
├── readme.md                       # Documentación
│
├── beisbol/                        # Sistema de torneos de béisbol
│   ├── admin.html                  # Panel de administración
│   ├── index.html                  # Vista pública
│   └── data.json                   # Datos del torneo (generado)
│
├── softbol/                        # Sistema de torneos de softbol
│   ├── admin.html                  # Panel de administración
│   ├── index.html                  # Vista pública
│   └── data.json                   # Datos del torneo (generado)
│
├── futbol/                         # Sistema de torneos de fútbol
│   ├── admin.html                  # Panel de administración
│   ├── index.html                  # Vista pública
│   └── data.json                   # Datos del torneo (generado)
│
├── basquetbol/                     # Sistema de torneos de basquetbol
│   ├── admin.html                  # Panel de administración
│   ├── index.html                  # Vista pública
│   └── data.json                   # Datos del torneo (generado)
│
├── voleibol/                       # Sistema de torneos de voleibol
│   ├── admin.html                  # Panel de administración
│   ├── index.html                  # Vista pública
│   └── data.json                   # Datos del torneo (generado)
│
├── handball/                       # Sistema de handball varonil
│   ├── admin.html                  # Panel de administración
│   ├── index.html                  # Vista pública
│   └── data.json                   # Datos del torneo (generado)
│
└── handballf/                      # Sistema de handball femenil
    ├── admin.html                  # Panel de administración
    ├── index.html                  # Vista pública
    └── data.json                   # Datos del torneo (generado)
```

## 🛠️ Funcionalidades por Deporte

### ⚾ Béisbol & 🥎 Softbol
- **Formato**: 2 grupos de 4 equipos + eliminatoria
- **Criterios**: Porcentaje de victorias, diferencia de carreras
- **Regla Mercy**: 15+ carreras (3ra) / 10+ carreras (4ta)
- **Semifinales**: A1 vs B2, B1 vs A2

### ⚽ Fútbol & 🏀 Basquetbol & 🏐 Voleibol
- **Formato**: 4 grupos de 3 equipos + eliminatoria
- **Criterios**: Puntos, diferencia de goles, goles a favor
- **Sistema de puntos**: 3-1-0 (victoria-empate-derrota)

### 🤾 Handball
- **Ramas**: Varonil y Femenil separadas
- **Formato**: Grupos + eliminatoria según cantidad de equipos

## 📋 Instrucciones de Uso

### Para Administradores
1. **Accede** al panel de administración del deporte correspondiente
2. **Configura** los equipos por grupo
3. **Genera** el calendario de partidos automáticamente
4. **Registra** resultados, horarios y lugares
5. **Publica** los datos para que se actualice la vista pública

### Para Espectadores
1. **Visita** la vista pública del deporte deseado
2. **Consulta** grupos, resultados y tablas de posiciones
3. **Sigue** la fase eliminatoria en tiempo real

## 🔧 Personalización

Cada sistema deportivo incluye:
- **Temas de colores** personalizables
- **Nombre del torneo** editable
- **Criterios específicos** por deporte
- **Horarios y lugares** configurables

## 🌐 Despliegue

### GitHub Pages
1. Sube todos los archivos al repositorio
2. Activa GitHub Pages en la configuración
3. Los torneos estarán disponibles en: `https://[usuario].github.io/[repositorio]`

### Servidor Web Tradicional
1. Sube los archivos a cualquier servidor web
2. Asegúrate de que todos los archivos mantengan la estructura de carpetas
3. Accede a `index.html` desde el navegador

## 📞 Soporte

- **Documentación**: Consulta este archivo README
- **Problemas técnicos**: Verifica la consola del navegador (F12)
- **Sugerencias**: Contacta al equipo de desarrollo

---

**Desarrollado para la Muestra Deportiva 2025**  
*Sistema unificado de gestión de torneos multideportivos*