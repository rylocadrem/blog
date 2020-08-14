---
layout: breve
title : "Logique de base"
name: "logique-base"
categories: rationalite
---

Lisez l'article complet ici : [Introduction à la pensée critique]({{ site.baseurl }}{% post_url rationalite/2020-08-14-introduction-pensee-critique %})
{: .read-full-info}

## Implication, contraposée, réciproque, équivalence

En logique ces quatre termes sont centraux.

L'implication exprime une relation de causalité selon laquelle une proposition en entraine une autre si elle est vraie. Elle se note $$A \Rightarrow B$$ et se lit *A implique B*.

La contraposée d'une implication est sa réécriture sous une forme négative. Elle a exactement la même valeur logique. La contraposée de $$A \Rightarrow B$$ (A implique B) est $$\neg B \Rightarrow \neg A$$ (non B implique non A).

La réciproque d'une implication est son inverse. Elle n'a pas la même valeur logique. La réciproque de $$A \Rightarrow B$$ (A implique B) est $$B \Rightarrow A$$ (B implique A).

On parle d'équivalence quand une implication et sa réciproque sont toutes les deux vraies. Elle se note $$A \Leftrightarrow B$$ et se lit *A équivaut à B*. On dit aussi que *A est nécessaire et suffisant à B*.

## Modus Ponens et Modus Tollens

Derrière ces termes latins se cachent deux principes très simples et fondamentaux de la logique.

Le *modus ponens* est la *déduction du conséquent*. C'est à dire que si *A implique B* et que *A est vrai*, alors *B est vrai*. On écrit formellement cette relation :

$$A, A \Rightarrow B \vdash B$$

Cela se lit *de A et A implique B on déduit B*.

Par exemple :

1. On sait que tous les poissons respirent sous l'eau. ($$A \Rightarrow B$$)
2. Or le saumon est un poisson. ($$A$$)
3. Donc le saumon respire sous l'eau. ($$B$$)

Le *modus tollens* est la *validité de la contraposée*. La contraposée de *A implique B* est *non A implique non B*. On écrit formellement cette relation :

$$A \Rightarrow B \vdash \neg B \Rightarrow \neg A$$

Cela se lit *de A implique B on déduit non B implique non A*.

Par exemple :

1. On sait que tous les poissons respirent sous l'eau. ($$A \Rightarrow B$$)
2. Or l'ours ne respire pas sous l'eau. ($$\neg B$$)
3. Donc l'ours n'est pas un poisson. ($$\neg A$$)

## Affirmation du conséquent et négation de l'antécédent

Les deux principes précédents sont logiquement valides, mais il existe deux raisonnements fallacieux très similaires dans leur forme qui sont logiquement invalides : l'*affirmation du conséquent* et la *négation de l'antécédent*.

L'*affirmation du conséquent* c'est considérer une condition suffisante comme nécessaire. Elle dit que si *A implique B* et que *B est vrai*, alors *A est vrai*. On écrit formellement cette affirmation fausse :

$$B, A \Rightarrow B \vdash A$$

Cela se lit *de B et A implique B on déduit A*.

Par exemple :

1. On sait que tous les poissons respirent sous l'eau. ($$A \Rightarrow B$$)
2. Or le crabe respire sous l'eau. ($$B$$)
3. Donc le crabe est un poisson. ($$A$$)

La *négation de l'antécédent* c'est considérer que la réciproque d'une implication est toujours vraie. Elle dit que si *A implique B* alors *non A implique non B*. On écrit formellement cette affirmation fausse :

$$A \Rightarrow B \vdash \neg A \Rightarrow \neg B$$

Cela se lit *de A implique B on déduit non A implique non B*.

Par exemple :

1. On sait que tous les poissons respirent sous l'eau. ($$A \Rightarrow B$$)
2. Or le crabe n'est pas un poisson. ($$\neg A$$)
3. Donc le crabe ne respire pas sous l'eau. ($$\neg B$$)
