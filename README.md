# TP-TOBOGAN-EXTRANET-README.md
# TP TOBOGAN / EXTRANET – Diagnostic réseau

## Objectif

Diagnostiquer un problème de connectivité entre un LAN, le réseau TOBOGAN et un serveur EXTRANET.

## Contexte

Certains postes ne parviennent pas à accéder à Internet ou au serveur EXTRANET.  
L’objectif est d’identifier l’origine du problème et de corriger la configuration réseau.

## Outils utilisés

- ping
- traceroute
- nslookup
- curl
- show ip route

## Diagnostic réalisé

Les tests ont permis de vérifier :

- la configuration IP locale ;
- la passerelle par défaut ;
- la résolution DNS ;
- la table de routage ;
- les règles NAT/PAT ;
- les ACL ;
- l’accès HTTP au serveur EXTRANET.

## Commandes principales

```bash
ping 8.8.8.8
traceroute 8.8.8.8
nslookup www.google.com
curl http://<IP_EXTRANET>
