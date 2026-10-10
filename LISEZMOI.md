# Mettre le portfolio en ligne (gratuit, environ 10 minutes)

Ce dossier est le site complet, prêt à publier. Pour que Google et les IA (ChatGPT, Perplexity, Gemini, Claude) trouvent et citent ton profil, il doit être en ligne sur une adresse publique : la page claude.ai, elle, n'est pas indexée.

## Hébergement : GitHub Pages

Le site est publié depuis le dépôt `PeyoDupouey/peyodupouey.github.io` (GitHub Pages, branche `main`, dossier racine) à l'adresse https://peyodupouey.github.io/

Si tu choisis une autre adresse (par exemple un nom de domaine `peyodupouey.fr`), dis-le pour régénérer le dossier : l'adresse figure dans la balise canonique, les données structurées, le sitemap, le robots.txt et le llms.txt.

## Ensuite, pour être référencé

1. **Google Search Console** (https://search.google.com/search-console) : ajoute le site, valide-le, puis soumets `sitemap.xml`.
2. **Bing Webmaster Tools** (https://www.bing.com/webmasters) : importe le site depuis la Search Console. Bing alimente notamment Copilot et une partie des recherches de ChatGPT.
3. **LinkedIn** : ajoute l'adresse du portfolio dans « Coordonnées » et dans la section « Sélection ». Ce lien dans les deux sens confirme aux moteurs que le site et le profil LinkedIn sont la même personne.
4. Mets l'adresse dans ton CV, ta signature d'e-mail et tes candidatures.

## À chaque mise à jour

Modifie le contenu, change la date dans `content-seo.js` (`C.updated` et `foot.updated`), régénère le dossier, puis redépose les fichiers modifiés.
