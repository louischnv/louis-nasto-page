# louis-nasto-page

Page de confirmation post-booking Calendly de Nasto International Kft.
Réplique exacte de la page Lovable louis.mcconseil.eu (charte M&C : Noe Display + Inter, navy/orange/stone), badgée Nasto en header/footer.

- URL : https://louis.nasto.hu
- Hébergement : GitHub Pages (branche main, racine), HTTPS Let's Encrypt, Enforce HTTPS
- DNS : CNAME louis.nasto.hu -> louischnv.github.io (zone Netim, TTL 5 min)
- Déploiement : git push (deploy key ~/.ssh/id_ed25519_nasto_pages, configurée dans core.sshCommand du repo)
- CSS : bundle Tailwind repris du build Lovable (assets/styles.css), fonts auto-hébergées (Noe Display depuis le M&C Brain, Inter variable)
- JS vanilla : accordéon FAQ (un seul ouvert) + compteurs animés de la bande navy
