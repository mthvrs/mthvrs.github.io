
**Ce document n'a pas été rédigé par un professionnel**; tout ce qui figure ici est basé sur des connaissances personnelles et des sources fiables consultables à la fin de ce document. Nombreuses de celles-ci sont rédigées en anglais. Comme je l'ai déjà dit, je ne suis pas un professionnel, que ce soit en termes de sécurité numérique ou d'écriture journalistique. Néanmoins, je suis convaincu que ce que j'ai écrit est fiable et mérite d'être considéré comme un "article d'opinion" sérieux. 

<br>

**Table des matières:**

1. Préambule
2. Argumentation
	1. Introduction
	2. Zoom
	3. WhatsApp
	4. Conclusion
3. Sources
4. Contact

<br>

<br>

<br>

## 2. Arguments à l'encontre de Zoom, WhatsApp, et autres.

<b>Introduction |</b> WhatsApp et Zoom ne doivent pas être utilisés dans un cadre professionnel: ils (ainsi que de nombreuses autres applications du genre) ne sont pas dignes de confiance et présentent de nombreux problèmes de sécurité.

Si les applications les plus populaires (et par coïncidence les plus problématiques) sont de loin Zoom & WhatsApp (et je les traiterai plus en détail ci-dessous), il existe bien évidemment de nombreux autres services de télécommunications/vidéoconférences. Je pense cependant que ces quelques divers exemples permettront de mettre en évidence l'absolue nécessité de ne pas faire confiance à ces plateformes à la fois sur la question de l'utilisation abusive des données collectées par la société mère, mais aussi quant à la facilité avec laquelle une entité étrangère pourrait avoir accès à ces données en raison de leur faible sécurité - et ce qu'il s'agisse d'un hacker isolé ou d'un État étranger. 

Est-il néanmoins possible de trouver une plateforme sûre et fiable ? Oui, même si le risque zéro n'existe probablement pas - nous y reviendrons plus tard. 

<br>

<b>Zoom |</b> [Zoom Zoom Zoom](https://www.youtube.com/watch?v=bkr7JGSY_VI) [10], parlons-en. L'utilisation de [Zoom](https://en.wikipedia.org/wiki/Zoom_Video_Communications) [11] a considérablement augmenté ces dernières semaines en raison de la nécessité pour beaucoup de télétravailler et de participer à des visioconférences. En effet, la firme similarweb spécialisée dans l'analyse de l'utilisation des sites internet et plateformes estime que Zoom [connait une augmentation de son utilisation de plus de 650%](https://www.similarweb.com/fr/website/zoom.us#overview) [12] depuis Mars.

Zoom est une compagnie établie et existante depuis de nombreuses années puisque celle-ci édite la première version de son application en 2013. Peut-être alors pourrait-on supposer que celle-ci est plus fiable et moins sujette à des failles de sécurité grace à son ancienneté et donc son expérience? Détrompez-vous. [Les problèmes sont nombreux au sein de Zoom](https://www.theguardian.com/technology/2020/apr/02/zoom-technology-security-coronavirus-video-conferencing) [13], tant en ce qui concerne le respect de la vie privée que les questions de sécurité.

Commençons par ce qu'il y a peut-être de moins grave: le ["Zoom-Bombing"](https://www.fbi.gov/contact-us/field-offices/boston/news/press-releases/fbi-warns-of-teleconferencing-and-online-classroom-hijacking-during-covid-19-pandemic) [14], que le FBI décrit ici comme une forme de "*teleconference hijacking*" fait référence à des individus indésirables qui se joignent à des appels Zoom dans le but de harceler les personnes qui s'y trouvent, soit en criant des injures, en diffusant de la musique forte, ou en affichant du contenu sensible par le biais de leur flux vidéo. Si Zoom se défend en expliquant qu'il est possible pour l'utilisateur qui créé une conférence Zoom [de se prémunir de ce genre de choses en activant certain paramètres](https://blog.zoom.us/wordpress/2020/03/20/keep-the-party-crashers-from-crashing-your-zoom-event/) [15], il s'agit néanmoins d'une négligence de la part de Zoom puisque celle-ci identifie les appels par une URL basée sur un simple numéro court qui peut ensuite être utilisée pour rejoindre les-dits appels à condition que le verrouillage par mot de passe de ceux-ci n'ait pas été activé. Comme le souligne la firme de sécurité Checkpoint dans [un rapport établi en Janvier](https://research.checkpoint.com/2020/zoom-zoom-we-are-watching-you/) [16], il s'agit d'une négligence de sécurité puisqu'il est très simple pour un attaquant de trouver "au hasard" ces numéros en raison de leur courte taille.

Mais nous ne faisons qu'effleurer la surface pour le moment. Savez-vous ce que signifie le terme de "chiffrement de bout en bout"? Aussi connu sous le nom de [End-to-End Encryption (ou E2EE)](https://fr.wikipedia.org/wiki/Chiffrement_de_bout_en_bout) [17] il s'agit d'un système de communication simple où seules les personnes qui communiquent peuvent lire les messages échangés -- c'est le strict minimum pour pouvoir considérer une application de communication comme étant sécurisée. En principe, il empêche l'écoute électronique, y compris par les fournisseurs de télécommunications, par les fournisseurs d'accès Internet et même par le fournisseur du service de communication. Et Zoom n'hésite pas à l'utiliser comme argument de marketing [alors même que celle-ci ne propose en réalité aucun chiffrement de la sorte](https://twitter.com/trevortimm/status/1244990579705958400) [18]. Problématique n'est-ce pas? Si la [compagnie reconnait son tort](https://theintercept.com/2020/03/31/zoom-meeting-encryption/) [19], l'application reste néanmoins toujours aussi peu sécurisée. Un porte-parole de celle-ci explique à The Intercept que:

> "Currently, it is not possible to enable E2E encryption for Zoom video meetings. Zoom video meetings use a combination of TCP and UDP. TCP connections are made using TLS and UDP connections are encrypted with AES using a key negotiated over a TLS connection." -  [Zoom à The Intercept](https://theintercept.com/2020/03/31/zoom-meeting-encryption/) [19]
 
En termes moins barbares, le protocole de sécurité utilisé par Zoom est le même que celui utilisé pour accéder à un site protégé par HTTPS, cela signifie donc que lorsque vous organisez une réunion Zoom, les flux vidéo et audio restent protégés de toute personne qui espionnerait votre réseau Wi-Fi, mais pas de l'entreprise elle-même. Bien sûr, la société prétend qu'elle ne fait rien avec vos données, mais faut-il faire confiance à une compagnie qui ment ouvertement et qui ne se rectifie qu'après avoir été mise à mal dans la presse? Ce n'est là pas une politique que je trouve honnête.

Bien sûr, c'est aussi sans compter le fait qu'il y a peu, la politique de confidentialité de Zoom informait les utilisateurs que [leurs messages et fichiers partagés par le biais de l'application pouvaient être analysés par des systèmes automatisés afin de fournir un ciblage publicitaire](https://www.consumerreports.org/video-conferencing-services/zoom-teleconferencing-privacy-concerns/) [20]. Si cette politique a depuis été retirée (on peut supposer qu'[un article de blog en provenance d'Harvard](https://blogs.harvard.edu/doc/2020/03/27/zoom/) [21] n'y est pas pour rien - encore une fois Zoom se comporte abusivement jusqu'à ce qu'on la rappelle à l'ordre), je pense à titre personnel que cela n’incite pas à la confiance. 

Nous avons évoqué les mauvais choix de design qui facilitent le spamming (pollupostage, en "bon" français) par des individus malhonnêtes, nous avons parlé de l'absence du chiffrement de bout en bout et des politiques d'entreprise/marketing lamentables de Zoom. Concentrons-nous maintenant sur les véritables failles de sécurité et commençons par un petit retour en arrière en 2019. 

À l'époque, [il avait été révélé](https://medium.com/bugbountywriteup/zoom-zero-day-4-million-webcams-maybe-an-rce-just-get-them-to-visit-your-website-ac75c83f4ef5) [22] que Zoom avait discrètement [installé un serveur web caché sur les appareils des utilisateurs](https://www.wired.com/story/zoom-bug-webcam-hackers/) [23] (au moins 22 milion de personnes affectées) qui permettait à ce derniers [d'être ajoutés à un appel sans leur permission](https://epic.org/privacy/zoom/EPIC-FTC-Complaint-In-re-Zoom-7-19.pdf) [24]. Inutile, je l'espère, d'expliquer en quoi une telle chose n'est bien entendu en aucun cas acceptable en ce qu'elle consiste une faille de sécurité considérable et qu'elle représente une violation de la vie privée des utilisateurs. Dans un geste sans précédent, [Apple avait décidé de mettre à jour son système d'exploitation afin de désactiver cette fonctionnalité](https://techcrunch.com/2019/07/10/apple-silent-update-zoom-app/) [25] pour protéger ses utilisateurs. Rien que cela devrait suffire à expliquer à quel point la situation était désastreuse.

Vous en voulez plus ? En voici d'autres. Il y a à peine un mois, [il a été signalé que l'installateur de Zoom pour macOS prenait le contrôle des privilèges d'administrateur](https://twitter.com/c1truz_/status/1244737672930824193) [26] pour obtenir l'accès root à l'ordinateur d'un utilisateur. Cet accès pouvait être utilisé de manière abusive pour installer subrepticement des programmes à l'insu de l'utilisateur, y compris la possibilité d'accéder à la webcam et au microphone de l'ordinateur. Comme l'explique celui qui a mis au jour ce problème: 

> "This is not strictly malicious but very shady and definitely leaves a bitter aftertaste. The application is installed without the user giving his final consent and a highly misleading prompt is used to gain root privileges. The same tricks that are being used by macOS malware." - [Tweet de @c1truz_](https://twitter.com/c1truz_/status/1244737676990976001) [27]
 
Si il n'y a pas *malum in se*, comme le rappelle l’intéressé cette méthode est similaire à celle qu'emploierait un virus afin de prendre le contrôle de votre ordinateur. Une fois encore [ces problèmes ont été résolus](https://twitter.com/c1truz_/status/1245767226499764225) [28] après avoir été portés à l'attention du public. 

Si il est bien entendu louable que Zoom résolve la plupart de ces divers problèmes, il ne faut néanmoins pas oublier qu'ils sont le reflet d'une application non sécurisée et peu fiable. Pire encore, rien de ce que nous avons listé jusqu'à présent n'est le résultat de bugs déplorables (mais indépendant de la volonté de l'entreprise) survenus au cours du développement de l'application. Ils sont tous la conséquence de mauvaises décisions de conception (entièrement assumées) où la sécurité de l'utilisateur a été volontairement ignorée. 

Veuillez par ailleurs noter qu'il existe de nombreuses autres failles de sécurité ([révéler le mot de passe d'une session utilisateur Windows](https://twitter.com/hackerfantastic/status/1245133371262619654) [29] en est une, par exemple), mais afin de vous épargner la lecture fastidieuse des détails techniques, passons à autre chose. 

Parlons, par exemple, de la vente de données par Zoom et de ses liens avec Facebook (Facebook? Vente des données? [Surprenant.](https://en.wikipedia.org/wiki/Facebook%E2%80%93Cambridge_Analytica_data_scandal) [30]) - En effet [un rapport de Motherboard](https://www.vice.com/en_us/article/k7e599/zoom-ios-app-sends-data-to-facebook-even-if-you-dont-have-a-facebook-account) [31] a révélé que Zoom envoyait les données des utilisateurs de son application iOS à Facebook à des fins publicitaires, même si l'utilisateur n'a pas de compte Facebook. Zoom a modifié certaines de ses politiques en réponse (à son habitude) et a promptement déclaré que:

> "[Zoom] has never sold user data in the past and has no intention of selling users’ data going forward." - [Communiqué Officiel de Zoom](https://blog.zoom.us/wordpress/2020/03/29/zoom-privacy-policy/) [39]

Cependant le rapport de Motherboard a été cité dans [un procès intenté devant un tribunal fédéral en Californie](https://www.scribd.com/document/454166545/Zoom-Lawsuit) [32] en Avril, accusant Zoom de ne pas "*protéger correctement les informations personnelles de millions d'utilisateurs de plus en plus nombreux*" sur sa plateforme.

Autre point: s'il n'est bien entendu pas souhaitable de tomber dans la paranoïa et la sinophobie, il reste intéressant de relever qu'une partie du trafic de Zoom passe par la Chine et [qu'un rapport](https://abcnews.go.com/International/intel-report-warns-zoom-vulnerable-foreign-surveillance/story?id=70376203) [33] (quoique controversé) rédigé conjointement aux Etats Unis par le Department of Homeland Security’s Cyber Mission Center et le Counterintelligence Mission Center note que:

> "Zoom's sudden immense growth and use across both public and private sector entities in combination with its highly publicized cybersecurity issues creates a vulnerable, target-rich environment." - [Rapport Officiel obtenu par ABCNews](https://abcnews.go.com/International/intel-report-warns-zoom-vulnerable-foreign-surveillance/story?id=70376203) [33]

et en concluent que toute organisation utilisant actuellement - ou envisageant d'utiliser - Zoom se doit d'évaluer le risque de son utilisation. 

Il faut toutefois ne pas oublier de préciser que [de nombreux autres problèmes de confidentialité et de sécurité ont été (ou n'ont pas encore été) résolus par Zoom au cours des dernières semaines](https://www.tomsguide.com/news/zoom-security-privacy-woes) [34], ce qui dénote bien entendu un effort de la part de la compagnie en vue d'améliorer leur application. 

Pour conclure avec Zoom, je pense qu'il est également intéressant de noter que plusieurs entités, dont [Google](https://www.techradar.com/news/zoom-banned-from-google-worker-laptops) [35], le [New York City Department of Education](https://www.washingtonpost.com/education/2020/04/04/school-districts-including-new-york-citys-start-banning-zoom-because-online-security-issues/) [52], ou encore [Taiwan, et l'Allemagne](https://www.techradar.com/news/zoom-banned-for-official-use-in-taiwan) [36], ont interdit l'utilisation de Zoom en leur sein pour des raisons de confidentialité et de sécurité. [Enfin, je partage ici la conclusion de Brian Feldman](https://nymag.com/intelligencer/2020/04/the-zoom-app-has-a-lot-of-security-problems.html) [37] très rationnelle (traduite EN->FR): 

> "La question qui se pose à vous, une personne normale avec des problèmes normaux, est la suivante : "Dois-je me soucier de tout cela ?" Personnellement, je pense que vous devriez vous en soucier, mais je suis moins sûr que vous devez vous en inquiéter. Les failles de sécurité documentées de Zoom nécessiteraient un haut niveau de ciblage et de précision pour être pleinement exploitées. Ce n'est pas le genre de sécurité laxiste qui pourrait entraîner une fuite de données catastrophique et généralisée ; c'est le genre de sécurité laxiste qui laisse les cibles individuelles de grande valeur vulnérables. Pour vous, la question qui entoure Zoom devient alors : "Suis-je vraiment si important ?" Si vous travaillez pour une entité gouvernementale ou une multinationale, ou si vous manipulez des informations sensibles comme des données médicales ou financières, envisagez peut-être d'utiliser certains des concurrents de Zoom." - [Article NYMag](https://nymag.com/intelligencer/2020/04/the-zoom-app-has-a-lot-of-security-problems.html) [37]

<br>

<b>WhatsApp |</b> En ce qui concerne le respect de la vie privée ou la sécurité des utilisateurs, Facebook est une déchetterie et WhatsApp en est le déchet cardinal (*sic*). Si Zoom semble souffrir de nombreux défauts de sécurité, ce n'est rien par rapport à WhatsApp. Afin d'éviter d'alourdir ce papier inutilement nous allons passer outre les chefs d'accusation contre Facebook si nombreux qu'ils méritent à eux-seuls [leur propre article Wikipédia](https://en.wikipedia.org/wiki/Criticism_of_Facebook) [1,2], mais ne les oublions surtout pas pour autant. 

En effet, WhatsApp est un produit de Facebook et il est de loin son produit le moins bien sécurisé. Car le sujet a déjà été traité de manière assez extensive et honnête par Pavel Durov, PDG de Telegram (dont nous parlerons à nouveau dans quelques instants) ce que vous vous apprêtez à lire est une retraduction de cet article issu de son blog personnel: "[Why Using WhatsApp Is Dangerous](https://telegra.ph/Why-Using-WhatsApp-Is-Dangerous-01-30-4)" [38]. Veuillez noter que celui-ci a été publié le 30 Janvier 2020 mais reste d'actualité.

> **Why Using WhatsApp Is Dangerous** - Pavel Durov - 30 Janvier, 2020
> 
> Il y a quelques mois, j'ai écrit un article sur [une porte dérobée de WhatsApp qui permettait aux pirates d'accéder à toutes les données de n'importe quel téléphone équipé de WhatsApp](https://www.techspot.com/news/82843-hackers-can-use-whatsapp-flaw-way-handles-video.html) [40]. Facebook, sa société mère, a déclaré à l'époque qu'[elle n'avait aucune preuve que cette faille avait été utilisée par des pirates](https://www.zdnet.com/article/attackers-using-whatsapp-vulnerability-triggered-by-video-files-can-remotely-execute-code/) [41]. 
>
> La semaine dernière (*autour du 20 Janvier 2020; NDLA*), il est apparu clairement que cette porte dérobée avait été exploitée pour extraire des communications privées et des photos de Jeff Bezos - la personne la plus riche de la planète - [qui s'est malheureusement fié à WhatsApp](https://www.popularmechanics.com/technology/security/a30666361/jeff-bezos-whatsapp-hack/) [42]. Comme l'attaque semblait provenir d'un gouvernement étranger, [il est probable que d'innombrables autres dirigeants d'entreprises et de gouvernements aient été pris pour cible](https://www.forbes.com/sites/thomasbrewster/2020/01/22/if-jeff-bezos-iphone-can-be-hacked-over-whatsapp-so-can-yours/) [43].
> 
> [Dans mon post de Novembre](https://t.me/durov/109) [44], j'évoquais la possibilité qu'une telle chose se produise. [Les Nations Unies recommandent maintenant à leurs fonctionnaires de retirer WhatsApp de leurs appareils](https://www.reuters.com/article/us-un-whatsapp/u-n-says-officials-barred-from-using-whatsapp-since-june-2019-over-security-idUSKBN1ZM32P) [45], tandis que les proches de Donald Trump [ont été invités à changer de téléphone](https://www.cnn.com/2020/01/23/politics/jared-kushner-saudi-arabia-jeff-bezos-phone-hack/index.html) [46]. 
>
>[...]
>
> Dans son marketing, WhatsApp parle de "chiffrement de bout en bout" (*à l'instar de Zoom; NDLA*) comme s'il s'agissait d'une incantation magique (*sic*) qui, elle-seule, [est censée sécuriser automatiquement toutes les communications](https://twitter.com/BBCr4today/status/1220631511101210630) [47]. Cependant, cette technologie n'est pas une solution miracle qui peut à elle seule garantir une confidentialité absolue. (*Il reste bien entendu de loin préférable d'avoir une telle encryption (WhatsApp) qu'une encore moins sécurisée (Zoom), cependant ni l'une ni l'une ne sont infaillibles; NDLA*)
> 
> Telegram a déployé le chiffrement de bout en bout pour les communications de masse des années avant que WhatsApp ne lui emboîte le pas, et nous avons été conscients non seulement des points forts, mais aussi des limites de cette technologie. (*En tant que PDG de Telegram, il est évident que Pavel Durov compare WhatsApp à sa propre application. Ses propos n'en sont pas moins crédibles pour autant; je viendrais néanmoins les nuancer plus loin; NDLA*) D'autres aspects d'une application de messagerie peuvent rendre le cryptage de bout en bout inutile. Voici trois exemples de ce qui peut mal tourner:
>
> Premièrement, il y a les sauvegardes. Les utilisateurs ne veulent pas perdre leurs discussions lorsqu'ils changent d'appareil, ils les sauvegardent donc dans des services comme iCloud - souvent sans se rendre compte que leurs sauvegardes ne sont pas cryptées. [Le fait qu'Apple ait été forcé par le FBI à abandonner ses plans de cryptage pour iCloud est révélateur](https://www.reuters.com/article/us-apple-fbi-icloud-exclusive/exclusive-apple-dropped-plan-for-encrypting-backups-after-fbi-complained-sources-idUSKBN1ZK1CT) [48].  
>
> Deuxièmement, il existe des portes dérobées. De nombreuses institutions ne sont pas très fan des données cryptées, et obligent les développeurs d'applications à y intégrer secrètement des vulnérabilités. Je le sais car certaines nous (*Telgram, NDLA*) ont contactés et ont refusé de coopérer. C'est pour cela par exemple que Telegram est interdit dans certains pays où WhatsApp n'a pas de problèmes avec les autorités, [notamment en Russie et en Iran](https://www.theverge.com/2018/4/13/17233112/russia-telegram-ban-court-ruling) [49,50]. 
>
> Les portes dérobées sont généralement camouflées comme des failles de sécurité "accidentelles". Rien que l'année dernière, 12 failles de ce type ont été découvertes dans WhatsApp. [Sept d'entre elles étaient critiques - comme celle qui a valu à Jeff Bezos le vol de ses données](https://www.businessinsider.fr/us/jeff-bezos-hack-whatsapp-disclosed-security-flaws-last-year-ft-2020-1) [51]. [...] Telegram, une application utilisée par des centaines de millions de personnes, y compris des chefs d'État et de grandes entreprises, n'a pas connu de problèmes de cette gravité au cours des six dernières années. (*Donc depuis la création de Telegram, NDLA*)
>
> Troisièmement, il existe des failles dans la mise en œuvre du cryptage. Comment peut-on être sûr que le cryptage que WhatsApp prétend utiliser est celui qui est réellement mis en œuvre dans ses applications ? Leur code source est caché et les binaires des applications sont obscurcis, ce qui les rend difficiles à analyser. [...] (*Cela signifie donc qu'un chercheur, un indépendant, ou un quelconque tiers ne peut s'assurer de ses propres yeux que WhatsApp utilise des technologies sécurisées; NDLA*)
> 
> Ne vous laissez pas tromper par l'équivalent technologique des magiciens de cirque qui voudraient concentrer votre attention sur un aspect isolé tout en exécutant leurs tours ailleurs. Ils veulent que vous considériez le cryptage de bout en bout comme la seule chose à prendre en compte pour la protection de la vie privée. La réalité est beaucoup plus compliquée. 

Me voici de nouveau à la barre. Tout ce que Pavel Durov a souligné dans son billet de blog que j'ai traduit ci-dessus est exact, même s'il cherche bien évidemment à mettre son service, Telegram, en valeur. Bien sûr, il n'y a pas de honte à cela, étant donné qu'il ne ment pas et ne fait que promouvoir une application objectivement plus sûre. Notez cependant que Telegram ne supporte actuellement pas les appels vidéo, mais bien uniquement les appels audio et l'échange de messages textuels. 

<br>

<b>Conclusion |</b> Il me semble évident à ce stade de conclure que WhatsApp ou Zoom ne sont pas des choix raisonnables pour une communication sécurisée dans un cadre professionnel. 

De manière plus générale, la conclusion empruntée au NYMag que je citais plus haut pour Zoom s'applique aussi à WhatsApp et à tout autre service de téléconférence de manière générale. Je la cite à nouveau ici (toujours traduite de l'anglais):

> "La question qui se pose à vous, une personne normale avec des problèmes normaux, est la suivante : "Dois-je me soucier de tout cela ?" Personnellement, je pense que vous devriez vous en soucier, mais je suis moins sûr que vous devez vous en inquiéter. Les failles de sécurité documentées de Zoom nécessiteraient un haut niveau de ciblage et de précision pour être pleinement exploitées. Ce n'est pas le genre de sécurité laxiste qui pourrait entraîner une fuite de données catastrophique et généralisée ; c'est le genre de sécurité laxiste qui laisse les cibles individuelles de grande valeur vulnérables. Pour vous, la question qui entoure Zoom devient alors : "Suis-je vraiment si important ?" Si vous travaillez pour une entité gouvernementale ou une multinationale, ou si vous manipulez des informations sensibles comme des données médicales ou financières, envisagez peut-être d'utiliser certains des concurrents de Zoom." - [Article NYMag](https://nymag.com/intelligencer/2020/04/the-zoom-app-has-a-lot-of-security-problems.html) [37]

Mais alors quel service utiliser? Les opinions divergent mais à ce jour il semblerait que Microsoft Teams ou encore Google Meet, par exemple, soient des alternatives préférables à Zoom/WhatsApp. Avec aucun problème de sécurité connu, ces applications ont été créés par des entreprises habituées à traiter des informations sensibles et à les conserver en toute sécurité. Une fois encore, le risque zéro n'existe pas mais WhatsApp et Zoom sont outrageusement non sécurisées et continuer à les utiliser dans un cadre professionnel serait à mon humble avis, une grossière erreur.


<br>

<br>

<br>

## 3. Sources

Notice: Une partie de ces sources ne sont pas réellement référencées dans le document. Pour cause, toute une section du document parlait du service Facebook Rooms, mais celle-ci a finalement été retirée.

1. https://en.wikipedia.org/wiki/Criticism_of_Facebook
2. https://en.wikipedia.org/wiki/Privacy_concerns_with_social_networking_services#Facebook
3. https://www.cnet.com/how-to/messenger-rooms-heres-how-to-use-facebooks-free-new-video-chat-app/
4. https://en.wikipedia.org/wiki/Facebook_Messenger
5. https://www.eff.org/node/101713/
6. https://about.fb.com/news/2020/04/introducing-messenger-rooms/
7. https://www.pocket-lint.com/apps/news/151426-what-is-zoom-and-how-does-it-work-plus-tips-and-tricks
8. https://twitter.com/wongmjane/status/1255913581788327936
9. https://fr.wikipedia.org/wiki/Code_arbitraire
10. https://www.youtube.com/watch?v=bkr7JGSY_VI
11. https://en.wikipedia.org/wiki/Zoom_Video_Communications
12. https://www.similarweb.com/fr/website/zoom.us#overview
13. https://www.theguardian.com/technology/2020/apr/02/zoom-technology-security-coronavirus-video-conferencing
14. https://www.fbi.gov/contact-us/field-offices/boston/news/press-releases/fbi-warns-of-teleconferencing-and-online-classroom-hijacking-during-covid-19-pandemic
15. https://blog.zoom.us/wordpress/2020/03/20/keep-the-party-crashers-from-crashing-your-zoom-event/
16. https://research.checkpoint.com/2020/zoom-zoom-we-are-watching-you/
17. https://fr.wikipedia.org/wiki/Chiffrement_de_bout_en_bout
18. https://twitter.com/trevortimm/status/1244990579705958400
19. https://theintercept.com/2020/03/31/zoom-meeting-encryption/
20. https://www.consumerreports.org/video-conferencing-services/zoom-teleconferencing-privacy-concerns/
21. https://blogs.harvard.edu/doc/2020/03/27/zoom/
22. https://medium.com/bugbountywriteup/zoom-zero-day-4-million-webcams-maybe-an-rce-just-get-them-to-visit-your-website-ac75c83f4ef5
23. https://www.wired.com/story/zoom-bug-webcam-hackers/
24. https://epic.org/privacy/zoom/EPIC-FTC-Complaint-In-re-Zoom-7-19.pdf
25. https://techcrunch.com/2019/07/10/apple-silent-update-zoom-app/
26. https://twitter.com/c1truz_/status/1244737672930824193
27. https://twitter.com/c1truz_/status/1244737676990976001
28. https://twitter.com/c1truz_/status/1245767226499764225
29. https://twitter.com/hackerfantastic/status/1245133371262619654
30. https://en.wikipedia.org/wiki/Facebook%E2%80%93Cambridge_Analytica_data_scandal
31. https://www.vice.com/en_us/article/k7e599/zoom-ios-app-sends-data-to-facebook-even-if-you-dont-have-a-facebook-account
32. https://www.scribd.com/document/454166545/Zoom-Lawsuit
33. https://abcnews.go.com/International/intel-report-warns-zoom-vulnerable-foreign-surveillance/story?id=70376203
34. https://www.tomsguide.com/news/zoom-security-privacy-woes
35. https://www.techradar.com/news/zoom-banned-from-google-worker-laptops
36. https://www.techradar.com/news/zoom-banned-for-official-use-in-taiwan
37. https://nymag.com/intelligencer/2020/04/the-zoom-app-has-a-lot-of-security-problems.html
38. https://telegra.ph/Why-Using-WhatsApp-Is-Dangerous-01-30-4
39. https://blog.zoom.us/wordpress/2020/03/29/zoom-privacy-policy/
40. https://www.techspot.com/news/82843-hackers-can-use-whatsapp-flaw-way-handles-video.html
41. https://www.zdnet.com/article/attackers-using-whatsapp-vulnerability-triggered-by-video-files-can-remotely-execute-code/
42. https://www.popularmechanics.com/technology/security/a30666361/jeff-bezos-whatsapp-hack/
43. https://www.forbes.com/sites/thomasbrewster/2020/01/22/if-jeff-bezos-iphone-can-be-hacked-over-whatsapp-so-can-yours/
44. https://t.me/durov/109
45. https://www.reuters.com/article/us-un-whatsapp/u-n-says-officials-barred-from-using-whatsapp-since-june-2019-over-security-idUSKBN1ZM32P
46. https://www.cnn.com/2020/01/23/politics/jared-kushner-saudi-arabia-jeff-bezos-phone-hack/index.html
47. https://twitter.com/BBCr4today/status/1220631511101210630
48. https://www.reuters.com/article/us-apple-fbi-icloud-exclusive/exclusive-apple-dropped-plan-for-encrypting-backups-after-fbi-complained-sources-idUSKBN1ZK1CT
49. https://www.theverge.com/2018/4/13/17233112/russia-telegram-ban-court-ruling
50. https://www.nytimes.com/2018/04/13/world/europe/russia-telegram-encryption.html
51. https://www.businessinsider.fr/us/jeff-bezos-hack-whatsapp-disclosed-security-flaws-last-year-ft-2020-1



<br>

<br>

<br>

## 4. Contact
Mathis Ivars - mathis-ivars@hotmail.fr - 07.49.35.78.74

