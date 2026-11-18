# Informe Buen Fin 2026 · Z-PEV

Informe ejecutivo de la campaña Buen Fin 2026 (canal WhatsApp Z-IA) para Z e-Scooters MX. Elaborado por Neural Network Initiative.

Sitio estático en Firebase Hosting: proyecto `z-ia-whatsapp`, sitio `zpev-buenfin` → https://zpev-buenfin.web.app

Contiene datos personales de clientes (uso interno); la página no se indexa (`noindex`).

## Deploy
```powershell
firebase hosting:sites:create zpev-buenfin --project z-ia-whatsapp   # solo la primera vez
firebase deploy --only hosting
```
