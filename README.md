# TP 2

A lire impérativement avant de commencer quoi que ce soit, ce sont les règles que vous devrez appliquer tout au long du semestre:

<p align="center">
 <a href="https://gitlab.com/Adrien_Kourganoff/instructions_web_ocres_ing4/-/blob/master/README.md">Règles pour le semestre</a>
</p>

## Instructions



5. Utiliser Bootstrap pour :

   - Masquer la colonne de gauche sur mobile et sur tablette en mode portrait ([display utilities](https://getbootstrap.com/docs/4.2/utilities/display/))
   - Aligner les liens Collection et History à droite lorsque l'espace disponible devient insuffisant
   - Mettre en place le [menu déroulant](https://getbootstrap.com/docs/4.2/components/dropdowns/) (en haut à droite)

6. Remplacer toutes les tailles de police en pixel par des unités relatives (em ou rem)

7. Régler le viewport pour les mobiles

```html
<meta
  name="viewport"
  content="width=device-width, initial-scale=1.0, shrink-to-fit=no"
/>
```

Cela permet d'eviter que l'utilisateur zoom dans votre page web pour naviguer

8. Utiliser les **medias queries** pour :

   - Masquer le champs de recherche lorsque l'espace disponible devient insuffisant
   - Masquer les icônes twitter et facebook sur mobile
   - Ajuster la taille du texte aux 3 points de ruptures suivants : 1400px (grossir) / 600px (plus petit) / 450px (encore plus petit)

9. Redimensionner la fenêtre du navigateur ou émuler la taille du device à travers la console dévelopeur. Tester que la page est visuellement cohérente à toutes les résolutions. Faire les ajustements nécessaires avec les media queries.
