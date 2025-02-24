# template-api-symfony

Ce repo permet de démarrer avec une API Symfony permettant le minimum pour un système de connexion utilisateur avec un Token JWT (lexik/jwt-authentication-bundle et gesdinet/jwt-refresh-token-bundle)

Certaines fonctionnalités peuvent ne pas être complète, cela me sert principalement pour débuter mes projets

Au niveau des routes vous trouverez :
- api/login_check : Connexion utilisateur avec email et mot de passe
- api/auth/me : Permet de récupérer quelques infos utilisateur
- api/logout : Déconnexion
- api/token/refresh : Refresh le token jwt lorsqu'il arrive à expiration / ou a expiré
