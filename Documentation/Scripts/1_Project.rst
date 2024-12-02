2.3.Local OCR and LLM
~~~~~~~~~~~~~~~~~~~~~~~
Pour cette approuche on va utiliser un outil OCR local comme PaddleOCR,EasyOCR... pour l'extraction du texte suivie avec un LLM pour Token Classification
afi d'extraire les informations pertinentes.


**Avantages de l’utilisation local OCR and LLM:**

- Économique : Aucun coût supplémentaire pour les services externes.
- Sécurité des données : La confidentialité des données est renforcée car le traitement est effectué au sein de votre écosystème.
- Indépendance vis-à-vis des API : Le manque de dépendance vis-à-vis des API externes élimine les préoccupations concernant les limites de débit et la latence,la vitesse ne dépendant que du matériel de l’utilisateur.

**Inconvénients de l’utilisation de local OCR and LLM:**

- Exigences d’infrastructure : Nécessite des ressources de calcul importantes pour la mise à l’échelle.
- Vitesse d’inférence : La vitesse de traitement dépend du matériel disponible, ce qui pourrait être une limitation pour les utilisateurs de systèmes moins puissants.



















