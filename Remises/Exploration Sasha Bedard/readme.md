# Compte Rendu de l'exploration
## Par Sasha Bédard

Dans le cadre de mon rôle d'auxiliaire pour le cours de Motion Design, j'ai eu la chance d'organiser des ateliers de Blender. Comme je suis expert en 3D, un effet que j'apprécie particulièrement dans Blender est la déconstruction des mesh, qu'il réalise habituellement à l'aide d'un plugin. Cependant, je voulais relever un nouveau défi : recréer cet effet dans TouchDesigner de manière quasi-procédurale.

L'idée a pris forme après une session d'inspiration sur Pinterest, où j'ai découvert plusieurs styles visuels axés sur la fragmentation des formes en 3D. Motivé par l'envie de repousser mes compétences, je me suis lancé dans la reproduction de la déconstruction des mesh dans TouchDesigner, sans recourir aux plugins de Blender, mais en exploitant les outils natifs de TouchDesigner.

Pour commencer, j'ai consulté une vidéo YouTube qui expliquait comment déstructurer des mesh dans TouchDesigner. La vidéo présentait des techniques de conversion des SOP (Surface Operators) en CHOP (Channel Operators), ce qui m'a permis de mieux comprendre la manipulation des données 3D sous forme de canaux dans TouchDesigner. Cette méthode a servi de base pour construire mon effet de déconstruction.

Ensuite, j'ai enrichi le projet en ajoutant plusieurs améliorations. L'une des premières étapes a été de créer des animations de caméra qui suivent la déconstruction des mesh en temps réel. Plutôt que de choisir un mouvement linéaire simple, je suis allé pour des trajectoires complexes qui mettent en valeur la fragmentation. Ce choix visait à renforcer l'interaction visuelle entre la caméra et l'effet de déconstruction.

Pour le post-processing, j'ai intégré trois éléments principaux : du texte, un fond visuel et un léger flou. Le texte a été ajouté pour fournir des informations ou des titres à l'écran, contribuant à donner plus de contexte au rendu. Le fond visuel permet de mieux contraster les modèles en déconstruction, créant un arrière-plan simple mais efficace qui fait ressortir les détails de l'effet. Enfin, le léger flou a été utilisé pour adoucir les transitions et rendre l'ensemble plus homogène.

J'ai également synchronisé les changements de modèles avec le timing des animations pour maintenir une continuité visuelle dynamique tout au long du rendu. Cela permet d'assurer une transition fluide entre les différentes phases de la déconstruction et d'exploiter pleinement les capacités modulaires de TouchDesigner.

En conclusion, cette exploration m'a permis de mieux comprendre le potentiel de TouchDesigner dans le domaine de la 3D procédurale. Ce projet a enrichi mes compétences techniques et m'a aidé à mieux saisir comment l'art génératif peut créer des expériences visuelles immersives et engageantes.

À l'avenir, je compte approfondir cette approche en explorant de nouvelles interactions entre les SOP, CHOP et d'autres opérateurs, pour pousser encore plus loin l'animation procédurale dans TouchDesigner