Le code du projet Aristote est publié sous licence MIT sous la forme de plusieurs dépôts correspondant chacun à un composant différent.

- **Serveur API Aristote** : Ce dépôt contient le serveur d'API pour les clients et pour les workers (transcription, LLM, évaluation)

[https://github.com/CentraleSupelec/aristote-api](https://github.com/CentraleSupelec/aristote-api)

-  **Worker d'enrichissement LLM** : Ce dépôt permet de créer un worker d'enrichissement LLM pour Aristote

[https://github.com/CentraleSupelec/aristote-llm-workers](https://github.com/CentraleSupelec/aristote-llm-workers)

- **Worker de transcription** : Ce dépôt permet de créer un worker de transcription basé sur Whisper pour Aristote

En cours de publication, à suivre sur:

[https://github.com/CentraleSupelec/aristote-transcription-workers](https://github.com/CentraleSupelec/aristote-transcription-workers)

- **Portail Aristote** : Ce dépôt permet de créer un portail Web client d'Aristote pour tester les enrichissements de fichiers vidéo ou audio (production de métadonnées, de sous-titres avec ou sans traduction, de quiz, de prise de notes)

En cours de publication, à suivre sur:

[https://github.com/CentraleSupelec/aristote-portail](https://github.com/CentraleSupelec/aristote-portail)

- **Aristote-Dispatcher** : Ce dépôt permet de créer une infrastructure de partage de LLM en exposant des API compatibles OpenAI et en s'occupant de la répartition de charge et de la gestion des priorités

[https://github.com/CentraleSupelec/aristote-dispatcher](https://github.com/CentraleSupelec/aristote-dispatcher)

- **Passerelle Aristote/Visio** : Ce dépôt est le résultat du Hackathon organisé le 12/09/2024 par la DINUM pour ajouter la fonctionnalité de transcription et de prises de notes à l’outil Visio [https://visio.numerique.gouv.fr](https://visio.numerique.gouv.fr)

[https://github.com/CentraleSupelec/aristote-meet-transcript](https://github.com/CentraleSupelec/aristote-meet-transcript)

- **Passerelle Aristote/Ubicast-Nudgis** : Ce dépôt permet de traiter en lots, via Aristote, les vidéos  disponibles sur un serveur VoD Nudgis d'Ubicast

[https://github.com/CentraleSupelec/aristote-nudgis-enrich](https://github.com/CentraleSupelec/aristote-nudgis-enrich)
