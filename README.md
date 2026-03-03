📊 Analyse des facteurs influençant les performances commerciales
🎯 Objectif
Comprendre les interactions entre ventes, remises, volume et rentabilité afin d’identifier les leviers d’optimisation stratégique.

Dataset : Superstore Dataset

🔎 Méthodologie
Analyse bivariée (corrélations)
Segmentation par région
Segmentation par catégorie
Analyse des remises et de leur impact
Visualisations (scatter plots, heatmap)

📈 Résultats clés
Sales et Profit présentent une corrélation modérée positive (r = 0.48).
Discount est négativement corrélé au Profit (r = -0.22).
Discount n’a quasiment aucun impact sur Quantity (r ≈ 0.01).
La région Central applique les remises les plus élevées (~24 % en moyenne).
Sur la catégorie Furniture en Central, la remise atteint près de 30 %.
Furniture est la catégorie la plus sensible aux remises (r = -0.48).

💡 Insight stratégique
Les remises n’augmentent pas significativement le volume mais dégradent fortement la rentabilité, notamment sur la catégorie Furniture en région Central.

🚀 Recommandations
Réduire les remises sur Furniture en région Central.
Introduire un plafond de remise.
Mettre en place un suivi mensuel des marges par région et catégorie.
Tester une stratégie promotionnelle différenciée.

🛠 Outils utilisés
Python
Pandas
Seaborn
Matplotlib

📁 Structure du projet
- data/ → dataset
- notebooks/ → analyse complète
- images/ → visualisations exportées
