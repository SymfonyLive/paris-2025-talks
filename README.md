# [SymfonyLive Paris 2025](https://live.symfony.com/2025-paris/) talks

> [!IMPORTANT]
> It's unfortunate that [videos aren't hosted on YouTube anymore](https://www.youtube.com/@SymfonyTv/videos), and most are [locked behind a paywall](https://live.symfony.com/replay), even years later 😔. <ins>If you’re a speaker, please consider sharing your insights in a blog post</ins>. It would really help beginners and uplift the entire community! 🤗

> [!NOTE]
> - All talks are in **French**.
> - You can send feedback and love to speakers on their social networks.
> - Social posts during the event: [Bluesky](https://bsky.app/search?q=%23symfony_live+since%3A2025-03-26+until%3A2025-03-30) · [Mastodon](https://mastodon.social/tags/symfony_live) · [Twitter](https://x.com/search?q=(%23symfony_live%20OR%20%40symfonylive)%20until%3A2025-03-30%20since%3A2025-03-26%20-filter%3Areplies&f=live)
> - [Photos during the event](https://pixi.live/gallery/symfonylive-paris-2025)

---

## Keynote · Symfony : 20 ans d'évolution vers la simplicité

[Slides](https://speakerdeck.com/fabpot/symfony-in-2025-scaling-to-0)  
[Video](https://live.symfony.com/account/replay/video/1091)  <sup>(behind paywall)</sup>  
~~Blog post~~

By [Fabien Potencier](https://connect.symfony.com/profile/fabpot)  
💻 on [![github](icon/github.svg) @fabpot](https://github.com/fabpot)  <sup>[💚](https://github.com/sponsors/fabpot)</sup>  
✍ on [🌐 fabien.potencier.org](https://fabien.potencier.org)  
💬 on [![bluesky](icon/bluesky.svg) @fabien.potencier.org](https://bsky.app/profile/fabien.potencier.org)
· [![twitter](icon/twitter.svg) @fabpot](https://twitter.com/fabpot)
· [![mastodon](icon/mastodon.svg) @fabpot@mastodon.social](https://mastodon.social/@fabpot)
· [![linkedin](icon/linkedin.svg) @fabienpotencier](https://www.linkedin.com/in/fabienpotencier)

---

## Le Composant Symfony Mapper

<dl>
  <dt>Description</dt>
  <dd>Le mapping est quelque chose que l'on retrouve dans de nombreux frameworks sur le web dans tous les langages de programmation. Doctrine, par exemple, possède un système de mapping assez complexe pour transformer la représentation de la base de données relationnelle en votre entité.
Après avoir parcouru l'historique de quelques années de discussion et de recherches de la communauté Symfony autour de ce domaine, nous allons étudier les besoins d'un tel composant dans Symfony. Nous analyserons en quoi il est différent du Serializer de Symfony, et quelles sont les solutions offertes par les frameworks populaires sur le Web. Enfin, nous présenterons le nouveau composant Mapper que j'ai proposé et ses différents usages entre la conception de l'API jusqu'aux cas d'utilisation quotidiens.</dd>
</dl>

[Slides](https://speakerdeck.com/soyuka/symfony-mapper-component)  
[Video](https://live.symfony.com/account/replay/video/1078)  <sup>(behind paywall)</sup>  
~~Blog post~~  
[Pull Request of `symfony/object-mapper`](https://github.com/symfony/symfony/pull/51741)  <sup>Merged 🎉</sup>

By [Antoine Bluchet](https://connect.symfony.com/profile/soyuka)  
💻 on [![github](icon/github.svg) @soyuka](https://github.com/soyuka)  <sup>[💚](https://github.com/sponsors/soyuka)</sup>  
✍ on [🌐 soyuka.me](https://soyuka.me/)  <sup>[![rss](icon/rss.svg)](https://soyuka.me/index.xml)</sup>  
💬 on [![bluesky](icon/bluesky.svg) @soyuka.me](https://bsky.app/profile/soyuka.me)
· [![mastodon](icon/mastodon.svg) @soyuka@phpc.social](https://phpc.social/@soyuka)
· [![twitter](icon/twitter.svg) @s0yuka](https://twitter.com/s0yuka)
· [![linkedin](icon/linkedin.svg) @soyuka](https://linkedin.com/in/soyuka)

---

## Postgres pour vos besoins NoSQL

<dl>
  <dt>Description</dt>
  <dd>Postgres est connu pour ses capacités SQL. Mais en fait, Postgres est aussi très capable de gérer du JSON. Je vais expliquer comment utiliser les fonctions JSON des versions récentes de Postgres pour gérer vos données moins structurées. Je vais aussi montrer l'utilisation des fonctionnalités JSON depuis Doctrine.</dd>
</dl>

[Slides](https://davidbu.ch/slides/2025-03-27-symfony-live-paris-postgres-json.html#1)  
[Video](https://live.symfony.com/account/replay/video/1063)  <sup>(behind paywall)</sup>  
[Blog post](https://davidbu.ch/mann/blog/2025-03-27/symfony-live-paris-postgres-json/)  
[Exemples and measures: postgres](https://github.com/dbu/postgres-json) / [MySQL](https://github.com/dbu/postgres-json/pull/2)

By [David Buchmann](https://connect.symfony.com/profile/dbu)  
💻 on [![github](icon/github.svg) @dbu](https://github.com/dbu)  
✍ on [🌐 davidbu.ch/mann/blog](https://davidbu.ch/mann/blog)  <sup>[![rss](icon/rss.svg)](https://davidbu.ch/mann/atom.xml)</sup>  
💬 on [![mastodon](icon/mastodon.svg) @dbu@phpc.social](https://phpc.social/@dbu)
· [![twitter](icon/twitter.svg) @dbu](https://twitter.com/dbu)
· [![linkedin](icon/linkedin.svg) @david-buchmann-…](https://linkedin.com/in/david-buchmann-5308654)

---

## Passkeys pour une authentification fluide et sécurisée

<dl>
  <dt>Description</dt>
  <dd>Dites adieu aux mots de passe fragiles et aux processus de connexion fastidieux ! Les passkeys et webauthn, une nouvelle technologie d'authentification native des navigateurs et systèmes d'exploitation, promettent une expérience utilisateur fluide et sécurisée. Dans cette conférence, nous explorerons le potentiel de webauthn pour votre site web en abordant les sujets suivants :
  - Présentation des passkeys
  - Présentation de webauthn
  - Intégration de webauthn dans les applications Symfony : démonstration pratique et bonnes pratiques
  - Cas d'utilisation concrets : authentification client, paiements sécurisés, gestion de comptes
  - Impact sur la sécurité et l'expérience utilisateur : vers un futur sans friction et sans compromis</dd>
</dl>

[Slides](https://rjanot.github.io/webauthn-sflive2025/)  
[Video](https://live.symfony.com/account/replay/video/1068)  <sup>(behind paywall)</sup>  
~~Blog post~~  
[Demo repository](https://github.com/rjanot/webauthn-demo-symfony)

By [Rémi Janot](https://connect.symfony.com/profile/rjanot)  
💻 on [![github](icon/github.svg) @rjanot](https://github.com/rjanot)  
_✍ blog not found_  
💬 on [![linkedin](icon/linkedin.svg) rjanot](https://www.linkedin.com/in/rjanot)

---

## Symfony UX : Points forts de 2024 et perspectives d'avenir

<dl>
  <dt>Description</dt>
  <dd>Symfony UX est un ensemble de composants conçus pour créer des interfaces front-end riches avec Symfony. Ce mois de décembre, il a fêté ses 4 ans (Joyeux anniversaire UX !).

  Quelle année 2024 pour Symfony UX !

  Nous passerons en revue tout ce qui s’est passé : nouveaux composants (Icon, Map), améliorations apportées à TwigComponent et LiveComponent, et nous discuterons de la philosophie et des orientations adoptées par l’équipe Symfony UX.

  Ensuite, nous explorerons l’avenir de Symfony UX en 2025, incluant une ou deux surprises !</dd>
</dl>

[Slides](https://speakerdeck.com/smnandre/symfony-ux-bilan-2024-et-perspective-davenir-fr)  
[Video](https://live.symfony.com/account/replay/video/1067)  <sup>(behind paywall)</sup>  
~~Blog post~~

By [Simon André](https://connect.symfony.com/profile/simonandre)  
💻 on [![github](icon/github.svg) @smnandre](https://github.com/smnandre)  <sup>[💚](https://github.com/sponsors/smnandre)</sup>  
_✍ blog not found_  
💬 on [![bluesky](icon/bluesky.svg) @smnandre.dev](https://bsky.app/profile/mtarld.bsky.social)
· [![twitter](icon/twitter.svg) @simonandre](https://twitter.com/simonandre)
· [![linkedin](icon/linkedin.svg) @smnandre](https://www.linkedin.com/in/smnandre)

---

## Rôles & permissions : développez une marque blanche avec du Feature Flipping

<dl>
  <dt>Description</dt>
  <dd>Les rôles et les permissions permettent de gérer d'une manière très fine les droits des utilisateurs : ce sont donc deux composants essentiels de la sécurité d'une application web.

  Nous ferons dans un premier temps un focus sur leurs différences et intérêts avant de voir comment les intégrer de manière très simple dans Symfony. Puis, nous verrons, au travers d'un retour d'expérience, comment tirer parti des rôles et permissions pour mettre en place une marque blanche, du "Feature Flipping" et un système de profils utilisateurs dans une application web.

  Découvrez comment les implémenter dans votre base de code, mais aussi des exemples d'outils à mettre en place dans votre CI et votre monitoring afin d'être sûr de ne pas avoir de raté.</dd>
</dl>

[Slides](https://slides.com/florianbogey/sf-live-roles-permissions)  
[Video](https://live.symfony.com/account/replay/video/1070)  <sup>(behind paywall)</sup>  
~~Blog post~~

By [Florian Bogey](https://connect.symfony.com/profile/florianlyon)  
💻 on [![github](icon/github.svg) @Florian-B](https://github.com/Florian-B)  
✍ _blog not found_  
💬 on [![twitter](icon/twitter.svg) @Florian_FB](https://twitter.com/Florian_FB)
· [![linkedin](icon/linkedin.svg) florian-bogey-…](https://www.linkedin.com/in/florian-bogey-96371710b)

---

## API Platform sans Doctrine

<dl>
  <dt>Description</dt>
  <dd>API Platform est l’outil de référence pour créer des APIs perfectionnées, avec une intégration fluide à Doctrine et à diverses sources de données. Mais que faire si l’on souhaite accéder à d’autres types de bases de données ou optimiser les requêtes pour des cas d’usage spécifiques ? Est-il possible de se passer de Doctrine ?</dd>
</dl>

[Slides](https://jerome.tamarelle.net/slides/2025-03-27-SymfonyLive-Paris-2025-API_Platform_sans_Doctrine.pdf)  
[Video](https://live.symfony.com/account/replay/video/1079)  <sup>(behind paywall)</sup>  
~~Blog post~~

By [Jérôme Tamarelle](https://connect.symfony.com/profile/gromnan)  
💻 on [![github](icon/github.svg) @GromNaN](https://github.com/GromNaN)  
✍ [🌐 dev.to/gromnan](https://dev.to/gromnan/)  <sup>[![rss](icon/rss.svg)](https://dev.to/feed/gromnan/)</sup>  
💬 on [![twitter](icon/twitter.svg) @GromNaN](https://twitter.com/GromNaN)
· [![linkedin](icon/linkedin.svg) jerometamarelle](https://www.linkedin.com/in/jerometamarelle)

---

## Développer plus vite grâce à FrankenPHP

<dl>
  <dt>Description</dt>
  <dd>L’une des forces de Symfony est son mécanisme de cache (les fichiers stockés dans "var/cache") qui permet aux composants du framework tels que le conteneur d’injection de dépendance et le routeur ainsi qu’à de nombreux bundles d'être ultra-rapides en production.

  Cependant, pendant le développement, la régénération de ce cache peut entraîner des lenteurs et rendre le travail des programmeuses et des programmeurs pénible. En effet, à chaque fois qu'un fichier PHP, un fichier de configuration ou un template Twig est modifié, tout ou partie du cache doit être régénéré.

  La dernière version de FrankenPHP contient une nouvelle fonctionnalité qui, couplée au mode worker, peut changer la donne : les watchers.

  Après avoir présenté le fonctionnement du mécanisme de cache de Symfony, et comment en tirer partie dans nos applications et bundles, nous découvrirons comment utiliser les watchers et le mode worker de FrankenPHP pour que les changements apportés à notre code soient reflétés quasi-instantanément dans notre navigateur, et ainsi nous éviter la frustration des temps de chargement long en dev.</dd>
</dl>

[Slides](https://speakerdeck.com/dunglas/develop-faster-with-frankenphp)  
[Video](https://live.symfony.com/account/replay/video/1064)  <sup>(behind paywall)</sup>  
[Blog post](https://dunglas.dev/2025/03/develop-faster-with-frankenphp/)

By [Kévin Dunglas](https://connect.symfony.com/profile/dunglas)  
💻 on [![github](icon/github.svg) @dunglas](https://github.com/dunglas)  <sup>[💚](https://github.com/sponsors/dunglas)</sup>  
✍ on [🌐 dunglas.dev](https://dunglas.dev/)  <sup>[![rss](icon/rss.svg)](https://dunglas.dev/feed/)</sup>  
💬 on [![mastodon](icon/mastodon.svg) @dunglas@mastodon.social](https://mastodon.social/@dunglas)
· [![bluesky](icon/bluesky.svg) @dunglas.dev](https://bsky.app/profile/dunglas.dev)
· [![twitter](icon/twitter.svg) @dunglas](https://twitter.com/dunglas)
· [![linkedin](icon/linkedin.svg) dunglas](https://www.linkedin.com/in/dunglas)

---

## Où sont passées les femmes de l'histoire de la tech ?

<dl>
  <dt>Description</dt>
  <dd>Ada Lovelace, Hedy Lamarr, les "ENIAC Girls," Grace Hopper, Joan Clarke... Issu du rôle de calculatrice, le métier de développeur était initialement considéré comme un travail de femmes, tandis que la conception matérielle était vue comme un travail d'hommes. Mais qui sont ces femmes qui ont façonné le monde de la technologie ? Pourquoi entend-on si peu parler d'elles ? Avec Laura Durieux, vous tenterez de rétablir les faits petit à petit et de fournir des modèles inspirants en tech, dont vous avez toujours eu besoin.</dd>
</dl>

~~Slides~~  
[Video](https://live.symfony.com/account/replay/video/1080)  <sup>(free 🙌)</sup>  
~~Blog post~~

By [Laura Durieux](https://connect.symfony.com/profile/devgirl_)  
💻 on [![github](icon/github.svg) @Lauwed](https://github.com/Lauwed)  
💬 on [![twitter](icon/twitter.svg) @devgirl__](https://twitter.com/devgirl__)
· [![linkedin](icon/linkedin.svg) devgirl](https://www.linkedin.com/in/devgirl)

---

## Asynchrone avec Symfony Messenger et Mercure

<dl>
  <dt>Description</dt>
  <dd>Générer des PDF, des CSV, ou faire des traitements lourd lors du traitement d'une requête HTTP impacte lourdement les performances de l'application.

  Pour pallier ce problème nous pouvons avoir recours à l'utilisation d'un système de asynchrone. Le composant Messenger sera un super allier pour nous faciliter cette tache.

  Cependant, comment prévenir le client que son PDF est prêt ou que son import de données est fini ? Mercure nous simplifiera la tache pour notifier le client en temps réel.

  Et si notre site est une SPA, pouvons nous tirer parti de ces composant pour rafraîchir notre application avec seulement 3 lignes de code JS ? Venez le découvrir !</dd>
</dl>

[Slides](https://s.lyrixx.info/async)  
[Video](https://live.symfony.com/account/replay/video/1065)  <sup>(behind paywall)</sup>  
~~Blog post~~  
[Demo repository](https://s.lyrixx.info/async-demo)

By [Grégoire Pineau](https://connect.symfony.com/profile/lyrixx)  
💻 on [![github](icon/github.svg) @lyrixx](https://github.com/lyrixx)  <sup>[💚](https://github.com/sponsors/lyrixx)</sup>  
✍ on [🌐 jolicode.com/blog](https://jolicode.com/qui-sommes-nous/equipe/gregoire-pineau)  <sup>[![rss](icon/rss.svg)](https://jolicode.com/feed.rss)</sup>  
💬 on [![bluesky](icon/bluesky.svg) @lyrixx.bsky.social](https://bsky.app/profile/lyrixx.bsky.social)
· [![twitter](icon/twitter.svg) @lyrixx](https://twitter.com/lyrixx)
· [![mastodon](icon/mastodon.svg) @lyrixx@mastodon.social](https://mastodon.social/@lyrixx)

---

## Atteindre la qualité d'une SPA avec HTMX et Twig

<dl>
  <dt>Description</dt>
  <dd>Découvrez comment HTMX peut transformer votre façon de développer en apportant la puissance et la flexibilité des Single Page Applications (SPA) à vos projets Symfony, sans écrire de JavaScript !</dd>
</dl>

[Slides](https://jolicode.github.io/htmx-conf/)  
[Video](https://live.symfony.com/account/replay/video/1084)  <sup>(behind paywall)</sup>  
[Blog post](https://damienalexandre.fr/post/parler-dhtmx-a-symfony-live-2025)  
[Demo repository](https://github.com/jolicode/symfony-htmx-demo)

By [Damien Alexandre](https://connect.symfony.com/profile/damienalexandre)  
💻 on [![github](icon/github.svg) @damienalexandre](https://github.com/damienalexandre)  
✍ on [damienalexandre.fr/posts](https://damienalexandre.fr/posts)  <sup>[![rss](icon/rss.svg)](https://damienalexandre.fr/latest?format=rss)</sup>  
💬 on [![bluesky](icon/bluesky.svg) @damienalexandre.bsky.social](https://bsky.app/profile/damienalexandre.bsky.social)
· [![linkedin](icon/linkedin.svg) damienalexandre](https://www.linkedin.com/in/damienalexandre)

---

## Du lego de composants pour un bundle Gotenberg !

<dl>
  <dt>Description</dt>
  <dd>Générer un document PDF est un besoin commun dans nos projet, notamment pour de l’e-commerce, depuis que wkhtmltopdf est déprécié, il est difficile de trouver une librairie simple à utiliser / installer pour générer des PDFs.

  Parmi les outils disponibles, nous avons choisi de nous concentrer sur Gotenberg.

  Le SDK natif ne nous a pas semblé offrir une Développeur eXpérience(DX) optimale pour une intégration Symfony. Nous avons donc décidé de nous lancer dans la création « from scratch » d’un Bundle dédié avec une DX adaptée aux développeurs Symfony... et aux utilisateurs de PHPStorm !

  Du fulgurant HttpClient au méconnu Webhook, voyons comment la myriade de composants Symfony peuvent nous aider à faire de la génération PDF une tâche rapide et simple à mettre en place.

  Pour ce faire, nous nous sommes posé quelques questions que nous couvrirons ensemble !

  * Comment exposer une configuration simple et sémantique ?
  * Comment s’assurer d’une bonne auto-complétion ?
  * Comment faciliter le debug ?
  * Comment maximiser l’efficience de la mémoire ?
  * Comment faire de la génération asynchrone facilement ?

  Viendez et découvrez comment générer des PDF’s devient désormais aussi simple que d’utiliser Twig !</dd>
</dl>

[Slides](https://jean-beru.github.io/2025_03_sflive_gotenberg)  
[Video](https://live.symfony.com/account/replay/video/1082)  <sup>(behind paywall)</sup>  
[Blog post](https://github.com/StevenRenaux/GotenbergBundle-Article)  
[Code of `sensiolabs/gotenberg-bundle`](https://github.com/sensiolabs/GotenbergBundle)  
[Demo repository](https://github.com/StevenRenaux/GotenbergBundle-Article)

By [Adrien Roches](https://connect.symfony.com/profile/neirda24)  
💻 on [![github](icon/github.svg) @Neirda24](https://github.com/Neirda24)  
✍ on [🌐 blog.roc-it.tech](https://blog.roc-it.tech/)  <sup>[![rss](icon/rss.svg)](https://blog.roc-it.tech/rss/)</sup>  
💬 on [![twitter](icon/twitter.svg) @AdrienRoches](https://twitter.com/AdrienRoches)
· [![bluesky](icon/bluesky.svg) @adrienroches.bsky.social](https://bsky.app/profile/adrienroches.bsky.social)
· [![mastodon](icon/mastodon.svg) @neirda@phpc.social](https://phpc.social/@neirda)
· [![linkedin](icon/linkedin.svg) @adrien-roches](https://linkedin.com/in/adrien-roches)

And [Hubert Lenoir](https://connect.symfony.com/profile/hubert_lenoir)  
💻 on [![github](icon/github.svg) @Jean-Beru](https://github.com/Jean-Beru)  
_✍ blog not found_  
💬 on [![twitter](icon/twitter.svg) @jean_beru](https://twitter.com/jean_beru)
· [![linkedin](icon/linkedin.svg) @hubert-lenoir](https://linkedin.com/in/hubert-lenoir)

---

## Tirez profit de Messenger pour améliorer votre architecture

<dl>
  <dt>Description</dt>
  <dd>Symfony Messenger est principalement vu comme un composant pour déléguer des traitements en tâche de fond.
  Mais est-il réellement limité à ce cas d'utilisation?

  Dans cette présentation nous verrons à travers une session de refactoring comment l'utilisation de Messenger peut avant tout être bénéfique à l'architecture et au découplage de nos applications.</dd>
</dl>

[Slides](https://speakerdeck.com/tucksaun/tirez-profit-de-messenger-pour-ameliorer-votre-architecture)  
[Video](https://live.symfony.com/account/replay/video/1096)  <sup>(behind paywall)</sup>  
~~Blog post~~

By [Tugdual Saunier](https://connect.symfony.com/profile/tucksaun)  
💻 on [![github](icon/github.svg) @tucksaun](https://github.com/tucksaun)  
_✍ blog not found_  
💬 on [![twitter](icon/twitter.svg) @tucksaun](https://twitter.com/tucksaun)
· [![bluesky](icon/bluesky.svg) @tucksaun.bsky.social](https://bsky.app/profile/tucksaun.bsky.social)
· [![mastodon](icon/mastodon.svg) @tucksaun@mastodon.social](https://mastodon.social/@tucksaun)
· [![linkedin](icon/linkedin.svg) @tugdual-saunier](https://linkedin.com/in/tugdual-saunier)

---

##  Développer avec API Platform 4, ça change quoi ?

<dl>
  <dt>Description</dt>
  <dd>Énormément d'eau a coulé sous les ponts depuis la version 2.6 d'API Platform.

  En effet, ce framework permettant de réaliser des APIs a une première fois fait peau neuve lors de son passage en 3.0, en redéfinissant totalement la DX et la manière dont il est possible de l'utiliser.
  Et en septembre dernier, API Platform s'est à nouveau grandement renouvelé, proposant de nombreuses améliorations et de nouveaux points d'extensions.

  Ainsi, comme vous pourrez vous en douter, utiliser API Platform en version 4 n'a plus rien à voir avec son utilisation en version 2.6.
  Et donc, une manière de faire en version 2.6 est très probablement obsolète, voire invalide en version 4, car elle irait à l'encontre du framework.

  Nous verrons donc ensemble ce que veut dire développer une API avec API Platform dans sa version 4, et quels paradigmes de développement absolument éviter afin d'éviter de se battre contre le framework.</dd>
</dl>

~~Slides~~  
[Video](https://live.symfony.com/account/replay/video/1083)  <sup>(behind paywall)</sup>  
~~Blog post~~

By [Mathias Arlaud](https://connect.symfony.com/profile/mtarld)  
💻 on [![github](icon/github.svg) @mtarld](https://github.com/mtarld)  <sup>[💚](https://github.com/sponsors/mtarld)</sup>  
✍ on [🌐 baksla.sh/blog](https://baksla.sh/blog)  
💬 on [![bluesky](icon/bluesky.svg) @mtarld.bsky.social](https://bsky.app/profile/mtarld.bsky.social)
· [![twitter](icon/twitter.svg) @matarld](https://twitter.com/matarld)
· [![linkedin](icon/linkedin.svg) matarld](https://www.linkedin.com/in/matarld)

---

## Keynote · Les Nouveautés de Symfony 7.3

~~Slides~~  
[Video](https://live.symfony.com/account/replay/video/1092)  <sup>(behind paywall)</sup>  
~~Blog post~~

By [Nicolas Grekas](https://connect.symfony.com/profile/nicolas-grekas)  
💻 on [![github](icon/github.svg) @nicolas-grekas](https://github.com/nicolas-grekas)  <sup>[💚](https://github.com/sponsors/nicolas-grekas)</sup>  
✍ on [🌐 medium.com/@nicolas.grekas](https://medium.com/@nicolas.grekas)  <sup>[![rss](icon/rss.svg)](https://medium.com/feed/@nicolas.grekas)</sup>  
💬 on [![twitter](icon/twitter.svg) @nicolasgrekas](https://twitter.com/nicolasgrekas)
· [![bluesky](icon/bluesky.svg) @nicolasgrekas.bsky.social](https://bsky.app/profile/nicolasgrekas.bsky.social)
· [![mastodon](icon/mastodon.svg) @nicolasgrekas@phpc.social](https://phpc.social/@nicolasgrekas)
· [![linkedin](icon/linkedin.svg) @nicolasgrekas](https://linkedin.com/in/nicolasgrekas)

---

### Bonus : 8 Lightning Talks

## User-Agent : Plongée dans l'histoire d'un header web mystérieux

<dl>
  <dt>Description</dt>
  <dd>Savez-vous ce que raconte votre navigateur aux sites web que vous visitez ? Derrière une ligne de texte étrange se cache une histoire fascinante des débuts d'internet, pleine de rivalités et d'astuces pour que les sites s'affichent correctement sur tous les écrans. Découvrez comment le "User-Agent" a évolué, des premiers navigateurs comme Mosaïque aux géants actuels comme Chrome, en passant par des techniques parfois surprenantes pour assurer la compatibilité.</dd>
</dl>

~~Slides~~  
[Video](https://live.symfony.com/account/replay/video/1122) *starting at 00:22*   <sup>(behind paywall)</sup>  
~~Blog post~~

By [Benjamin Clay](https://connect.symfony.com/profile/ternel)  
💻 on [![github](icon/github.svg) @ternel](https://github.com/ternel)  
✍ on [🌐 baksla.sh/blog](https://baksla.sh/blog)  
💬 on [![bluesky](icon/bluesky.svg) @ternel.bsky.social](https://bsky.app/profile/ternel.bsky.social)
· [![mastodon](icon/mastodon.svg) @ternel@mastodon.social](https://mastodon.social/@ternel)
· [![twitter](icon/twitter.svg) @ternel](https://x.com/ternel)
· [![linkedin](icon/linkedin.svg) benjaminclay](https://linkedin.com/in/benjaminclay)


## Simplifiez vos formulaires Symfony grâce aux attributs PHP 8

<dl>
  <dt>Description</dt>
  <dd>Découvrez comment les attributs PHP 8 peuvent révolutionner la création de formulaires dans Symfony. Oubliez les FormTypes traditionnels et concentrez-vous sur vos DTO : des attributs directement dans vos classes vous permettront de définir et configurer vos formulaires de manière intuitive et concise. Validation,  events, transformers... explorez le potentiel de cette approche pour un développement plus rapide et agréable.</dd>
</dl>

~~Slides~~  
[Video](https://live.symfony.com/account/replay/video/1122) *starting at 04:58*   <sup>(behind paywall)</sup>  
~~Blog post~~

By [Benjamin Georgeault](https://connect.symfony.com/profile/WedgeSama)  
💻 on [![github](icon/github.svg) @wedgesama](https://github.com/wedgesama)  
_✍ blog not found_  
💬 on [![twitter](icon/twitter.svg) @WedgeSama](https://twitter.com/WedgeSama)
· [![mastodon](icon/mastodon.svg) @wedgesama@mastodon.social](https://mastodon.social/@wedgesama)
· [![bluesky](icon/bluesky.svg) @wedgesama.bsky.social](https://bsky.app/profile/wedgesama.bsky.social)
· [![linkedin](icon/linkedin.svg) benjamin-georgeault-…](https://linkedin.com/in/benjamin-georgeault-67212172)


## MCP : Unifier les outils pour les LLM

<dl>
  <dt>Description</dt>
  <dd>Démonstration de MCP, un protocole qui permet aux LLM d'interagir avec le monde extérieur en leur fournissant des outils. L'orateur montre comment MCP permet à un LLM de créer un livre dans une base de données et explique le fonctionnement du protocole.</dd>
</dl>

[Slides](https://speakerdeck.com/lyrixx/mcp-symfony-live-paris-2025)  
[Video](https://live.symfony.com/account/replay/video/1122) *starting at 12:17*   <sup>(behind paywall)</sup>  
[Blog post](https://jolicode.com/blog/mcp-the-open-protocol-that-turns-llm-chatbots-into-intelligent-agents)

By [Grégoire Pineau](https://connect.symfony.com/profile/lyrixx)  
💻 on [![github](icon/github.svg) @lyrixx](https://github.com/lyrixx)  <sup>[💚](https://github.com/sponsors/lyrixx)</sup>  
✍ on [🌐 jolicode.com/blog](https://jolicode.com/qui-sommes-nous/equipe/gregoire-pineau)  <sup>[![rss](icon/rss.svg)](https://jolicode.com/feed.rss)</sup>  
💬 on [![bluesky](icon/bluesky.svg) @lyrixx.bsky.social](https://bsky.app/profile/lyrixx.bsky.social)
· [![twitter](icon/twitter.svg) @lyrixx](https://twitter.com/lyrixx)
· [![mastodon](icon/mastodon.svg) @lyrixx@mastodon.social](https://mastodon.social/@lyrixx)


## Gitingest : Libérez la Puissance des LLM avec Votre Code GitHub

<dl>
  <dt>Description</dt>
  <dd>Découvrez Gitingest, l'outil révolutionnaire qui transforme votre code GitHub en un format optimisé pour les LLM. En quelques clics, convertissez vos dépôts en Markdown structuré et générez des prompts intelligents pour une analyse de code, une documentation et une collaboration assistées par IA. Simplifiez l'intégration des LLM dans votre workflow et exploitez leur plein potentiel pour des revues de code automatisées, l'onboarding de nouveaux développeurs et bien plus encore.</dd>
</dl>

[Slides](https://slides.com/imentroudi/gitingest-exploitez-la-puissance-des-llms-avec-votre-code)  
[Video](https://live.symfony.com/account/replay/video/1122) *starting at 16:13*   <sup>(behind paywall)</sup>  
~~Blog post~~

By [Imen Ezzine](https://connect.symfony.com/profile/imen-ezzine)  
💻 on [![github](icon/github.svg) @imenezzine](https://github.com/imenezzine)  
✍ on [🌐 medium.com/the-sensiolabs-tech-blog](https://medium.com/the-sensiolabs-tech-blog)  <sup>[![rss](icon/rss.svg)](https://medium.com/feed/the-sensiolabs-tech-blog)</sup>  
💬 on [![twitter](icon/twitter.svg) @imenezzine1](https://twitter.com/imenezzine1)
· [![linkedin](icon/linkedin.svg) imen-ezzine-…](https://linkedin.com/in/imen-ezzine-09938a45)


## ShapeUp : Quand Scrum Devient Triste, l'Histoire de Dave, Alice et Huguette

<dl>
  <dt>Description</dt>
  <dd>Dave, Alice et Huguette font du Scrum, mais quelque chose ne va pas. Entre les estimations floues en points et une vélocité capricieuse, ils cherchent une autre voie. Découvrez comment la méthode ShapeUp, adaptée par Monsieur Biz, transforme leur manière de travailler en se concentrant sur des cycles courts et concrets, des "cacahuètes" à construire, pour finalement voir des "feux d'artifice" de satisfaction. Une présentation éclair pour comprendre comment cette approche peut révolutionner le quotidien des équipes web.</dd>
</dl>

~~Slides~~  
[Video](https://live.symfony.com/account/replay/video/1122) *starting at 22:18*   <sup>(behind paywall)</sup>  
~~Blog post~~

By [Jacques Bodin-Hullin](https://connect.symfony.com/profile/jacquesbh)  
💻 on [![github](icon/github.svg) @jacquesbh](https://github.com/jacquesbh)  
✍ on [🌐 monsieurbiz.com/fr/blog](https://monsieurbiz.com/fr/blog/) & [🌐 jacques.sh](https://jacques.sh)  <sup>[![rss](icon/rss.svg)](https://jacques.sh/atom.xml)</sup>  
💬 on [![twitter](icon/twitter.svg) @jacquesbh](https://x.com/jacquesbh)
· [![bluesky](icon/bluesky.svg) @jacquesbh.bsky.social](https://bsky.app/profile/jacquesbh.bsky.social)
· [![linkedin](icon/linkedin.svg) …-jacques-bodin-hullin-…](https://linkedin.com/in/%F0%9F%A6%84-jacques-bodin-hullin-9a36081a/)


## Il y a 20 ans : Retour sur SfContext, le cœur magique de Symfony 1

<dl>
  <dt>Description</dt>
  <dd>À l'occasion des 20 ans de Symfony, replongeons-nous dans l'histoire de ce framework en explorant SfContext, une classe centrale de Symfony 1. Découvrez comment ce "singleton" aux multiples facettes permettait d'accéder à tout, de la gestion des formulaires à l'envoi d'emails, et comment son héritage a façonné les  versions actuelles de Symfony.</dd>
</dl>

~~Slides~~  
[Video](https://live.symfony.com/account/replay/video/1122) *starting at 26:04*   <sup>(behind paywall)</sup>  
~~Blog post~~

By [Jérémy Romey](https://connect.symfony.com/profile/jeremyfreeagent)  
💻 on [![github](icon/github.svg) @jeremyFreeAgent](https://github.com/jeremyFreeAgent)  
_✍ blog not found_  
💬 on [![twitter](icon/twitter.svg) @jeremyFreeAgent](https://twitter.com/jeremyFreeAgent)
· [![bluesky](icon/bluesky.svg) @jeremyfreeagent.bsky.social](https://bsky.app/profile/jeremyfreeagent.bsky.social)
· [![linkedin](icon/linkedin.svg) jeremyfreeagent](https://www.linkedin.com/in/jeremyfreeagent)


## Flow : Orchestrez vos données visuellement avec PHP !

<dl>
  <dt>Description</dt>
  <dd>Découvrez Flow, une librairie PHP innovante pour l'orchestration de données. Basée sur les principes de la programmation fonctionnelle et du Flow-Based Programming, Flow vous permet d'assembler votre code de manière intuitive et d'exploiter la puissance de l'asynchrone pour des traitements de données efficaces.</dd>
</dl>

[Slides](https://speakerdeck.com/matyo91/flow-introduction)  
[Video](https://live.symfony.com/account/replay/video/1122) *starting at 30:28*   <sup>(behind paywall)</sup>  
~~Blog post~~

By [Mathieu Ledru](https://connect.symfony.com/profile/matyo91)  
💻 on [![github](icon/github.svg) @matyo91](https://github.com/matyo91)  
✍ on [🌐 blog.darkwood.com](https://blog.darkwood.com)  <sup>[![rss](icon/rss.svg)](https://feeds.feedburner.com/darkwood-com/blog)</sup>  
💬 on [![bluesky](icon/bluesky.svg) @mtarld.bsky.social](https://bsky.app/profile/mtarld.bsky.social)
· [![twitter](icon/twitter.svg) @matyo91](https://twitter.com/matyo91)
· [![linkedin](icon/linkedin.svg) mathieu-ledru](https://linkedin.com/in/mathieu-ledru)


## Agents IA génératifs : La révolution 2025

<dl>
  <dt>Description</dt>
  <dd>Découvrez comment les nouveaux outils d'IA générative en PHP, comme LLM Chain, Elhant et Neuron, simplifient l'intégration de l'intelligence artificielle dans vos applications. Apprenez comment enrichir les réponses des modèles de langage avec vos propres données grâce au RAG et comment les agents IA, pilotés par le protocole MCP, peuvent interagir avec votre environnement pour automatiser des tâches et transformer votre travail. 2025 sera l'année où ces technologies deviendront incontournables !</dd>
</dl>

[Slides](https://speakerdeck.com/welcomattic/2025-lannee-des-agents-genia)  
[Video](https://live.symfony.com/account/replay/video/1122) *starting at 37:32*   <sup>(behind paywall)</sup>  
~~Blog post~~

By [Mathieu Santostefano](https://connect.symfony.com/profile/welcomattic)  
💻 on [![github](icon/github.svg) @welcoMattic](https://github.com/welcoMattic)  <sup>[💚](https://github.com/sponsors/welcoMattic)</sup>  
✍ on [🌐 blog.welcomattic.com](https://blog.welcomattic.com/)  <sup>[![rss](icon/rss.svg)](https://blog.welcomattic.com/index.xml)</sup>  
💬 on [![bluesky](icon/bluesky.svg) @welcomattic.com](https://bsky.app/profile/welcomattic.com)
· [![mastodon](icon/mastodon.svg) @welcomattic@phpc.social](https://phpc.social/@welcomattic)
· [![linkedin](icon/linkedin.svg) msantostefano](https://linkedin.com/in/msantostefano)
