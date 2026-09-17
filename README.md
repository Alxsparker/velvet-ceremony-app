# Velvet Ceremony

App pour Sève (officiante de cérémonies laïques, Love & Live) — gestion des mariages,
questionnaires des mariés, discours des intervenants, Constellation du couple.

## Backend

Utilise le projet Supabase partagé `loveandlive-media` (le même que l'app de
publication Instagram/Facebook de Love & Live) — pas de projet Supabase dédié,
pour rester sur le plan gratuit sans dépasser la limite de 2 projets actifs.

## Robot anti-pause

`.github/workflows/keep-supabase-alive.yml` ping ce projet Supabase tous les
jours à 9h (UTC) pour éviter la mise en pause automatique du plan gratuit après
7 jours sans activité. Aucune donnée n'est modifiée, juste un ping.
