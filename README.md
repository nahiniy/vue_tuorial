# vue_tuorial

2. soit le tableau suivant :
pages : [
                        {
                            Lien: { text: 'Accueil', url: "accueil.html" },
                            titrePage: "Accueil",
                            contenu: "Je suis dans l'accueil "
                        },
                        {
                            Lien: { text: 'Principale', url: "principale.html" },
                            titrePage: "Principale",
                            contenu: "Je suis dans principale"
                        },
                        {
                            Lien: { text: 'Galerie', url: "gelerie.html" },
                            titrePage: "Galerie",
                            contenu: "Je suis dans Galerie "
                        }
                    ]
Utiliser les directives v-bind, v-for, @click pour optimiser le code en :
-	Affichant le contenu de la balise ul avec un seul balise il au lieu de trois
-	Ajouter la propriété active dans class de bootstrap à l’élément li courant
 
-	Modifier le contenu de l’élément div ayant pour id=contenu_modifiable par le contenu de l’élément courant
-	Ecrire un code scrpits vue qui modifie la couleur du navbar et du back-ground navbar simultanement en dark et light aux clicks
