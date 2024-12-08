# Bitcoin Price Prediction

Ce projet analyse et prédit le prix du Bitcoin en utilisant des modèles de machine learning, notamment des réseaux de neurones, RNN et LSTM.

## Données
- **Période** : Août 2017 à Juillet 2023  
- **Source** : API Binance  
- **Fréquence** : Intervalles d'une minute  
- **Colonnes** : Prix d'ouverture, haut, bas, clôture et volume de trading.

## Modèles et Performances
### Top Modèles :
1. **Réseaux de Neurones**  
   - R² = 0.948  
   - MSE : 0.00155  
2. **RNN**  
   - R² = 0.904  
   - MSE : 645,917  
3. **LSTM**  
   - R² = 0.673  
   - MSE : 2,213,336  

## Moyenne
La différence moyenne entre les prix d'ouverture et de clôture est de **0.0406**.
