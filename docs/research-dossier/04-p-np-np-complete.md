# 04 — P, NP et NP-complétude

## P

P est la classe des problèmes de décision résolubles par une machine de Turing déterministe en temps polynomial.

## NP

NP est la classe des problèmes de décision dont un certificat peut être vérifié en temps polynomial par une machine déterministe.

## Inclusion

P ⊆ NP. La question ouverte est P = NP ?

## NP-complet

Un problème est NP-complet lorsqu'il appartient à NP et que les problèmes de NP peuvent être réduits vers lui en temps polynomial, selon la définition standard de la réduction utilisée.

## Réduction

Une réduction polynomiale transforme efficacement une instance d'un problème A en une instance d'un problème B de manière à préserver la réponse pertinente. On note A ≤p B.

Intuition : si B avait un algorithme polynomial, alors A pourrait également être résolu en temps polynomial via la réduction.

## Cook-Levin

Le théorème de Cook-Levin établit que SAT est NP-complet. Il constitue un point historique et théorique fondamental.

## Avertissement

« SAT est difficile dans mes expériences » ne signifie pas « SAT n'a aucun algorithme polynomial ». La seconde affirmation demanderait une preuve générale.
