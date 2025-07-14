# PCKTRCR-AV
petit exercice test Packet tracer pour un cabinet d'avocat

Ce projet a été réalisé dans Cisco Packet Tracer. Il représente l’infrastructure réseau d’un cabinet d’avocats avec plusieurs postes utilisateurs, un serveur, une imprimante réseau et un accès à Internet.

## Contenu du projet

###  Architecture réseau
- Tous les équipements sont connectés à un **switch central (Switch0)**.
- Le réseau est en **IPv4** sur le sous-réseau `192.168.1.0/24`.
- Accès à Internet simulé via un **routeur sans fil (WRT300N)**.

###  Postes utilisateurs
- Plusieurs PC répartis par service : Avocats, Secrétariat, Comptabilité, Direction.
- Chaque PC reçoit une IP automatiquement grâce au serveur DHCP.

### 🖨️ Périphériques
- 1 imprimante réseau connectée au switch.
- 1 serveur HP Proliant utilisé pour les services réseau.

## Services réseau

###  DHCP
- Le serveur `HP PROLIANT ML30 GEN10` joue le rôle de serveur DHCP.
- Plage d’adresses attribuées automatiquement à partir de `192.168.1.2` à `192.168.1.151`.

###  DNS
- Le DNS estégalement configuré dans le `HP PROLIANT ML30 GEN10.
- Permet la résolution de noms internes pour les postes clients.

###  Sécurité d’accès
Le routeur 1 et le switch central sont sécurisés par des mdp.

mdp pour mode privilégié switch:
cisco123
Utilisateur accés au switch "Administrateur" , mdp :cisco124
routeur mdp mode privilégié : 5878FPX//*@MHZz2578
mdp administrateur : 587://78BmFtY899//***@@())
