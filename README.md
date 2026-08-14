# Race Engineer WebHUD host

Cliente WebHUD estático para RaceRoom. Mantiene válida la URL configurada aunque Race Engineer no esté abierto y se conecta directamente al servicio local de telemetría cuando está disponible.

No recibe, almacena ni transmite telemetría: el HUD y sus datos continúan en `127.0.0.1`.

`tools/Sync-WebHudHost.ps1` lo sincroniza mecánicamente desde `WebHudPage.Html` para que la versión local y la alojada no puedan divergir.
