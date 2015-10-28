
# LITTERATURENN

This project is inspired from the DNN work in neural style. You can generate "art" from paintings and other work of visual art, or at least visuals that look like art.

**This project will research if you can generate litterature "art" in poetry and novel from previous author's work**

## CASE 1 : Moliere (Theater)

```
th sample.lua cv/moliere.t7
```

Sample output sounds and looks like old French from Molière. It is elegant and one could try to make sense out of it:

```
Me quoi qu'il premente tous deux mise, ou de la mauvres.

ANSELME.

Enfin, j'aime la cille n'effronteudement;
Qu'il m'a point qui changeant que nous fortions,
Oux les obstacles de ce diage malgré.
Je ne me point tâquant, je vous frapploie.

ANDRÈS.

Et ma mort, est trop décemisser ma connoisse;
Ce qui donc nous avez chérime, et soit fuir.
Celle qu'il me veut poyit qu'il nous est mon amour!
La vie! mon père s'aimani qui doit: je sais à beaucoup,
Et que tout leur soin bien qu'il perfide entange:
Mais aussi.


SCÈNE IXI.--POLVIOS.

Ma cole l'entre il faux feindre avec
De bien qu'encore.

LÉLIE.

                            On vions, ce n'est pas la gerrage.
Votre promption, par là le noble tana d'espérend
```

However, even children will recognize it is not proper french.

Results are thus negative

## CASE 2 : PAUL VERLAINE (Poet)

Paul Verlaine is a 19th century French surrealist poet.

```
th sample.lua cv/verlaine.t7
```

Sample generated ouput:

```
Mérat et moins Deroux)es.
On celair escorphe et les ont où nos figleux,
Riance en toutes les ailhessients.
Et ne vigleme et qui je sais dirien incerse,
Lointez et la chose et l'aire glein de sox
Et de mon dormez, peil, et dirent font tenselle,
La Avoit de la tière et fort aux funemelles.

```

Like Molière, this is based on the complete works of the author. The output could be interpreted as avant-garde poem. However it clearly suffers from lack of data.

Results are neutral and could be reused for another project but unusable in production.


## CASE 3 : ANDRÉ BRETON (Author, Poet)

French Author

*Status: Data Input being prepared*
