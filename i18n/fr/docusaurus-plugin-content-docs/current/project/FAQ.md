---
sidebar_position : 20
slug : /foire-aux-questions
titre : FAQ
---

# Questions fréquemment posées

> 📚 Apprenez tout sur Alephium dans cet [aperçu de 5 minutes](5min-overview).

Avant de plonger plus profondément, nous vous recommandons de consulter les ressources suivantes car elles fournissent des informations utiles sur Alephium :

- Site Web officiel](https://alephium.org)
- Discord officiel](https://discord.gg/JErgRBfRSB)
- Telegramme officiel](https://t.me/alephiumgroup)
- [Medium officiel](https://medium.com/@alephium), et plus particulièrement :
  - [Tokenomics d'Alephium](https://medium.com/@alephium/tokenomics-of-alephium-61d59b51029c)
  - [Récompenses des blocs d'Alephium](https://medium.com/@alephium/alephium-block-rewards-72d9fb9fde33)
  - [Programme de récompenses de la communauté d'Alephium](https://medium.com/@alephium/introducing-community-rewards-f4638bbf14bf)
  - [Mise à jour du 1er trimestre 2022 d'Alephium](https://medium.com/@alephium/alephium-q1-project-update-50f4a7b354b0)
  - [1er AMA d'Alephium](https://medium.com/@alephium/alephiums-first-live-ama-761a90d3f672)

## FAQ

- FAQ](#faq)
- [Exploitation minière](#mining)
  - [Quelle est la récompense pour l'exploitation minière ?](#what-is-the-mining-reward)
  - [J'ai un GPU modèle XYZ, quel est mon profit par jour ?](#i-have-gpu-model-xyz-what-is-my-profit-per-day)
  - [Quelle est la raison de maintenir la récompense du bloc pendant 500 minutes, étant donné que le temps de bloc n'est que de 64 secondes ?](#what-is-the-reason-to-hold-the-block-reward-for-500-minutes-given-the-block-time-is-only-64-seconds)
  - [Pourquoi ai-je 4 adresses de mining ?](#why-do-have-4-mining-addresses)
  - [Existe-t-il un groupe pour les mineurs d'Alephium ?](#is-there-a-group-for-alephium-miners)
- [dApps](#dapps)
  - [Que sont les UTXO à état et comment sont-ils différents des autres modèles d'UTXO ?](#what-are-stateful-utxos-and-how-are-they-different-from-the-other-utxos-models)
  - [Quelle est la raison de créer un nouveau langage au lieu d'utiliser un langage existant comme Solidity ?](#what-is-the-reason-for-making-a-new-language-instead-of-using-an-existing-language-like-solidity)
  - [Quelqu'un construit-il déjà un DEX sur ALPH ?](#is-anyone-already-building-a-dex-on-alph)
- [wallet](#wallet)
  - [Existe-t-il un moyen de faire la distinction entre une adresse héritée de Bitcoin et une adresse Alephium ?](#is-there-a-way-to-distinguish-between-a-bitcoin-legacy-address-and-an-alephium-address)
  - [Y a-t-il une intégration prévue avec Ledger Nano ?](#is-there-a-planned-integration-with-ledger-nano)
- [Tokenomics](#tokenomics)
  - [Si les jetons sont brûlés, y aura-t-il un moment dans le futur où le montant des ALPH existants sera proche de zéro ?](#if-tokens-are-burnt-will-there-be-a-time-in-the-future-where-the-amount-of-existing-alph-will-be-close-to-zero)
  - [Quels sont les frais de transaction minimums (TF) ?](#what-is-the-minimum-transaction-fee-tf)
- [Échanges](#exchanges)
  - [Combien de temps faut-il pour que les dépôts apparaissent sur les échanges ?](#how-long-does-it-takes-for-deposits-to-show-up-on-exchanges)
  - [Quand Binance ?](#when-binance)
- [Divers](#miscellaneous)
  - [Avez-vous un programme de subventions et de récompenses ?](#do-you-have-a-grant--reward-program)
  - [Combien de transactions par seconde (TPS)](#how-many-transactions-per-second-tps)
  - [Pourquoi le projet s'appelle-t-il Alephium ?](#why-is-the-project-named-alephium)
  - [Pourquoi avoir choisi PoLW et non PoS ?](#why-did-you-choose-polw-not-pos)
  - [Pourquoi ne pas avoir 1M de shard ?](#why-not-have-1m-shards)
  - [Quel est le symbole de votre jeton ?](#what-is-your-token-symbol)
  - [Où puis-je apprendre tout ce qu'il faut savoir sur Alephium en 5 minutes ?](#where-can-i-learn-everything-about-alephium-in-5min)
  - [A QUAND LA LUNE ?](#when-moon)

## Exploitation minière

### Quelle est la récompense pour l'exploitation minière ?

La récompense pour les blocs d'Alephium est composée de deux éléments : la récompense pour les blocs nouvellement générés, également appelée récompense pour le minage (MR), et les frais de transaction (TF).

Récompense totale des blocs = Récompense minière + min(max(MR, 1 ALPH), Frais de transaction / 2)

Vous trouverez une explication plus détaillée de la récompense de bloc [dans cet article du officiel d'Alephium](https://medium.com/@alephium/alephium-block-rewards-72d9fb9fde33).

### J'ai le modèle de GPU XYZ, quel est mon bénéfice par jour ?

Un membre de la communauté a créé une feuille de calcul avec différents GPU [disponible ici](https://docs.google.com/spreadsheets/d/10eUjwGU-Kmw1XM1dDOKfdscOeShakSnjcBGzBT46rmc/)

### Quelle est la raison de retenir la récompense du bloc pendant 500 minutes, étant donné que la durée du bloc n'est que de 64 secondes ?

Le blocage de 500 minutes a été mis en place pour prévenir les attaques de ré-org. Similaire à Bitcoin, qui a ~1000 minutes de verrouillage pour les récompenses minées.

### Pourquoi ai-je 4 adresses minières ?

Alephium est une blockchain sharded avec G groupes et G\*G shards. En raison de cette conception, il est nécessaire d'avoir une adresse de minage par groupe.

Sur le réseau principal, nous avons actuellement 4 groupes et 16 shards. C'est pourquoi vous avez 4 adresses de minage, une pour chaque groupe.

### Y a-t-il un groupe pour les mineurs d'Alephium ?

Sur [le Discord,](https://discord.gg/JErgRBfRSB) il y a un canal spécial pour les mineurs, où vous pouvez trouver des groupes actifs.

## dApps

### Qu'est-ce qu'un UTXO à état et en quoi est-il différent des autres modèles d'UTXO ?

Il existe deux types d'états : l'état mutable (par exemple ETH) et l'état immuable (par exemple UTXO, Extended UTXO). L'état mutable est beaucoup plus expressif comme vous pouvez le voir dans l'écosystème de l'ETH, tandis que l'eUTXO peut être utilisé pour construire certaines applications avec des limitations.
Dans notre modèle UTXO avec état, nous supportons les états mutables de type ETH. Cela nous permet de construire facilement des dApps aussi puissantes que sur Ethereum sans les problèmes de sécurité du modèle de compte.

### Quelle est la raison de créer un nouveau langage au lieu d'utiliser un langage existant comme Solidity ?

Plusieurs raisons :

1. Nous sommes basés sur le modèle UTXO avec état, qui est très différent du modèle de compte d'ETH. Il est incompatible avec Solidity.
2. Les conceptions Solidity et EVM ne sont pas optimales et présentent des problèmes de sécurité connus. Nous voulons faire mieux.
3. Nous nous sommes concentrés sur l'expérience de développement lors de la conception de notre propre langage, afin de nous assurer qu'il est facile à démarrer !

#### Quelqu'un a-t-il déjà construit un DEX sur ALPH ?

Nous avons un simple [DEX de type Uniswap en test](https://github.com/alephium/alephium/blob/master/app/src/it/scala/org/alephium/app/SmartContractTest.scala#L142-L170).
Nous pourrions également prendre en charge les DEX de type carnet d'ordres, ce qui permettrait d'éviter le problème bien connu des pertes impermanentes (impermanent loss problem) grâce au modèle UTXO.

Nous avons identifié la DeFi et les dApps comme étant le prochain point critique pour Alephium. Pour lancer le développement, nous allons construire des dApps de démonstration propres, qui serviront d'exemples. Cela nous aidera à trouver des goulots d'étranglement ou des cas limites que nous n'avons pas été en mesure d'identifier auparavant. Cela servira également de base à la compilation de la documentation nécessaire pour aider les développeurs de la communauté à construire et à déployer leurs applications.
Notre VM et notre langage sont très conviviaux et si vous êtes familier avec Solidity, vous pouvez facilement créer des applications similaires sur Alephium.

### Wallet

### Existe-t-il un moyen de faire la distinction entre une adresse Bitcoin traditionnelle et une adresse Alephium ?

Les adresses Alephium sont généralement plus longues, car elles utilisent un hachage de 32 octets au lieu de 20 octets.

### Y a-t-il une intégration prévue avec Ledger Nano ?

Le plan est qu'une fois que la conception du wallet Desktop et du wallet de navigateur sera stable, nous travaillerons sur l'intégration de Ledger. En ce moment, nous introduisons des changements qui pourraient affecter la conception de l'application Ledger.

## Tokenomics

### Si les jetons sont brûlés, y aura-t-il un moment dans le futur où le nombre d'ALPH existants sera proche de zéro ?

Théoriquement oui, l'avenir n'est pas vraiment projetable au-delà de 80 ans. Cependant, il n'est pas rare que les blockchains open-source gérées par la communauté, comme Alephium, modifient leurs politiques au cours de leur évolution. Si la communauté décide de modifier un plafond, alors ce plafond sera modifié.

### Quel est le montant minimum des frais de transaction (TF) ?

Actuellement, les frais de transaction minimum sont de 0,002 ALPH. Ceci est appliqué au niveau du nœud pour éviter les attaques DoS sur le réseau.
Par la suite, le minimum sera réduit. Les frais de transaction minimums les plus bas possibles sont de 0,00000000000001 ALPH.
Les frais réels dépendront du nombre d'entrées (utxo) et du nombre de signataires.

## Échanges

### Combien de temps faut-il pour que les dépôts apparaissent sur les échanges ?

Actuellement, 120 confirmations sont nécessaires pour les dépôts, ce qui représente environ 2 heures (120 blocs \* temps de bloc 64s). Les chaînes PoW exigent généralement un nombre plus élevé de confirmations pour garantir une sécurité suffisante. Pour référence, il est toujours d'environ 1 heure pour le Bitcoin.

### Quand Binance ?

Nous n'avons pas de date exacte à ce sujet. Mais nous y travaillons. Cependant, vous serez parmi les premiers informés en rejoignant le [groupe Telegram](https://t.me/alephiumgroup), le [Discord Alephium](https://discord.gg/JErgRBfRSB) ou si vous suivez notre [compte Twitter](https://twitter.com/alephium).

## Divers

### Avez-vous un programme de subventions et de récompenses ?
Oui, voir [ce document](https://github.com/alephium/community/blob/master/Grant&RewardProgram.md) pour les détails.

### Combien de transactions par seconde (TPS) ?

Actuellement jusqu'à 400 TPS avec 16 shards. Alephium peut évoluer jusqu'à 10k TPS en augmentant le nombre de shards si nécessaire.

### Pourquoi le projet s'appelle-t-il Alephium ?

Pour ceux d'entre vous qui sont moins familiers avec la théorie des ensembles et les mathématiques, l'origine du nom "Alephium" n'est peut-être pas si évidente. Il est fait à partir du nom "Aleph" qui est défini sur Wikipedia : "Les nombres d'Aleph sont une séquence de nombres utilisée pour représenter la cardinalité des ensembles infinis qui peuvent être bien ordonnés. Ils ont été introduits par le mathématicien Georg Cantor et portent le nom du symbole qu'il utilisait pour les désigner, la lettre hébraïque aleph ( ℵ ). "

D'ailleurs, le logotype d'Alephium est une stylisation de la lettre Aleph.

En hommage aux promesses techniques d'Ethereum, nous avons suivi le même modèle de dénomination et le nom Alephium a été inventé.

### Pourquoi avoir choisi PoLW et non PoS ?

La technologie blockchain n'en est qu'à ses débuts et l'une des questions les plus courantes est la suivante : quelle infrastructure blockchain est nécessaire pour les 10 prochaines années pour les dApps, y compris DeFi ?

Nous pensons avoir besoin d'une blockchain évolutive avec un débit élevé et de faibles frais de transaction. Nous voulons un haut niveau de programmabilité comme sur Ethereum. Et nous avons besoin qu'elle soit aussi fiable et sûre que le Bitcoin.
Par conséquent, Alephium a été développé sur l'idée de construire un Bitcoin évolutif avec une solution DeFi fiable.

Selon la théorie de l'effet Lindy, et malgré les récents succès du PoS, il est très probable que le modèle Bitcoin et le sharding + PoW restent le moyen le plus robuste et décentralisé de construire une blockchain évolutive. Plus précisément :

1. Le PoW est simple et robuste. Il est beaucoup plus facile de concevoir un algorithme de sharding avec PoW.
2. Le PoS n'a pas encore été testé dans le temps, nous attendons avec impatience de voir comment le PoS va évoluer après le changement de PoS de l'ETH.
3. Le PoS a tendance à être plus centralisé et plus vulnérable à la censure.
4. Le PoS a tendance à réduire la confiance car le coût de fonctionnement d'un nœud peut être considérablement plus élevé.
5. PoS est plus vulnérable à certaines attaques DeFi comme MEV.

### Pourquoi ne pas avoir 1M de shard ?

La taille du groupe G n'est pas très grande. Chaque noeud doit maintenir 2G - 1 autres shards pour la cohérence. Nous voulons garder les choses petites. 2G-1 ne peut pas être trop grand. Si la bande passante moyenne du réseau est suffisante, G peut être fixé jusqu'à 32. Il y a aussi des frais de calcul, mais le réseau est le principal goulot d'étranglement pour pousser G plus haut.

### Quel est votre symbole de jeton ?

ALPH

### Où puis-je apprendre tout sur Alephium en 5 minutes ?

Vous pouvez obtenir rapidement une très bonne vue d'ensemble de tout ce qui concerne Alephium dans [cet article Medium](https://medium.com/@alephium/welcome-to-alephium-alph-48dfb72aa458).

### A QUAND LA LUNE ?

1ALPH équivaut toujours à 1ALPH. Le voyage est la destination !
