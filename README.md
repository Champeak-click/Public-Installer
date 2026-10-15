# ChamPeak Pro — Official Installer & Releases 🚀

Repositorio oficial de distribución pública, instaladores y notas de versión de **ChamPeak Pro** (Esports High-Performance Optimization Suite).

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011%20(x64)-blue.svg)](#requisitos-del-sistema)
[![Releases](https://img.shields.io/github/v/release/Champeak-click/Public-Installer?color=brightgreen&label=Latest%20Release)](https://github.com/Champeak-click/Public-Installer/releases/latest)
[![Security](https://img.shields.io/badge/Security-Ring%203%20User%20Mode-success.svg)](#seguridad-y-anti-cheat)

---

## 📥 Descarga e Instalación

Para descargar la versión más reciente y verificada:

1. Ve a la sección de **[Releases](https://github.com/Champeak-click/Public-Installer/releases/latest)**.
2. Descarga el instalador oficial: `ChamPeak_Setup.exe`.
3. Ejecuta el instalador y sigue las instrucciones en pantalla.

---

## 🛡️ Seguridad, Integridad y Anti-Cheats

ChamPeak Pro fue diseñado bajo una estricta filosofía de seguridad y compatibilidad competitiva:

- **Ejecución Ring 3 en Modo Usuario:** 0 inyecciones de DLL (`CreateRemoteThread`), 0 hooks de memoria protegida y 0 manipulación de procesos de terceros.
- **100% Compatible con Anti-Cheats:** Totalmente transparente para **Riot Vanguard, Easy Anti-Cheat (EAC), BattlEye, Valve Anti-Cheat (VAC) y Call of Duty Ricochet**.
- **Compilación C++ Nativa:** Binarios de bajo nivel generados con optimizaciones de máquina MSVC, minimizando falsos positivos heurísticos de antivirus.
- **Rollback en 1-Click:** Reversión instantánea de directivas a los valores predeterminados de Windows en cualquier momento.

### Verificación de Integridad (SHA-256)
Puedes verificar la integridad del instalador descargado en PowerShell:
```powershell
Get-FileHash -Path .\ChamPeak_Setup.exe -Algorithm SHA256
```
Compara el hash obtenido con el hash publicado en las notas de la release correspondiente.

---

## 💻 Requisitos del Sistema

- **Sistema Operativo:** Windows 10 (64-bit) versión 1903 o superior / Windows 11 (64-bit).
- **Procesador:** Intel Core o AMD Ryzen (soporte para perfiles híbridos P/E-Cores y 3D V-Cache).
- **Memoria RAM:** 4 GB mínimo (8 GB recomendado).
- **Privilegios:** Permisos de administrador de Windows para la aplicación de optimizaciones del sistema.

---

## 🐛 Reporte de Errores y Soporte

Si experimentas algún problema con el instalador o deseas sugerir una mejora:
- Abre un reporte en la pestaña **[Issues](https://github.com/Champeak-click/Public-Installer/issues)**.
- O visita nuestro sitio web oficial.
