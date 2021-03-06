# Masque {#core-ref:327ad491-06df-4e5b-b49a-695c75439fe1}
 
Les masques permettent de changer la visibilité des attributs d'un document.

Ainsi, il est possible de définir pour chaque attribut de la famille sa
nouvelle visibilité, ainsi que de changer son caractère obligatoire.

Remarques :

*   il est important ici de rappeler que la visibilité des attributs ne garantit
    aucunement la confidentialité des informations, puisque les attributs Hidden
    sont quand même présents dans la dom
*   comme dans le document, les visibilités des attributs structurants impactent
    celles des attributs qu'ils contiennent. Ainsi, il est souvent plus efficace
    de changer la visibilité d'une *frame* que de l'ensemble de ses attributs
    (voir le [calcul de visibilité][computed_visibility] pour plus de détails).

<!-- links -->
[computed_visibility]: #core-ref:8349d1e6-ad9b-4c51-957e-b3f63497354c
