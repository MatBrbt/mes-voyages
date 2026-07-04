# Mes Voyages

Planificateur de voyages multi-destinations : idées, planning jour par jour, budget bi-devise, carte interactive avec itinéraire, checklist, carnet de voyage.

**Application :** https://matbrbt.github.io/mes-voyages/

## Architecture

- `index.html` (ce dépôt) : page de chargement servie par GitHub Pages — ne pas modifier.
- Le contenu réel de l'application est hébergé sur Supabase Storage et chargé dynamiquement ; les mises à jour de l'app ne passent pas par ce dépôt.
- Données synchronisées via Supabase (partage de voyages par lien d'invitation `?join=<id>`).
