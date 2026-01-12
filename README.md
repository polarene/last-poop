# Ultima Cacca

Mini webapp client-only (una singola pagina) per segnare la data dell’ultima cacca di Susanna.

## Pubblicazione su GitHub Pages

1. Crea un repository su GitHub (es. `ultima-cacca`).
2. Metti questi file nella root del repository (come sono qui).
3. Attiva GitHub Pages:
   - Repository → **Settings** → **Pages**
   - **Build and deployment** → Source: **Deploy from a branch**
   - Branch: `main` / folder: `/ (root)`
4. Apri l’URL di Pages dal telefono.

## Installazione sul telefono "tipo app"

### Android (Chrome)
- Apri l’URL su Chrome.
- Menu ⋮ → **Installa app** / **Aggiungi a schermata Home**.

### iPhone (Safari)
- Apri l’URL su Safari.
- Condividi → **Aggiungi a Home**.

## Nota su offline

Senza service worker l’installazione/“aggiungi a home” può comunque funzionare, ma l’offline non è garantito in modo affidabile: se vuoi offline sicuro, serve aggiungere un service worker (non incluso qui).
