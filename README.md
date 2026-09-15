# EventsHub
ICI 2026 01

## API

Para iniciar la API localmente:

```bash
dotnet run --project src/EventsHub.Api/EventsHub.Api.csproj
```

La API queda disponible en `https://localhost:5001/api/v1`.

### Endpoints de eventos

| Método | Ruta | Descripción |
| --- | --- | --- |
| `GET` | `/Events` | Lista los eventos disponibles. |
| `GET` | `/Events/{id}` | Consulta un evento por su identificador. |

La colección de pruebas de Bruno se encuentra en `tests/EventsHub.IntegrationTests`.
