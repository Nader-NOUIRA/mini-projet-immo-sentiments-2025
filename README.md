# Mini-projet Data Mining - Prédiction Prix Immobiliers Paris

**Étudiants** : Nader NOUIRA & Nesrine BEN YAHIA  
**Classe** : 3 DNI - 2025

## Description du projet
Application web interactive qui prédit le prix d'un bien immobilier à Paris en intégrant :
- Sentiments simulés sur les quartiers
- Clustering K-Means pour grouper les quartiers par vibe
- Régression Random Forest pour prédire le prix
- Indice d'attractivité personnalisé (combinaison sentiment + prix moyen)

## Installation
1. Clone le dépôt  
   `git clone https://github.com/[ton-pseudo]/mini-projet-immo-sentiments-2025`
2. Installe les dépendances  
   `pip install -r requirements.txt`
3. Lance l'application  
   `python -m streamlit run src/app.py`

## Démonstration (captures d'écran)
<img width="1366" height="768" alt="Capture d’écran (137)" src="https://github.com/user-attachments/assets/0ddfe27f-2018-47cd-8508-06ff9df03bef" />
<img width="1366" height="768" alt="Capture d’écran (138)" src="https://github.com/user-attachments/assets/ae33c2de-1913-4e98-ab30-ffb8d11953d3" />
<img width="1366" height="768" alt="Capture d’écran (140)" src="https://github.com/user-attachments/assets/44ef061a-992c-4b16-839d-787ea37b8e9d" />


## Algorithmes Data Mining utilisés
- Clustering non supervisé : **K-Means**
- Régression supervisée : **Random Forest Regressor**
- Feature engineering : indice d'attractivité original

Projet 100% original – Réalisé avec Python, scikit-learn et Streamlit.
