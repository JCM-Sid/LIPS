Entrées (prod + load + topo + statut)
        │
Encodage séparé (Dense)
        │
Concaténation
        │
Traitement principal (Dense)
        │
Ajout statut/topologie
        │
Sous-réseaux de prédiction (Dense)
        │
Application des masques (Multiply)
        │
Sorties : a_hat, p_hat, q_hat, v_hat, theta_hat, ...
