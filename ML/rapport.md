# AHAKKOUN Houssam
<img src="sb3.jpg" style="height:464px;margin-right:432px"/>
Le graphique montre l'erreur d'entraînement et l'erreur de validation en fonction de k. Nous pouvons observer :

Erreur d'entraînement : Généralement, elle augmente avec k. Lorsque k est petit, le modèle est plus flexible et peut très bien s'adapter aux données d'entraînement, ce qui entraîne une faible erreur d'entraînement (et un surapprentissage potentiel). À mesure que k augmente, le modèle devient plus simple et sa capacité à s'adapter parfaitement aux données d'entraînement diminue, d'où l'augmentation de l'erreur d'entraînement.
Erreur de validation : Elle diminue initialement à mesure que k augmente à partir de 1, atteint un minimum, puis commence à augmenter. Un petit k (par exemple, k=1) conduit souvent à une variance élevée et à un surapprentissage des données de validation. Un très grand k conduit à un biais élevé et à un sous-apprentissage. Le k optimal est généralement celui où l'erreur de validation est minimisée.
Selon nos calculs, le k optimal (k_star) est la valeur qui a entraîné l'erreur de validation minimale. Cette valeur vise à équilibrer le biais et la variance, offrant la meilleure performance de généralisation sur des données non vues. Dans ce cas, k_star = 1 est le meilleur choix basé sur notre ensemble de validation.
