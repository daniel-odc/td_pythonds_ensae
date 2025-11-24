TODO:

- Add invite collaborators slides
- change order commands `push` `pull`

# TD ENSAE - Python pour la data science

Ce repo comporte des supports de présentation pour la conduite des TD du
cours [ENSAE](https://www.ensae.fr/) [Python pour la data science](https://pythonds.linogaliana.fr/)
de [Lino Galiana](https://github.com/linogaliana).

# Sommaire

- [TD 01 - Rappels de base](./docs/slides/01_rappels_base.html)

| Terme                          | Définition                                                   | Formulation                                          |
|--------------------------------|--------------------------------------------------------------|------------------------------------------------------|
| Exactitude (**Accuracy**)      | Proportion de prédictions correctes                          | 𝑎𝑐𝑐=(𝑉𝑃+𝑉𝑁)/𝑇𝑜𝑡𝑎𝑙                        | 
| Précision (**Precision**)          | Proportion de vrais positifs parmi tous les positifs prédits | 𝑝𝑟𝑒𝑐=𝑉𝑃/(𝑉𝑃 + 𝐹𝑃)                          | 
| Rappel (**Recall**) ou Sensibilité | Proportion de vrais positifs parmi tous les positifs réels   | 𝑟𝑒𝑐=𝑉𝑃/(𝑉𝑃+ 𝐹𝑁)                             | 
| **F1-Score**                       | Moyenne harmonique entre précision et rappel                 | 𝑓1−𝑠𝑐𝑜𝑟𝑒=2∗(𝑝𝑟𝑒𝑐 ∗𝑟𝑒𝑐)/(𝑝𝑟𝑒𝑐+𝑟𝑒𝑐) | 
| **Spécificité**                    | Proportion de vrais négatifs parmi tous les négatifs réels   | 𝑠𝑝𝑒𝑐=𝑉𝑁/(𝑉𝑁+𝐹𝑃)                            |   