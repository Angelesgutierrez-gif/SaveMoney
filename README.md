# SaveMoney

Proyecto del 3er parcial: aplicación móvil de ahorro desarrollada con React Native y Expo SDK 57.

## Ejecutar

Requiere Node.js 22.13 o superior.

```bash
npm install
npx expo start
```

Escanea el QR con Expo Go compatible con SDK 57. Para usar un túnel de Internet:

```bash
npx expo start --tunnel
```

Para abrir la versión web:

```bash
npx expo start --web
```

## Pantalla de alertas y recordatorios

La pantalla principal está en `src/components/savings-screen.tsx`, conectada mediante Expo Router en `src/app/index.tsx`.

Incluye monitoreo de presupuestos, selección de umbrales, activación de metas y formularios para ajustar topes, registrar aportes y crear recordatorios. Los datos son de demostración y los cambios se mantienen durante la sesión; no se realizan débitos ni se programan notificaciones reales.

## Verificación

```bash
npx tsc --noEmit
npx expo lint
```

Los documentos originales del repositorio se conservan en `Documents/`.
